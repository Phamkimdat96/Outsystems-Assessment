# Outsystems-Assessment

Project: Volunteer Event Management System on OutSystems Platform

Scenario: An NGO needs a web app and a mobile app to manage volunteer events. Volunteers should be able to register, browse upcoming events, sign up, check in, and leave feedback. Admins manage events and monitor volunteer activity.

Requirements:
- (Mandatory) Build a web app for volunteers to:         
     + View a list of upcoming events         
     + See event details         
     + Sign up for events             
     + Submit feedback after the event
- (Mandatory) Consume a public REST API to fetch weather information based on event location and show it on the Event Details screen
- (Mandatory) Create a Timer to send notifications (e.g., reminders) to volunteers before an event starts
- (Optional) Build a mobile app that allows volunteers to:   
    + Check in at events    
    + Use the Camera plugin to upload a photo at check-in
- (Optional) Use a BPT Process to handle post-event processing:    
    + Once an event is completed, automatically trigger a BPT flow that:    
    + Sends follow-up emails    
    + Collects feedback    
    + Generates participation reports
- (Optional) Enable offline functionality:    
    + Volunteers can check in and take notes even without an internet connection    
    + Sync the data once the connection is restored (using Local Storage)
- (Optional) Build a custom Extension to:    
   + Perform a small but useful task (e.g., calculate distance between coordinates, generate custom participation code, sanitize input, etc.)    
   + This Extension must be used at least once in either the mobile or web flow