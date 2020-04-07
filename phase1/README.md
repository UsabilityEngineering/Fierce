# Team Fierce, Phase 1: User Inquiry and Inspection

## Methods

### Questionairre
--------------------
Why: Accessibility for remote data collection during COVID-19 stay at home orders. A questionairre also allowed for simple mock data collection.
Sample Size: 20

A pivot table was created to analyze the response data with Timestamp for rows and the duration of ticket acquisition as columns. Values are the number of events attended and can be summed, averaged, etc. Filterable options are event attendance, how the event was found, and cancellation notification.

-------------------------------------------------------------------------------------------

## Findings

### Questionairre
-------------------
- Users that received cancellation of their event, via methods other than phone, attended 50% more events than those who received no notification or were notified via phone.

### Ticket Acquisition Distribution 
--------------------------------------------------------------------------------------------
 - 0-1min: 4 tickets
 - 1-2min: 2 tickets
 - 2-3min: 2 tickets
 - 3-5min: 15 tickets
 - 5+min: 1 tickets

- Users that did not attend any events did not specify search time 5/11 times. Two responded with less than one minute and four responded about five minutes.

### Event and User Distribution by Persona
--------------------------------------------------------------------------------------------
 - The Curious: 6 users, 0 events, average: 0 events
 - The Refined: 1 user, 1 event, average: 1 events
 - The Free Spirit: 2 users, 6 events, average: 3 events
 - The Veteran: 7 users, 17 events, average: 2.43 events
 
 ###  Event and User Distribution by Sub-Persona
 --------------------------------------------------------------------------------------------
  - The Ghosted: 5 users, 10 events, average: 2 events
  - The Landline: 1 user, 2 events, average: 2 events
  - The Forgiving: 4 users, 12 events, average: 3 events
  - The Sheriff: 3 users, 9 events, average: 3 events
  - The Detective: 7 users, 15 events, average: 2.14 events

--------------------------------------------------------------------------------------------

## Conclusions

Discoveries derived from the method(s). For example, explain a requirement (e.g. “Task X needs to be accomplished with fewer steps. . . ”) based on a finding (e.g. “. . . because in our contextual inquiry, we found it was what the users did most often and complained about extraneous work needed to complete it”)

## Caveats

Considerations and/or limitations to the method(s) you chose and the findings/conclusions drawn from them. In other words, give warnings if there are limitations to your research such as not being able to find enough users of a particular demographic, the methods not being able to expose certain information, assumptions you made, etc.

## Personas

### The Curious
--------------------
- Those who have not attended any events, but still responded. These users are considered to be potential leads and their return rate will be heavily influenced by their first experience.

- For the purposes of defining this persona, null answers for event attendace are interpreted as no. It is inferred that these users have an interest in events from the fact that they responded even with no event history.

------------------------------------------------------------------------------------------------
### The Refined
--------------------
- Those who have attended few events and spend over five minutes acquiring their ticket. These users are considered to be attracted to prestigious or niche events and their return rate will be heavily influenced by the perceived value for the cost.

- For the purposes of defining this persona it is inferred that these users spent more time acquiring tickets through a similar process, where others were able to spend less time. 

-----------------------------------------------------------------------------------------------
### The Free Spirit
--------------------
- Those who attend more than one event and spend less than two minutes acquiring their ticket. These users are considered to be attracted to a wide range of events and their return rate will be heavily influenced by the ease of attending multiple events. This includes everything from the ticket acquisition process to the rules of the event.

- For the purposes of defining this persona it is inferred that these users are experience-focused and are generally optimistic. Given their rapid acquisition of tickets and multiple events attended, it is also inferred that these users would more readily refund their purchase if there are significant difficulties involved in event attendance.

---------------------------------------------------------------------------------------------
### The Veteran
--------------------
- Those who have attended two or more events and spend 3-5 minutes acquiring their ticket. These users are considered to be attracted to the event and their return rate will be heavily influenced by the selection offered.

- For the purposes of defining this persona it is inferred that these users have experience in attending events and generally know what they want from an event. Given their routine ticket acquisition time and events attended, these users are considered to be more willing to engage with a more structured event environment. 

--------------------------Sub-Personas------------------------------------------------------
--------------------------------------------------------------------------------------------
These tags may be applied to any persona, and define how users respond to variables.

--------------------------------------------------------------------------------------------
### The Ghosted
--------------------
- Those who attended events, but were not notified of some cancellations. These users attend an average of 2 events, and are considered to have a negative position on the service.

