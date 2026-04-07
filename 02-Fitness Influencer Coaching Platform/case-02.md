# Case Study: Database Design for Fitness Influencer Coaching Platform

## Problem Statement

A fitness influencer has started an online coaching business. Initially, they train a few people through Instagram DMs and video calls. As their brand grows, they now want a platform where they can onboard clients, sell fitness plans, schedule consultations, manage subscriptions, track client progress, and maintain regular check-ins.

Some users join only for consultation. Some buy long-term coaching plans. Some may attend live sessions, while others may only receive a training routine and diet guidance. The platform should also be able to track progress information such as weight, body measurements, check-in reports, and trainer notes.

## Objective

Design an ER diagram for this platform.

This is not a gym management system. This is an online coaching ecosystem where one or more trainers/influencers manage multiple clients and provide structured online fitness support.

## Functional Expectations

Your database design should support answering the following:

* Who are the trainers and who are the clients?
* What plans or coaching programs exist?
* Which client purchased which plan?
* When does a client’s plan start and end?
* Are consultations or sessions being scheduled?
* Are clients submitting check-ins regularly?
* How is client progress being tracked?
* Can multiple clients enroll in the same program?
* Can one trainer handle multiple clients?
* How should payment and subscription information be stored?

## Scope of ER Diagram

Your ER diagram should include:

* User / Client related entities
* Trainer / Coach related entities
* Plans / Programs / Subscriptions
* Sessions / Consultations
* Progress tracking / Check-ins
* Payment-related structure (if needed)
* Primary keys and foreign keys
* Relationships and cardinality

## Design Considerations

* A trainer can coach multiple clients.
* A client may purchase multiple plans over time.
* One plan can be subscribed to by multiple clients.
* Progress tracking should not be stored directly in the user entity.
* Sessions and check-ins should be modeled separately.
* Trainer notes or feedback should be stored appropriately.
* Decide whether diet plans and workout plans should be modeled explicitly or abstractly.
* Keep the design practical and avoid unnecessary complexity.
