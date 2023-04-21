# CMPINF-0010-Big-Ideas-Final-Project
Final project for CMPINF 0010 at the University of Pittsburgh.

The project is measuing the best place to commit a campital crime within the Pittsburgh area gauged by the the number of police firearm seizures, the amount of serious (capital) crimes, and drug overdoses, which is correlated to drug use. 
Note: We do not condone the use of illegal substances, crime, or any other illegal activity. This project is for statistical, educational, and comical purposes only.

Teamname: This Project is A Giant Waste of Our Time
Team Members: - Owen Finucan (ofinucan7@gmail.com & otf6@pit.edu) and Jonah Smith (jws130@pitt.edu)

Canvas Group Number: Final Project Group 34

We will be looking to find the best area in Pittsburgh to commit capital crime (but we do not advocate doing this).

Datasets Used: 
                  
               - A Community Profile of Pittsburgh Neighborhoods, 1974 (Analysis: Owen Finucan)
                  - https://data.wprdc.org/dataset/a-community-profile-of-pittsburgh-neighborhoods-1974
                  - Gives a list of population and serious criminal activity such as murder, rape, assult, and larceny by region
               - Pittsburgh Police Firearm Seizure (Analysis: Owen Finucan)
                  - https://data.wprdc.org/dataset/pbp-fire-arm-seizures
                  - Gives a list of firearm seizures done by the Pittsburgh Police
               - Pittsburgh Police Arrest Date (Analysis: Jonah Smith)
                  - https://data.wprdc.org/dataset/arrest-data
                  - Gives a list of all arrests by the Pittsburgh police over the past ~7 years, with location, arrest time, arrest reason, and other metrics.
                  
FORMULA:

Each neighborhood will be assigned a point value which will be representative of how great of a place it is to commit capital crime.

Points = crimePoints * 100 / (arrestPoints * gunPoints)