---------------------------------------------------------------------------------------------
### The Landline
--------------------
- Those who attended events and were notified of its cancellation via phone. These users are considered less app-focused and more willing to attend events that do not require them. Ultimately, a cancellation call will provide minimal benefit since these users attend an average of 2 events anyway.

---------------------------------------------------------------------------------------------
### The Forgiving
--------------------
- Those who have attended events and were notified of its cancellation via a method other than phone. These users are considered to be less interested in customer service except regarding cancellations or other negative circumstances. A cancellation notification could mean a significant increase on return, as these users attended an average of 3 events.

---------------------------------------------------------------------------------------------
### The Sheriff
--------------------
- Those who find events through a trusted network of contacts like Friends/Family, Facebook Pages, Community Organizations (mesa) , or Radio. These users are inferred to respond most to word-of-mouth, actions, and local presence.

---------------------------------------------------------------------------------------------
### The Detective
--------------------
- Those who specifically search for events online, with or without other sources, using experience to guide their search. These users are inferred to respond most to informative online advertising when making a decision. 
- However, other sources of information will influence where these users begin their online search.

---------------------------------------------------------------------------------------------

## Scenarios

#### Scenario 1: User navigates events listings
The user navigates to the application, where their current location is requested. Based on the answer given to the software, the main page will display a scrollable list of events either based on the user’s location (followed by date), or events by date. The user can then select further filters such as race distance, average weight lifted, driving distance, and more. Once filters are selected (if desired), the user can scroll through the list where the events featured will have backgrounds of images related, a short city/state location, basic stats (distance/weights), the home venue company (Spartan, Tough Mudder, etc) and the start date of the event. Having this information without further navigating, the user, being a regular attendee, can quickly scroll through the list for events pertaining to their interest, quickly checking the ones that apply until there are either no events left to list, or they get tired of scrolling. When an event is checked for the first time, a “check-out” style cart appears and remains visible so long as one (or more) event is chosen. The user can then continue navigating through the different menus, search terms and filters to ensure they didn’t miss any events they’re interested in.
The Curious user’s reaction would be content with the fact they can search, filter, and scroll through all possible events known to our application and browse for further detail if they were interested, and could go as far as to even set up an event planner with even partial statistics. This kind of user may be slightly taken back at the flexibility of the software, as the website serves only a small amount of applicability: Event surfing, planning and registration, rather than detailed guides or experiences of events, as the website is a planning and registration assistant rather than a review or adventure guide.
The Refined user, free spirit and veteran users would be impressed by the ability to mass schedule events of their interest, and to map everything out on a planner where they could quickly link over to the registration process for each event. These personas would greatly benefit from the efficient and user-friendly software.
#### Scenario 2: Using the planner with selected events
Once they navigate to the cart, they’re brought to a planner where they can quickly organize the events they’ve selected. To do so, the user would either choose to arrange the events by dragging and dropping them from “the pool” (where events are not considered in the calculations), or using a sorting algorithm. The sorting algorithm would arrange dates by date, offering different arrangements if events conflict or offering to remove them. The user can then continue to drag/drop events from the planner or the pool, changing the calculations and viewing schedules. Once the user is satisfied with their organization, they can continue the registration process. If the user tries to navigate away from the page, they’ll be given a prompt to register an account if they want to save their progress, as once the session expires their planner will be lost.
This scenario, in a way, satisfies most user groups as it provides a very convenient and user-friendly planner to organize all events of interest so that they can choose the schedule that best suites them. Careful attention would have to be applied to being error tolerant and learnable, so that users can quickly and effectively plan and register.
#### Scenario 3: User wants to register their selection from the planner and set up their events
Once the user navigates to the registration page, any events that are contracted through the software can be registered at once through the checkout page with all coupons pre-applied. Any events not contracted will provide a link to a direct registration page to the event host’s checkout page. The user will (optionally) register an account, complete the registration process, pay all applicable fees, and then their planner will register all events. Once the events are registered, they’ll be taken to their profile page (if registered) or sent back to the planner with a prompt to create an account to save their planner.
Due to the contract limitations, many users would find this not so efficient as they would potentially be following popup links to different event registration pages. However, taking out the middle work by organizing everything in one place would be appreciated by users who were either curious, investigative or regular athletes.


## Supplementary Materials

Include link(s) or cop(ies) to your instrument(s) itself (questionnaire for a survey, protocol for an interview or contextual inquiry, etc)
