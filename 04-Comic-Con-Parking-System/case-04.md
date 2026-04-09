# Case Study: Database Design for Comic-Con Event Parking System

## Problem Statement

A large convention venue hosts Comic-Con India, where thousands of visitors arrive across multiple days for anime screenings, cosplay competitions, gaming showcases, creator meetups, merchandise zones, and panel discussions.

During the event, people arrive using bikes, cars, SUVs, cabs, and EV vehicles. The venue has a structured parking facility divided into multiple zones and levels. Some parking areas are reserved for cosplayers with props, exhibitors, creators, VIP guests, staff members, and EV charging vehicles.

Whenever a vehicle enters the parking facility, the system generates a parking ticket and assigns a suitable parking spot depending on vehicle type and availability. When the vehicle exits, the system records exit time and calculates the parking fee.

The venue management wants a system that can track:

* Vehicles entering the parking facility
* Vehicle categories
* Parking spot allocation
* Reserved parking categories
* Entry and exit timestamps
* Parking sessions
* Payment status
* Spot availability across zones and levels

This is a multi-zone event parking system where vehicle types, access categories, sessions, tickets, and payments must be modeled properly.

## Objective

Design an ER diagram for this parking system.

## Functional Expectations

Your design should support answering the following:

* What vehicles entered the parking facility?
* What type of vehicle entered?
* Which parking spot was assigned?
* Which zone or level does that parking spot belong to?
* Was the parking spot reserved for exhibitors, VIP guests, staff, or EV charging?
* When did the vehicle enter the facility?
* When did the vehicle exit the facility?
* What ticket was issued for the parking session?
* Can one vehicle visit the venue multiple times across different days?
* Can one parking spot be reused across multiple parking sessions?
* How is parking availability tracked?
* How are parking charges calculated?
* How is payment recorded for each parking session?
* Can special access categories (cosplayers, exhibitors, VIP guests, staff) be represented?
* Can the system track which vehicles are currently parked inside the venue?

## Scope of ER Diagram

Your ER diagram should include:

* Vehicles
* Vehicle categories
* Parking spots
* Parking spot categories
* Parking zones or levels
* Parking tickets
* Parking sessions (entry and exit tracking)
* Payment records
* Primary keys and foreign keys
* Relationships and cardinality

## Design Considerations

* One vehicle can enter multiple times during the event.
* One parking spot can serve multiple vehicles over time.
* Parking sessions should store entry and exit timestamps.
* Tickets and parking sessions may be separate entities.
* Different vehicle types require different parking spot types.
* Some parking spots may be reserved for specific access categories.
* Parking availability must be trackable.
* Zones or levels may contain multiple parking spots.
* Payments should be connected to parking sessions.
* Avoid putting all logic into a single entity.


## My Approach 

I have thought of metro parking which is a daily use case for me 

Arrive at parking gate -> tell him the Bike Number -> then he will check the vehicle category (for heavy CC's bikes he will allocate another place) -> Allocate spot -> Go and collect the ticket -> Session starts -> Park the vehicle (after i am enjoying in college) -> come and take vehicle out -> calculate the hours & pay the parking charges and zoooooooooooooop
