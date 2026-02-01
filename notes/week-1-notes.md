# How electricity goes from the sun to my house

1. What is electricity?
    1. Electricity is a type of energy that is created by the movement of electrons between two points (eg. A → B) when there is a potential difference between them (a potential energy difference). The movement between these two points is the flow of electric charge and this flow of electric charge between A and B is what we call ‘Electricity’. 
    2. Electricity is the flow of tiny particles we call electrons from one point to another when there is a potential difference between the two points(eg. point A to point B). Imagine a hill ,point A is the top the hill and B is the bottom. When you roll the ball it moves down because of gravity and the difference in the heights between A and B. This is the same with electrons they flow because there is a difference between A and B, electrons move from high to low and that flow from high to low is called electricity.
    3.  
2. What’s the difference between **power (kW)** and **energy (kWh)**?
    1. kW is the Kilowatts or the amount of power something uses at given given moment, A 1kW microwave or a 2kW or a 10kW tv. Where kWh is an overall sum of how many kW (kilowatt) are used per h (hour). For example a 1kW dryer used of 1 hour = 1kWh , a 2kW dryer running for 1 hour = 2kWh, a 2kW dryer running for 30min = 1kW.
    
3. When does a solar panel produce the *most* electricity?
    1. Around noon, solar PV responds to light, stronger sunlight generally means more electricity.
    
4. When does it produce **zero**?
    1. Solar panels do not produce any electricity during the night or monsoon

## Time-window

### How long will the simulation run ?

THe simulation will run for 24 hours, 12:00am - 12:00am

### Where the simulation starts

The simulation is begin at 12:00am

### Where the simulation ends 

The simulation will end at 11:59pm

### The one variable that changes over time ?

The Sunlight/UV intensity changes overtime 

### Shape of output

When the outout is at 0 the graph should display that, it should start to increase and look as if its
climbing a mountain at about 9am slowing increasing to a peak at 12pm, shortly after it should begin to slowly decline from its peak
with significant drop off by 6:00pm or sunset

### The timestep loop

For each timestep the simulator will advance the time, 
based on the models assumption it will then determine the UV/sunlight level for that time,
measure and record the UV/Sunlight output,
it will then continue onto the next time stamp

### Things that should never happen

- The simulator should not record the same value twice
- Should not record unrealistic values
- Should not miss any time stamps
- Should not continue after 24 hours
