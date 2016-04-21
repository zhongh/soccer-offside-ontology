Soccer offside analysis ontology
This ontology concentrates on the reasoning and logic of the soccer offside detection use case, the annotation information such as labels, definitions are currently not in the consideration. The final ontology version will be industrial level, though. 

The class names follow Camel rule, individuals are all small letters connected with an underline. 
All definitions and hierarchy are as follows. 

prefix so: <http://tw.rpi.edu/web/Ontologies/2016/Soccer_Offside/>

so:ActivePlay <=> {so:ball_touch, so:opponent_challenge}

so:Ball <=> {so:ball4, so:ball8, so:ball10, so:ball12}
---> BackupBall  (no definition, for data annotation)	
|---> InFieldBall (no definition, for data annotation)

so:Golve <=> {so:goalkeeper_A_left_glove, so:goalkeeper_A_right_glove, 
			  so:goalkeeper_B_left_glove, so:goalkeeper_B_right_glove}

so:Player <=> {so:goalkeeper_A, so:goalkeeper_B, so:player_A1, so:player_A2, 
			   so:player_A3, so:player_A4, so:player_A5, so:player_A6, so:player_A7, 
			   so:player_B1, so:player_B2, so:player_B3, so:player_B4, so:player_B5, 
			   so:player_B6, so:player_B7}

	|-