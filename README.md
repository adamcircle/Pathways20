Pathways Overview

# Pathways Overview

Pathways is a prize-winning project submitted at the 2017 HackMIT hackathon created by Adam Circle, Adam Shelby, Steven Moon, and Owen Lynch. Pathways is a mapping application that maximizes its use of the road network to rapidly evacuate people in densely populated areas in the event of a natural disaster or terrorist attack.

## How is Pathways different from other mapping applications?

Whereas commercial mapping applications work by setting a single origin and destination for a single user, Pathways directs drivers away from an epicenter towards a series of safe destinations. Whereas commercial mapping applications optimize for the shortest trip for a single user, Pathways creates routes that maximize the welfare of all drivers.

## How does Pathways work?

Pathways takes advantage of one key property of road traffic: the time it takes to travel a road scales *nonlinearly* with the number of cars on the road. For example, the amount of time it takes to drive a 1 mile section of a 3 lane highway is the same whether there is 1 car or 2 cars on the road; however, when the road is at maximum capacity, adding another car dramatically increases the travel time for every car on the road. Conversely, in surge traffic conditions, we can dramatically *decrease* travel time by removing just a few cars from the road.

Pathways works by allowing an administrator to set up a series of drain nodes on the map. These could be large parks or parking lots where people can safely congregate in the event of an emergency.

During surge traffic events, the fastest route away from the epicenter is rarely the shortest because