# Software-Architects-meetup
Meetup of Software architects

5 things every Software Architect should know . 
A good Product is successful when its released in the market and easily maintainable. 
1. Who Is your Actual customer ?
2.Learn a new Language ( Business Domain Language . Desirable to have a thorough business domain knowledge)
3."Perfect" vs "Good enough"  --> Do not aim for perfection !!! . Aim for "Good enough" solution and stop when you have achieved it. ( Just enough Architecture)
4.Architectural Trade-offs --> Architecture Tradeoff Analysis method. (ATAM) 
		--> CBAM (Cost benefit ANalysis method) 
		--> Communicate impact. 
		--> Fulfilling every requirement leads to unstable architecture
		--> You cant have it all.
5.Great software is not built , it is grown. (Walking skeleton :)) . Have a grand vision , not grand design


Should the artchitect know the "Why" every time ? 
walking skeleton, but not the first time ?? 

alistair cockburn .. walking skeleton
97 things every architect should know
ibm developer works mar06 eelees
----------------------------------------------------------------------------------------------------------------------------------------------------------

Big Data Streaming. Chetan Kothari

Key Points --> Reference lambda and kappa , storm, spark

Context: 
ecommerce, log analytics, telematics, faraud detection, network Monitoring, network failure prediction, data warehouse augmentation, real time marketing, analysis for IOT.

Reference Lambda Architecture

Input Topic --->RTS  	--->Serving DB Speed Table
			--> Hadoop   --->Batch Table  				Service lAYER 		Application
			
			
Reference Kappa Architecture 
Apache Samza , Spark, storm, flink, amazon kinesis. pentaho( streaming in ETL)


Storm --> storm core, storm trident ( micro batch operation .. so latency in few seconds)
Spark --> spark SQL, Spark streaming, ML Lib, GraphX
Amazon data flow. 
Samza, Flink 

use case  Makemytrip
Actors : hotel booking website , marketing analyst

Sceanario
user segmentation while they are browsing .. for offers
offline user segmentation for next time discounts

Kafka
Sotrm, 
Cloudera
Cassandra
Oracle db
Apapche OOzie
Jersey
timcat
Omniture JS captures events

---------------------------------------------------------------------------------------------------------------------

Introduction to software Licenses  --> nishant krishna
opensource.org/licenses/index.html

permissive License --> BSD, APAche,MIT license ( Best to use OSS) 
Restrictive licenses --> GNU GPL, LGPL, Mozilla Public license ( MPL)

Black Duck Code center
avaya.com/copyright
Black duck Protex helps you to find open source violations

----------------------------------------------------------------------------------------------------------------------


Connect Business and Technology 

multiple products workings towards a common goal --> hence called as enterprise apllication architecture
--> Business
--> Data 
--> Application
--> Technology
Philippe's 4+1 view


IIS/IEC/IEEE 42010
Architecture Framework --> TOGAF, Zachmann, FEAF, MODAF, Krutchen's 4+1 view
The open group togaf
