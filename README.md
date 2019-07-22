# Carbon-Footprint

Application would analyze the average Carbon Footprint of an individual in Oklahoma City and compare the results to the Carbon Footprint per tract in Oklahoma City, OK using the 2010 Census Tract.

# Getting Started

- To analyze the Carbon Footprint per tract in Oklahoma City, OK, One would have to calculate the average persons Carbon Footprint in Oklahoma and multiply by the population in the tract. 
- https://data.okc.gov/portal/page/viewer?datasetName=Census%20Tracts%202010&view=map is the primary source in gatering census data per tract in Oklahoma City, OK. 
- To gather Carbon Footprint data for an individual, one would have to answer the questions provded in the application.
- Calculations data for Carbon Footprint is provided at: http://shrinkthatfootprint.com/calculate-your-carbon-footprint
- Might have to Calculate per state of 2010 and divide by the population of 2010 to get per capita
- OR
- Get a average of emissions for Types of Housing, Per Capita, Per Vehicle, etc.
# Questions
- House or Apartment?
- People in Household?
- Car, Truck, Bus?
- Meats, Vegetarian, Vegan?
# Calculations
- **Housing**
  - Electricity : use (kWh/yr) * EF (kg CO2e/kWh) = emissions (kg CO2e/yr)
  - Natural Gas : use (therms/yr) * EF (kg CO2e/therms) = emissions (kg CO2e/yr)
  - Fuel Oil: use (litres/yr) * EF (kg CO2e/litre) = emissions (kg CO2e/yr)
  - LPG : use (litres/yr) * EF (kg CO2e/litre) = emissions (kg CO2e/yr)
  - Waste : use (kg/week) * 52 * EF (kg CO2e/kg) = emissions (kg CO2e/yr)
  - Water : use (litres/day) * 365 * EF (kg CO2e/kWh) = emissions (kg CO2e/yr)
- **Travel**
  - Vehicle: Distance (km/yr) /*EF (kg CO2e/km) = emissions (kg CO2e/yr)
  - Bus: distance (km/yr) * EF (kg CO2e/km) = emissions (kg CO2e/yr)
  - Metro: distance (km/yr) * EF (kg CO2e/km) = emissions (kg CO2e/yr)
  - Taxi: distance (km/yr) * EF (kg CO2e/km) = emissions (kg CO2e/yr)
  - Rail: distance (km/yr) * EF (kg CO2e/km) = emissions (kg CO2e/yr)
  - Flying : distance (km/yr)* 1.09 * EF (kg CO2e/km) = emissions (kg CO2e/yr)
- **Food**
  - Red meat: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr) 
  - White meat: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Dairy: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Cereals: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Vegetables: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Fruit: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Oils: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Snacks: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
  - Drinks: consumption (kCal/day)*365*EF (kg CO2e/kCal) = emissions (kg CO2e/yr)
- **Spend on New Products**
  - Electrical : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Household : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Clothes : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Medical : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Recreational : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr) 
  - Other : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)

- **Services**
  - Health : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Finance: spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Recreation: spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Education : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Vehicle: spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Communications : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
  - Other : spend ($/month) * 12 * EF (kg CO2e/$) = emissions (kg CO2e/yr)
 
# Conversions

# Development
# User Steps
# Authors
- **Martin Carrion**
# Informational
- **HomePage**
  - ![image](https://user-images.githubusercontent.com/46684934/61652976-d1f71b00-ac7e-11e9-84ff-3ab300c50007.png)












