# Exercise 2 - Specification I and Elicitation (Lau:2, 8)

## 1. For your own project (or Ticket Machine if own project is not applicable, p. 543) [Lau Ex. 2.4]:

### b) Write a data dictionary (see 2.3) for an interesting part of the system.

- Which advantages and disadvantages do you see with data dictionaries?
Textuall information is easy to understand for everyone. The is a risk that the text gets to detailed.

Data dictionary
Class: Traveller
The traveller is a person who can create an account and obseerve chflights

**Examples:**

1. A traveler decides to search for a route and wants to recieve recommendations in the future based on his/her previous searches.
2. A traveler decides to save a route and subscribe on price drops via email.
3. A traveler can subscribe to a e-mail list to get general updates about the company.

**Attributes:**
- E-mail address: Text. 254 chars
- Name: text. 120 chars
- Password: 62 chars
- City: 35 chars
- Consents boolean[]
### c) Outline a virtual window (see 2.5) for an interesting part of the system.

- Which advantages and disadvantages do you see with virtual windows?
Overview of data which serves as a blue print for the developers. Easy to understand for stakeholders. Can be limiting for development if the deveopers see the viritual window as the finilize design.

# Traveller #374

## Personal Information

| Field     | Value                   |
|-----------|-------------------------|
| **Email** | exampleJohn@gmail.com   |
| **Name**  | John Doe                |
| **Utskick** | ● True  ○ False       |
| **City**  | New York                |

## Övervakningar (Monitoring)

| From | Price Max | To  |
|------|----------|-----|
| NY   | 3000 SEK | CPH |
| CPH  | 2500 SEK | NY  |
| ...  | ...      | ... |

---

## 2. Which elicitation techniques could be used to overcome each of the elicitation barriers? (see 8.1.1 and 8.2) [Lau Ex. 8.1]


### a) Consider which of the barriers may appear in your own project.
Elicitation Barriers: 
Stakeholders will often reject proposals due to a general resistance to change.
Often different stakeholders have conflicting views. 
In most cases, stakeholders cannot express what they need

Users don't know what they need. Its up to the developers and designers to find their core needs and goals, and from there create a solution. For example, due to being unaware of the technical possiblities.

How to overcome barriers:
Have a clear goal with the product.
Give quesitions about simular products.
Learn about the users goals, not their problems.
---

## 3. For your own project (or Ticket Machine if own project is not applicable) [Lau Ex. 8.4]:

### a) Make a preliminary stakeholder analysis (your own best guess).
Who are the stakeholders?
Travel agency
Users
Advertisement management(google)
Competitors
Airlines

What goals do they see in the system?
Travel agency - More ways to sell, more interaction with customers
Users - Easier way to plan trips and follow through with the idea of trips and possibly find cheaper options
Advertisement management(google) - More places for advertisement and more ways to collect big data (idk last one)
Competitors - //Simon e lite lost på denna
Airlines - More ways to sell means also more data to analyze and improve efficeny of flight planing and resource management

Why would they like to contribute?

What risks and costs do they see?

What kind of solutions and suppliers do they see?


### b) Consider what information (or work products, see 8.2) you need and from which stakeholder(s).


### c) Consider what elicitation barriers (see 8.1.1) each stakeholder might present in eliciting the information you need.


### d) Consider which elicitation techniques to use for each information need and stakeholder.

- Discuss how these techniques address the elicitation barriers.

---

## **To review at home**

- Which techniques could be used to elicit user tasks?
- To elicit a data model?
- To elicit feature requirements?
- To elicit quality requirements? [Lau Ex. 8.2]

---

## For your own project (or Ticket Machine if own project is not applicable) [Lau Ex. 2.4]:


### a) Specify a data model for the system.

### d) Which data requirements styles would you suggest using in the case project?
