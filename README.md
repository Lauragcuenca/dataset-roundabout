# dataset-roundabout
Dataset Routes and Roundabout.
This dataset shows information about the parameterization of driving in roundabouts.
The data in this study are heterogeneous data with multiple formats and obtained from various sources. 
This study used data from vehicle sensors, smartphone, roundabout segmentation data, and data obtained from video processing.
The final dataset is embedded in a single CSV file and it is organized in three levels. Specifically, it is a group of routes, where each route is a collection of roundabouts, and each roundabout is divided in segments defined as points of interest.
Each segment has several attributes, namely vehicle speed, steering angle, roundabout diameter, number of lines, and data generated from video processing. Concerning video processing the variables are crowdedness, defined as the number of detected objects in each frame, presence of vulnerable users, the distance to the closest vehicle and its dominant orientation. 
The final dataset is a dataset that contains information related to 33 routes, 337 roundabouts with a total number of 4308 records. 
It includes the tags of id_route, id_roundabout, segment, segment_angle, diameter, lanes, speed_vehicle, steering_angle, Crowdedness_left, Crowdedness_center,Crowdedness_right,Vrus_left,Vrus_center, Vrus_right, Distance_left, Distance_center, Distance_right , Orientation_left, Orientation_center, Orientation_right.

id_route	   Int(11)	  Identifier of route;
id_roundabout	   Int(11)	  Identifier of roundabout;
segment	           Double	  Data segment;
segment_angle	   Varchar(4)	  Segment inner roundabout;
diameter	   Int(11)	  Diameter roundabout;
lanes	           Int(11)	  Lanes roundabout;
Speed_vehicle	   Int(11)	  Speed vehicle in data segment;
Steering_angle     Double	  Steering_angle in data segment;
Crowdedness_left   Int            Number of dynamic agents (left side);
Crowdedness_center Int            Number of dynamic agents (center);
Crowdedness_right  Int            Number of dynamic agents (right side);
Vrus_left          Binary         0=no VRUs, 1=presence of VRUs (left side);
Vrus_center        Binary         0=no VRUs, 1=presence of VRUs (center);
Vrus_right         Binary         0=no VRUs, 1=presence of VRUs (right side);
Distance_left      Double         Distance to the closest vehicle (left side);
Distance_center    Double         Distance to the closest vehicle (center);
Distance_right     Double         Distance to the closest vehicle (right side);
Orientation_left   Int            Dominant orientation bin (left side);
Orientation_center Int            Dominant orientation bin (center);
Orientation_right  Int            Dominant orientation bin (right side);
		
