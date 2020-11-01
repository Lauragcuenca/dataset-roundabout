# dataset-roundabout
Dataset Routes and Roundabout
This dataset shows information about the parameterization of driving in roundabouts
The data in this study are heterogeneous data with multiple formats and obtained from various sources. 
This study used data from vehicle sensors, smartphone, roundabout segmentation data, and data obtained from video processing. 
The final dataset is a dataset that contains information related to 33 routes, 337 roundabouts with a total number of 4308 records. 
It includes the tags of id_route, id_roundabout, segment, segment_angle, diameter, lanes, speed_vehicle, steering_angle, rain, night, agents_0, agents_1, agents_2, vru_0, vru_1, vru_2, distance_0, distance_1, distance_2, orientation_0, orientation_1, orientation_2, num_imagenes.

Label	          Type	        Description
id_route	      Int(11)	      Identifier of route
id_roundabout	  Int(11)	      Identifier of roundabout
segment	        Double	      Data segment
segment_angle	  Varchar(4)	  Segment inner roundabout
diameter	      Int(11)	      Diameter roundabout
lanes	          Int(11)	      Lanes roundabout
Speed_vehicle	  Int(11)	      Speed vehicle in data segment
Steering_angle  Double	      Steering_angle in data segment
Rain	          Binary 	      0=not rain; 1= rain
Night	          Binary	      0 = not night; 1=night
Agents_0		
Agents_1		
Agents_2		
Vru_0		
Vru_1		
Vru_2		
Distance_0		
Distance_1		
Distance_2		
Orientation_0		
Orientation_1		
Orientation_2		
Num_images		
