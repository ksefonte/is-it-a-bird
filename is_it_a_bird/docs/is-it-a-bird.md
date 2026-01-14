
# Is it a bird? Agile inception deck


## This document serves as an Agile inception deck for the Is it a bird? app project. As this is a learning experience which will result in a fully functioning mobile app, this document often considers two perspectives; 1.) A meta evaluation of the choices pertaining to this project as a developer, and 2.) An evaluation of the product as if it were being taken to market.


## Why are we here?

The stakeholder (myself) has a terrible sense of humour. While exploring a project which increased the developers (also myself) end-to-end knowledge of the software development life-cycle (SDLC), the stakeholder thought of a dad-joke which required identifying a plane in the sky. This application will serve to communicate the punch line, while facilitating developer learning.


## Elevator pitch

*Meta: *For the stakeholder who needs a fully documented, Agile, open-source software project, the “*Is it a bird?”* application is clearly bounded with a rigorous goal compliant with the development and learning requirements. Unlike existing works, our product features novel elements and can be legally published.

*Product: *For the plane fanatic who needs to identify airborne planes, The IIAB app is a plane-identifying tool that tells users details relating to the plane, and/or whether or not it isn’t a bird. Unlike current open source flight data, our product is web based (mobile) and can be accessed by users easily outdoors where the planes are.


## Product box

*Product:*



* Fast cold-load: Ensure app can be brought to functionality quickly to ensure no planes are missed.
* Consistent identification of planes: As above, ensure planes are identified to a high degree of accuracy.
* Intuitive logging: Ensure users are able to view all of the planes that they have logged.

*Meta:*



* Facilitate development of knowledge in SDLC and Agile methodologies
* Sustainable, low cost to deployment and zero cost for development.
* Able to be delivered with certainty.


## NOT List

*Product:*


<table>
  <tr>
   <td>IN SCOPE
   </td>
   <td>OUT OF SCOPE
   </td>
  </tr>
  <tr>
   <td>Identify planes in the users field of vision, including behind cloud cover \
Log and track identified planes per user \
Report and display plane metrics to user in an engaging manner
   </td>
   <td>Identifying birds \
Social functionalities \
Monetisation
   </td>
  </tr>
  <tr>
   <td>UNRESOLVED
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Missed planes - should users know if they missed a potential plane sighting based on current location. \
Exact API to be used - we think we want to use OpenSky, but this needs to be scoped.
<p>
Automatic vs manual discrepancy resolution
   </td>
   <td>
   </td>
  </tr>
</table>


*Meta:*


<table>
  <tr>
   <td>IN SCOPE
   </td>
   <td>OUT OF SCOPE
   </td>
  </tr>
  <tr>
   <td>Agile implementation plan - including inception deck and initial epic planning. \
Technical documentation of software architecture. \
Development of application. \
Testing of application, including generating and documenting unit tests. \
Deployment of application \
Google sign-in or equivalent
   </td>
   <td>Deployment of application to iOS/Android marketplaces
<p>
Monetisation of application.
<p>
Social functionalities.
   </td>
  </tr>
  <tr>
   <td>UNRESOLVED
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Precompiled .IPA/.APK vs user-compiled from source.
<p>
Backend DB in Supabase/Firebase/Other
   </td>
   <td>
   </td>
  </tr>
</table>



## Meet the neighbours

The team consists of the following: \
Primary Business Stakeholder: Kyle \
Product Owner, Product Manager: Kyle \
Lead Developer: Kyle, Claude \
Database Administrator: Kyle

User support: Kyle \
Customer: Kyle \
Vendors:



* Air traffic data provider
* Cloud service providers \



## The solution

Mobile application will leverage the following technologies:



* Flutter (DART)
* SQLite
* Vision Model/LLM. \



## What keeps us up at night?

Not having a feasible Open data source.

Expensive LLM layer.


## Size it up


## I think this project will take 3 months to implement.


## Be clear on what’s going to give

We don’t *need *to incorporate the usage of a Vision Model. Given we’re not identifying anything other than a plane, the vision model might only serve to help differentiate between 


## What’s it going to take?

3 months, 1 developer, $120 in cold hard cash.
