# ETSN15-Software-Requirements-Engineering

## Project Mission v1

1. A product name, different from all other product names in the course.

   - **Product Name:** EasyTrip

2. A short, high-level product description of its background and purpose.

   - **Product Description:** EasyTrip is a comprehensive travel planning tool designed to help travelser find, visualize, and track their trips efficiently. It aims to improve customer satisfaction by providing a comprehensive comparison of flight prices based on different geographic areas.

3. **User Roles:**

   - **Primary:** Travelers aging from 18-65 y/o.
   - **Secondary:** Family members & friends to to whom booked the trip.
   - **Tertiary:** Travel angencies.

4. **Team Roles:**

   - **Project Manager:** Felix Sundholm - Project, Process, Prioritization & Release Manager
   - **Stakeholder Manager:** Ossian Gewert
   - **Elicitation Manager:** André Roxhage - Elicitation & Prototyping Manager
   - **Quality Reqirements Manager:** Simon Jacobsson Persson - Quality Requirements Manager
   - **Data Reqirements Manager:** Jacob Jönsson
   - **Validation Manager:** Jonathan Ahlström
   - **Client:** Views project progress and provides feedback on deliverables.
   - **Tools, Documents, experiences and version manager:** All - Tools, Documents, Experiences & Version Manager

5. A brief description of some external system with which your product interacts.
   - **External Systems:**
     - **Trip planning Integration:** Retrieve flight price information and availability from travel agencies such as SAS, Norwegian, etc.
     - **Map Integration:** Sync with Google Maps for retrieving geographical data, including locations, distances, and travel routes.

---

## Requirement Specifications for EasyTrip

2024-01-22

**Two-step approach:** Domain-level + design-level
**Project Type:** Product dev

**Context Diagram:**
![Context Diagram](resources/contextDiagram.png)

### **Goal-Level Requirements**

1. **Purpose**: Provide an easy-to-use travel planning tool that enhances customer satisfaction by comparing flight prices efficiently across different geographic areas.
2. **Business Goals**:
   - Increase market share by competing with established platforms like Momondo and Flight Scanner.
   - Generate revenue through partnerships with travel agencies and ad placements.
   - Build a user base of travelers who trust the platform for accurate price comparisons.

---

### **Domain-Level Requirements**

1. **User Roles**:

   - **Primary Users**: Travelers aged 18-65, using the platform to plan trips.
   - **Secondary Users**: Family and friends involved in the traveler’s plans.
   - **Tertiary Users**: Travel agencies providing data and bookings.
   - **Non-Obvious Actors**: Customer experience support teams ensuring user satisfaction.

2. **System Interactions**:

   - **Flight Price Integration**: Sync with external travel agencies (e.g., SAS, Norwegian) for flight pricing and availability data.
   - **Map Integration**: Use Google Maps to fetch and display geographical data, travel routes, and distances.

3. **Stakeholders**:
   - Competitors like Momondo and Flight Scanner.
   - Travel agencies providing data partnerships.
   - End users (travelers) providing feedback.
   - Product management and development teams.
   - Airline companies indirectly benefitting from bookings.
   - **Non-obvious Actors:** Support department (Customer Experience)

---

### b. Outline a possible requirement for each of the four requirements levels (kap 1.6, goal, domain, etc.)

- **Goal Level Requirement:** Generate revenue through referral links, advertisements, and partnerships with transportation providers.
- **Domain Level Requirement:** Help customers to find cheap travel tickets
  EasyTrip must aggregate and display transportation options with real-time pricing and availability for users.
- **Product Level Requirement:** The system shall allow users to compare transportation options based on cost, travel time, and environmental impact.
  - Membership information storage
  - Visualization of prices
  - Airline info, aggretate data and provide an interactive comparison
- **Design Level Requirement:** The user interface shall include a dynamic filter and sorting feature for transportation options, supporting attributes such as price, duration, layovers, and user preferences.
  - Heatmap to enhanced interactive comparision of prices based on geography. For example by integrating Google Maps API together with flight information from Airlines' APIs.
  - Fast and intuitive user interface
  - Accesible for all user groups. For example, achieved by comprehensive usability evaluations
