# Parking Lot System - README

## Purpose:
This system simulates the management of a parking lot, including vehicle assignments, ticketing, and payment processing.

## How to Run:
1. Compile all Java files in the `1_code` folder.
2. Run the main class `ParkingLotSystem.java` to execute the system.

## Features:
- Assign parking spots to vehicles.
- Track the entry and exit times of vehicles.
- Handle payments and issue tickets.
- Show parking lot availability.

## Requirements:
- Java JDK 8 or higher.

2. To run unit tests, use a testing framework like JUnit. 
Ensure all the classes are compiled before running the tests.

Documentation- 

# README4.txt - Instructions to Run Data Collection Scripts

## Overview
This document provides instructions on how to run the data collection script for the Parking Lot Management System. The script simulates vehicle entries and exits, records the parking lot's availability, and logs the data in a text file.

## Prerequisites
Before running the data collection script, make sure the following are set up:

1. **Java Development Kit (JDK)** installed on your system. You can download the JDK from [Oracle's website](https://www.oracle.com/java/technologies/javase-downloads.html).
2. **NetBeans IDE** (or any Java IDE of your choice) for easy execution, or you can run the program via the command line.

## Steps to Run the Data Collection Script

1. **Download the Project Files**:
   - Ensure that you have downloaded the entire Parking Lot Management System project, including the `ParkingLot`, `TicketingSystem`, and `PaymentSystem` classes.

2. **Compile the Code**:
   - If using NetBeans, open the project in the IDE, and NetBeans will automatically compile the project.
   - If using the command line, navigate to the project directory and use the following command:
     ```
     javac -d bin src/com/mycompany/parkinglotsystem/*.java
     ```

3. **Run the Data Collection Script**:
   - **Using NetBeans**: Right-click on the `DataCollectionScript.java` file and select **Run File**.
   - **Using the Command Line**:
     - Navigate to the project's root directory.
     - Use the following command to run the script:
       ```
       java -cp bin com.mycompany.parkinglotsystem.DataCollectionScript
       ```

4. **View the Results**:
   - After running the script, the parking lot data will be logged in the file `parking_data_log.txt` in the root directory of the project.
   - Open the `parking_data_log.txt` file to view the details of the parking lot availability, vehicle assignments, and exit times.


