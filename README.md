# ChargeSpot: Smart EV Charging Accessibility App

**Live prototype:** https://moulyamallikarjun.github.io/Chargespot/

ChargeSpot is a clickable prototype of a mobile app that helps electric vehicle (EV) owners find available chargers, book slots, and plan long trips. It also gives planners a demand view showing where new chargers are needed.

Created for the 5th semester EVS assignment: *Design a Digital Solution for an Environmental Problem*.

## Problem
Petrol and diesel vehicles are a major source of urban air pollution and carbon emissions. Many people hesitate to switch to EVs because chargers are hard to find, often occupied or out of order, and unevenly spread across cities. Poor charging access slows EV adoption.

## Solution
ChargeSpot makes charging easy to find and plan:
- **Find:** see nearby chargers on a map, filtered by connector type (CCS2, Type 2) and availability.
- **Book:** check speed, price, and wait time, then reserve a time slot.
- **Trip planner:** enter a destination and battery level to get a route with charging stops.
- **Insights:** a planner view showing demand by area and where to install new chargers.

## Technologies
Mobile/Web Application, GIS (map-based), Cloud Computing, Data Analytics, and optional Machine Learning for predicting busy hours.

## Input Data and Sources
| Data | Source |
|---|---|
| Charger locations, connectors, power | OpenChargeMap, OpenStreetMap, government EV station lists |
| Live charger status | Operator APIs, user reports |
| User location, vehicle, battery | Phone GPS, user profile |
| Routes and traffic | OpenStreetMap routing |
| Usage history | App booking records |

## How It Works
**Input:** user location, vehicle type, battery level, destination, and charger data.
**Processing:** filter chargers by compatibility, rank them by distance, wait time, cost and reliability, calculate range and charging stops, update availability from bookings and reports, and analyse usage for peak hours and underserved areas.
**Output:** a map of recommended chargers, booking confirmation, a trip plan with stops, and a demand dashboard for planners.

## Expected Environmental Benefits
- Higher EV adoption, which cuts tailpipe emissions.
- Lower urban air pollution (PM2.5, NOx, CO₂).
- Less fuel wasted searching for chargers.
- Better placement of new chargers using demand data.
- Balanced grid use through booking and peak-time data.

## About This Prototype
This is a front-end prototype built with HTML, CSS, and JavaScript. All stations, bookings, and demand figures are **sample data** for demonstration. It does not connect to real chargers.

## Run Locally
Download `index.html` and open it in any browser. No installation is needed.

## Author
Moulya Mallikarjun
