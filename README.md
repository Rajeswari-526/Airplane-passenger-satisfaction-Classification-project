# Airplane-passenger-satisfaction-Classification-project

Objective: To Predict whether a passenger is satisfied or neutral/dissatisfied 

Overview:
The dataset contains passenger information and service ratings used to classify satisfaction levels.
It has multiple attributes covering demographics, travel details, and service quality.

Data:
Total Records: 103904 

Features (Attributes): 25 
Attribute	Description --
| Attribute                    | Description                                                            |
| ---------------------------- | ---------------------------------------------------------------------- |
| `Gender`                     | Gender of the passenger (Male/Female, encoded as 0/1)                  |
| `Customer Type`              | Loyalty status of the customer (Loyal / Disloyal, encoded)             |
| `Age`                        | Age of the passenger                                                   |
| `Type of Travel`             | Purpose of the flight (Business / Personal, encoded)                   |
| `Class`                      | Seat class of the passenger (Economy, Business, etc., one-hot encoded) |
| `Flight Distance`            | Distance of the flight (in miles)                                      |
| `Departure Delay in Minutes` | Minutes of departure delay                                             |
| `Arrival Delay in Minutes`   | Minutes of arrival delay (missing values filled with mean)             |
| `Checkin service`            | Rating of check-in service (scale 1–5)                                 |

Target Variable: satisfaction → Passenger satisfaction
                                1 → Satisfied
                                0 → Neutral or Dissatisfied

