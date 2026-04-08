# Case Study: Database Design for Clinic Appointment and Diagnostics Platform 

## Problem Statement

A modern clinic wants to organize its operations digitally. The system should manage doctors, patients, appointments, consultations, diagnostic tests, reports, and payments. Patients should be able to visit doctors, book appointments, undergo tests if prescribed, and receive reports later.

The clinic may have multiple doctors across different departments or specialties. A patient may visit the clinic multiple times. During a visit, the doctor may prescribe one or more diagnostic tests. Diagnostic reports may be generated later and should be linked back to the patient and the corresponding doctor visit.

## Objective

Design an ER diagram for this clinic system.

This is not a hospital-level system. Keep the design focused on a clinic that handles appointments, consultations, diagnostics, and reporting in a clean and scalable way.

## Functional Expectations

Your database design should support answering the following:

* Who are the doctors and what are their specialties?
* Which patient booked which appointment?
* What was the appointment status?
* Did the appointment result in a consultation?
* Were any diagnostic tests prescribed?
* What reports were generated?
* Can one patient have multiple visits?
* Can one doctor attend multiple patients?
* Can one consultation lead to multiple tests?
* How should payments be connected to visits or appointments?

## Scope of ER Diagram

Your ER diagram should include:

* Patients
* Doctors
* Appointments
* Consultations / Visits
* Tests / Diagnostics
* Reports
* Payment-related structure (if needed)
* Primary keys and foreign keys
* Relationships and cardinality

## Design Considerations

* Understand the difference between an appointment and an actual consultation/visit.
* Decide whether one appointment always results in one consultation.
* Determine whether diagnostic tests should be linked to appointments, consultations, or patients.
* Define how reports should be associated within the system.
* Consider whether doctor specialty should be modeled as a separate entity or as an attribute.
* Decide whether multiple tests can belong to a single consultation.
