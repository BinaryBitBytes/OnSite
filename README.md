# OnSite
Equipment Inspection Log &amp; Safety Data Sheet E-Tool that empowers users to meet safety compliance while working with tools, equipment, vehicles,  &amp; job site materials. Using geo location, photos, forms, &amp; checklist stored in a data base for all users within an org to meet safety standards to reduce paper work &amp; provide solutions fast. 

## User Story
As a **Business Owner** I want a tool for the team to use that allows for record keeping of safety related documents & to provide accessible resources to my personnel for when they are on a job site so that they can continue to work safely & have the resources they need on hand to meet safety guidelines set by governing authorities to better protect the interest of the company, employees, & stakeholders.

As a **Safety Manager** I want to oversee & review inspection records submitted by company personnel as well as a more effective method of providing Material Safety Data Sheets that is lightweight, compact, & digitized. I want to be able to ensure that personnel are following safety procedures and protocols by having a method to store, track, & flag inspection reports to make sure everybody is safe and meeting compliance.

As a **Technician** I want an easy web accessible solution to preform my safety checklists and have a place to store my records all in one place to meet compliance requirements. I also need a tool in the field that informs me with data sheets of potentially hazardous materials I could be handling on a job site.

## About the App OnSite
This is a full stack MERN application that allows users to log in to preform their safety inspections on job site equipment such as: vehicles, ladders, lifts, machinery, & tools. The purpose of this app is to document and identify known or realized hazards on a job site to quickly inform the safety team of these potential issues. This application will serve as a one stop shop for pre & post use inspection forms that when submitted by the user the app will then log that entry into the database containing: name of user, date, time, job site location, geographic coordinates, pictures of equipment if needed, & a field for user notes. Another feature of this app will be to provide a QR code database reference system for users to log materials into the database to then generate, log into the database, & print a QR code that can be applied to the material that when scanned will link the user to that materials Safety Data Sheet. Another significant feature is logging the users activity in a log of viewing that document so that the safety manager can identify who is & who is not being compliant on the job when it comes to meeting safety protocols.

### App Development Requirements
- Test Driven Development first
- Authentication: ability to securely log in & to create an account
- Database to store user entries
- Database to store QR Codes & Safety Data Sheets
- Time stamped transactions that also track user geographic location when logged
- Allows for photos to be added to database for an entry
- Catalogues users by: State, Division, & Current Job Site
- Allows for Queries to filter and search by users , activity, date, time & location
