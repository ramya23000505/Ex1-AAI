<H3> Name: RAMYA R </H3>
<H3>Register No: 212223230169</H3>
<H3> Experiment 1</H3>
<H3>DATE: 28-08-2025</H3>
<H1 ALIGN=CENTER> Implementation of Bayesian Networks</H1>

## Aim :
    To create a bayesian Network for the given dataset in Python
    
## Algorithm:
Step 1:Import necessary libraries: pandas, networkx, matplotlib.pyplot, Bbn, Edge, EdgeType, BbnNode, Variable, EvidenceBuilder, InferenceController<br/>
Step 2:Set pandas options to display more columns<br/>
Step 3:Read in weather data from a CSV file using pandas<br/>
Step 4:Remove records where the target variable RainTomorrow has missing values<br/>
Step 5:Fill in missing values in other columns with the column mean<br/>
Step 6:Create bands for variables that will be used in the model (Humidity9amCat, Humidity3pmCat, and WindGustSpeedCat)<br/>
Step 7:Define a function to calculate probability distributions, which go into the Bayesian Belief Network (BBN)<br/>
Step 8:Create BbnNode objects for Humidity9amCat, Humidity3pmCat, WindGustSpeedCat, and RainTomorrow, using the probs() function to calculate their probabilities<br/>
Step 9:Create a Bbn object and add the BbnNode objects to it, along with edges between the nodes<br/>
Step 10:Convert the BBN to a join tree using the InferenceController<br/>
Step 11:Set node positions for the graph<br/>
Step 12:Set options for the graph appearance<br/>
Step 13:Generate the graph using networkx<br/>
Step 14:Update margins and display the graph using matplotlib.pyplot<br/>

## Program:
''' Type your Code here '''
## Output:
<img width="905" height="770" alt="image" src="https://github.com/user-attachments/assets/4951645e-6636-43fe-9d5b-14e60551260c" />
<img width="903" height="768" alt="image" src="https://github.com/user-attachments/assets/9c4ada80-2e53-4756-9503-ba94849ae697" />
<img width="896" height="698" alt="image" src="https://github.com/user-attachments/assets/621562b3-1e65-4585-a339-715ee82e40e9" />
<img width="1514" height="183" alt="image" src="https://github.com/user-attachments/assets/37cadcf4-78a6-45af-924d-ba5655222fd8" />

## Result:
   Thus a Bayesian Network is generated using Python

