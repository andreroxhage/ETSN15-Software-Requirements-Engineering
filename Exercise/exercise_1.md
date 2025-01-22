# ETSN15-Software-Requirements-Engineering

## Exercise 1

1. Give examples of various project types (kap 1.2) from your own geographical region. [Lau övn 1.1]

   - **Examples:**
     - [Add more examples as needed]
     - Product dev: iPhone, End User: consumer, Customer order: Market, Supplier: Apple R&D
     - Product dev: Hövding in Malmö, End User: consumer, Customer order: suppliers, web shops
     - Tender: Svenska staten, for example solution for a digital ID
     - In-house dev: Test tool, End User: another department within the same organization

2. Which project model should the shipyard have used? Which one did they actually use? [Lau övn 1.7]

   - **Suggested Project Model:** 2-step: Domain- & Design- level
   - **Actual Project Model Used:** Fast approach: Domain-level

3. For your own project,
   a. Identify the project type (in-house, COTS, etc.)

   - **Project Type:** Product dev
     b. Suggest a project model to use [if not done as specified by the course project assignment].
   - **Suggested Project Model:** Two-step approach: Domain-level + design-level

4. In the hotel system example, is the receptionist part of the product? Is he/she part of the inner domain?
   Answer the same question for the waiter. Suggest different system limits so that we get another answer.
   [Lau övn 3.1] see Fig. 3.2 page 77

   - **Receptionist:**
     - Part of the product: No
     - Part of the inner domain: Yes
   - **Waiter:**
     - Part of the product: No
     - Part of the inner domain: No
   - **Different System Limits:** If adding a queing system then this might be a part of the waiter will be part of the inner domain as well.

5. For your own project,
   a. Create an initial version of a context diagram and consider the boundaries of your (black box) product.
   Which users and systems does it interact with, directly and indirectly? Are there any non-obvious actors,
   e.g. system admin, usage statistics? Who are the stakeholders in the business domain?

   - **Context Diagram:**
   - **Users and Systems:**
     - **Primary:** Travelers aging from 18-65 y/o.
     - **Secondary:** Family members & friends to to whom booked the trip.
     - **Tertiary:** Travel angencies.
   - **Non-obvious Actors:** Support department (Customer Experience)
   - **Stakeholders:** Competitors like Momondo and Flight Scanner, Travel agencies, Ad creators, End users (travelers), product management, development team, airline

   - **Requirements:** b. Outline a possible requirement for each of the four requirements levels (kap 1.6, goal, domain, etc.)
     - **Goal Level Requirement:** Generate revenue through referral links, advertisements, and partnerships with transportation providers.
   - **Domain Level Requirement:** Help customers to find cheap travel tickets
   EasyTrip must aggregate and display transportation options with real-time pricing and availability for users.
   - **Product Level Requirement:** The system shall allow users to compare transportation options based on cost, travel time, and environmental impact.
     -  Membership information storage
     -  Visualization of prices
     -  Airline info, aggretate data and provide an interactive comparison
   - **Design Level Requirement:** The user interface shall include a dynamic filter and sorting feature for transportation options, supporting attributes such as price, duration, layovers, and user preferences.
     - Heatmap to enhanced interactive comparision of prices based on geography. For example by integrating Google Maps API together with flight information from Airlines' APIs.
     - Fast and intuitive user interface
     - Accesible for all user groups. For example, achieved by comprehensive usability evaluations.
6. Study the following parts of existing reqts specifications in Chapters 11 and onwards [Lau övn 1.9]:
   Midland Hospital (Ch 12):
   - Section 2.3 Employee data, requirements 5 to 18
   - Requirement 144, 475, 666, 669
     Danish Shipyard (Ch 11):
   - Detailed planning (entire section 5.2.1.2.2)
   - Objectives (entire section 4.1)
     Bruel & Kjaer (Ch 14):
   - Requirement 35
   - Requirement 36
     For each of these specification pieces, answer the following questions (se kap1.3):
     a) Is it a functional requirement?
     b) A non-functional one?
     c) Something to help the reader?
     d) Something about the domain or the product?
     e) A system goal?
     f) An example?
     g) Is it verifiable?
     Note: The same piece may be several of these things at the same time
     h) Among the Midland Hospital requirements mentioned above there is a “killer requirement”, that is a
     requirement that looks innocent but could cause disaster for the unwary supplier. Which requirement is it?
   * **Answers:**
     - Midland Hospital:
       - Section 2.3 Employee data, requirements 5 to 18: [Answer questions a-h]
       - Requirement 144: [Answer questions a-h]
       - Requirement 475: [Answer questions a-h]
       - Requirement 666: [Answer questions a-h]
       - Requirement 669: [Answer questions a-h]
     - Danish Shipyard:
       - Detailed planning (section 5.2.1.2.2): [Answer questions a-h]
       - Objectives (section 4.1): [Answer questions a-h]
     - Bruel & Kjaer:
       - Requirement 35: [Answer questions a-h]
       - Requirement 36: [Answer questions a-h]
