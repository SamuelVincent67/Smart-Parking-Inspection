# Smart-Parking-Inspection

## Overview
This app helps manage parking requests. Vehicle owners can request a parking spot, and inspectors can approve or deny the request based on the availability.

## Technologies used
- **Power Apps (Canvas & Model Driven Apps)** - For entering and managing parking requests and approving parking inspections.
- **Power Automate** - Automated email notifications that send email to vehicle owner's email.
- **Power BI** - Dashboard to visualize the parking usage and request history of the vehicles.

## Data Model
- **Vehicle** : Stores vehicle details to manage all core entities.
- **Parking Requests** : Stores request details of the vehicle.
- **Parking Inspections** : Logs inspectors decisions and timestamp.

## How it works: 
- When the vehicle has to parked the request will be raised.
- The request is stored in the Database table and appears in the parking inspection canvas and model-driven app.
- The inspector reviews the request and either approves or denies it based on the timing and availability of the parking slots.
- Power Automate flow sends an email to the vehicle owner according to the decision.
- Power BI dashboard displays real-time metrics on parking activity.

## Business Impact 
Managing parking manually can be chaotic and inefficient. This solution brings structure, transparncy and automation to the process-making it easier for both vehicle owners and inspectors to coordinate. It's ideal for schools, offices or residential complexes looking to modernize their parking systems.
