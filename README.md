# Flink-Inner-Join
Commad I used to execute the code:
/home/ankur/Flink/flink-1.10.1/bin/flink run -c innerJoinPackage.InnerJoin /home/ankur/Flink-Execution/Jars/innerJoin.jar --input1 file:///home/ankur/Flink-Execution/Inputs/personInnerJoin.txt --input2 file:///home/ankur/Flink-Execution/Inputs/locationInnerJoin.txt --output file:///home/ankur/Flink-Execution/Outputs/innerJoin/IJ


path_for_flink run -c package_name.class_name path_for_jar --input1 path_for_1st_input --input2 path_for_2nd_input --output path_for_output_location
