# Smart India Hackathon Workshop
# Date: 26.08.2024
## Register Number: 212223100052
## Name: SATHYAA R
## Problem Title

E-Waste Facility Locator

## Problem Description

Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.

## Problem Creater's Organization

Ministry of Environment

## Idea

An user-friendly web application that helps people find nearby e-waste drop-off locations and provides information on responsible e-waste disposal.

## Proposed Solution / Architecture Diagram

The application will consist of a frontend for users and a backend database.

Frontend: A user-friendly web interface where users can: Enter their zip code or location. Filter by specific e-waste types (e.g., TVs, computers, batteries). View details of nearby e-waste facilities including: Address Hours of operation Accepted items Contact information

Backend: A database will store information on: E-waste facilities (location, hours, contact info, accepted items) E-waste types (categories and descriptions) User location data (for search functionality) - An anonymized form is recommended to protect privacy

## Use Cases

![Use](https://github.com/user-attachments/assets/6b0b1ef5-3232-4b15-90cc-eacd724fbfcc)

## Technology Stack

Frontend: HTML, CSS, Javascript (consider a framework like React or Vue.js for a more complex UI) Backend: Python (with Django or Flask framework) or Node.js (with Express framework) Database: PostgreSQL or MySQL Maps Integration: Leverage a mapping service API like Google Maps Platform or Leaflet.

## Dependencies

The application relies on a database to store e-waste facility information and user location data (anonymously). Integration with a mapping service API is necessary to display facilities on a map.
