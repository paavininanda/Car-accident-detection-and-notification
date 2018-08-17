# Predicting car accidents and notifying nearest hospital and cabs

## The idea

- This includes real time detection of car accidents using three filters
- The first filter detects sudden jerks in cars
- The second filters uses a video (taken from the car dashboard) as input to detect if an accident has actually taken place 
- The third filter would actually be a 20 second timer which can be switched off in case of a false alarm

After the detection of an accident, both the nearest cab (Uber) and the nearest hospital would be notified so the both of them can take respective actions

## Running the detection system
Just clone the project and run the given python notebook. Supply the correct video sample to the python code to predict the results
