# Learning to hunt: A data-driven stochastic feedback control model of predator-prey interactions

In this repository, we provide the data used in the development, calibration, and validation of the proposed model in the paper titled: "Learning to hunt: A data-driven stochastic feedback control model of predator-prey interactions" by Deze Liu, Mohammad Tuqan, and Daniel Burbano. 

The data is compiled in the excel sheet titled "Data.xlsx." Below is a description of all the files provided in this repository.

- The first sheet, "TimeSeries," consists of the time series used in the papers. Following is the description of the data in each column:
- - ID: Index of each time-step in the data
  - theta_f: The heading angle of the fish in radians
  - theta_d: The heading angle for the dolphin in radians
  - omega_f: The angular-speed of the fish in rad/s
  - omega_d: The angular speed of the dolphin in rad/s
  - D: The euclidean distance between the fish and the dolphin in meters
- The second sheet "Summary" contains a summary of the time-series
- The third sheet "FountainManeuvers&ChasingEps" references the time-steps (in terms of indices range) that correspond to the fish fountain maneuver episodes before, and after the dolphin learnt the fish escape strategy. Additionally, we reference time-steps (in terms of indices ranges) for episodes of the Dolphin in pure chasing mode.

Additionally, the cropped video from which the data in "Data.xlsx" was extracted is provided in the file "Movie.mov". The original video can be found on youtube using the following link:

https://www.youtube.com/watch?v=28gX_eeXd-Q
