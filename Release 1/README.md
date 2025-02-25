# Instructions for reading the RELEASE 1

Jonathan Ahlström, Ossian Gewert, Jacob Jönsson, Simon Persson, André Roxhage, Felix Sundholm

## Navigating the files

The System Requirements and Project Experiences documents are PDFs named SystemRequirements.pdf and ProjectExperiences.pdf.
These are based on are 2 main latex files, which depends on their subpages found the folder /subpages.

## Deliverables

- Elicitation
  - Stakeholder analysis
  - Interview of two potential users
  - Mail conversation with a airline-stakeholder from easyJet
- Functional Requirements
- Data Requirements
  - Data dictionary
  - Virtual window
  - E/R diagram
- Quality Requirements
- Context Diagram

---

## Feedback Supervision 31 Jan

no code needed!

send email to airlines people, for elicitations.
Need two types of stakeholders for higher grade (users, and ???)

continuously write the reflections

### Project Mission - feedback

we frame it like we already know it will be a good idea.

Context diagram\_
family and friends. include in booking process features.
add Google Maps integration to the diagram.
no need for multiple airlines, since airlines is in plural.

### Release 1 - feedback

DONE! Elicitation: email details, how did the contact work, questions asked etc.

DONE! ElicitationReflection: Add subsections

DONE! Add Goal level requirements, "smell of money", before or after the introduction.

#### Function requirements:

DONE! maybe task descriptions for heatmap feature (our some main feature)
DONE! subsections for grouping different features.

DONE! Reconsider ID system: robust for document restructoring
DONE! F2,F4 product or domain level. Skip naming -P -D and instead write about the level in the requirement. No need to argue it just tell which level it is

F5, F9 are very similar. Elaborate so the difference is clear. If we make subsections it will be clearer separation
Map or heatmap, make sure to use consistent terminology

F21, F22 maybe they are product or feature level reqiurements, perhaps they are req on multiple levels

#### Data

Add DR1 to ER diagram
flight search - schedule (1-1)? rethink the cardinality

Virtual window missing ID as well. Needs more descruptions regarding the context of the windows, add text before the virtual window.

#### Quality

Remove the level from the name.
F17, more types of quality requirements. Security.
André can add usability requirement SUS scale, score above 50 and WCAG 2.1 standard.

#### Other things

DONE! Add text description before context diagram, add an id to it. Maybe move it to near intro if we decide to use it as a explanation to the system.

Release plan. Add text before table.

#### Project experience

Make sure to include

- a section with reflections about the whole project
  - project decisions, why did we chose the methods etc.
  - what took more or less time etc
- cover every single method use and a reflection for that


### Release 2 - feedback

#### Validation report:
Think outside the checklist
check the grading grid for what we should demonstrate during validation
add additional sections outside the checklist
if prioritization is not part of the checklist add your own prioritaztion

#### SRS:
Tag quality requirements. E.g. add "quality" in brackets.
Maybe write in text that indented requirements are quality requirements

Data model should have ID in CamelCase as it is a requirement

Motivate why requirements in E/R diagram are design level

Sort out negative numbers, maybe discuss with Björn

Missing details on prioritization.
Separate from release plan, rank order of features

Dependencies between reqs/features should be included in SRS

More than one prioritization technique, at least two prioritization techniques
100$? Three prio levels - must have, ...

Usually Prioritization section before Release Plan section

Show how have we taken several stakeholders into account during prioritization

We could put reqT code snippets into the SRS

Remove validation checklist from R3 SRS, and only send it in as a separate document

#### Project Experiences:
Move constraints to SRS

- Make sure to have reflections on all parts
- What worked? What did not work?
- What could have been done differently
- What approaches/techniques complemented each other
- Cover all techniques used


#### Internal validation
- Use our own checklist
- Use the grading grid
