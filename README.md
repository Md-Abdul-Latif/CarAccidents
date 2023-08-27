# Car Accidents in New York 
The goal of this project is to infer qualitative data regarding the car accidents in New York City. In particular, it is asked to perform the following queries:
### Q1
Number of lethal accidents per week throughout the entire dataset.
### Q2
Number of accidents and percentage of number of deaths per contributing factor in the dataset.
### Q3
Number of accidents and average number of lethal accidents per week per borough.

#### Compile the project with maven
> mvn  pacage

#### Submit the project through spark-submit, for example:
spark-submit \ <br>
--class "accidents.AccidentCache" \ <br>
--master local[*] \ <br>
--deploy-mode client \ <br>
jar file \ <br>
dataset file folder <br>


