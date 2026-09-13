# **Traveler by EntahLaNak**

**Team:** \[Member 1\], \[Member 2\], \[Member 3\], \[Member 4\]

**Problem Statement:** Travel Planner

**Video Presentation:** \[[[Unlisted Youtube
Link]{.underline}](https://youtu.be/ra5-HuKso2Y)\]

**Presentation Slides:** \[[Public Link]{.underline}\]

## **1. Project Overview**

**The Problem**

Planning a trip can be stressful because travellers need to manage many
things at the same time, such as destinations, activities, schedules,
accommodation, transportation and bu in dgets. The problem becomes more
difficult when travelling in a group because everyone may have different
interests, preferences and budgets.

Another problem is that travel plans can change during the trip. For
example, a flight can be delayed, an activity can be cancelled, the
weather can change or a traveller may be running late. Most travel
applications mainly help users organise bookings or create itineraries,
but they provide limited support when the original plan needs to change.

One example is TripIt, which helps travellers organise travel
information and bookings in one place. However, it mainly focuses on
organising existing travel details rather than combining group
preference management, shared budgeting, expense splitting and adaptive
re-planning into one planning process.

The main stakeholders are:

-   Solo travellers who want an easier way to plan their trips.

-   Groups of friends or family travelling together.

-   Trip organisers who need to coordinate schedules, preferences and
    > budgets.

-   Travellers who need help when unexpected changes happen during a
    > trip.

**Our Solution**

Traveler is an AI-powered travel planning assistant designed to make
trip planning easier for both solo and group travellers. It combines
itinerary planning, AI recommendations, group preferences, budgeting,
expense splitting and AI-powered re-planning in one platform. Instead of
manually rebuilding a trip when something changes, Traveler can suggest
a new plan based on the situation.

The main features are:

-   **AI Itinerary Generation** --- Generate a daily itinerary based on
    > destination, dates, interests and travel style.

-   **Group Preferences** --- Allow travellers to add their interests
    > and preferences when planning together.

-   **Group Matching and Voting** --- Help groups find activities that
    > suit more members and allow them to vote on decisions.

-   **Budget Management** --- Set a trip budget and track planned and
    > actual spending.

-   **Expense Splitting** --- Record shared expenses and divide costs
    > between travellers.

-   **Explore and Locations** --- Discover activities, attractions, food
    > and places related to the trip.

-   **AI Travel Assistant** --- Provide suggestions and help users with
    > their travel plans.

-   **AI Re-planning** --- Suggest changes to the itinerary when
    > unexpected situations happen.

-   **Trip Overview and Notifications** --- Keep important trip
    > information and changes in one place.

The main user journey is:

Create Trip → Set Preferences → Set Budget → Invite Group → Generate
Itinerary → Review → Travel → Re-plan When Things Change

## **2. Ideation & Process**

### **2.1 Ideas We Considered**

At the beginning, our team discussed a few different ways to make travel
planning easier. We looked at the problems travellers usually face and
came up with several possible solutions before deciding on our final
idea.

  -----------------------------------------------------------------------
  **Idea**                **Decision**            **Why it was dropped /
                                                  kept**
  ----------------------- ----------------------- -----------------------
  Simple Travel Itinerary Kept as a starting      We liked the idea of
  Planner                 point                   having one place where
                                                  users could organise
                                                  their daily activities
                                                  and travel schedule.

  AI Travel               Considered              We wanted to use AI to
  Recommendation App                              recommend destinations,
                                                  activities and places
                                                  based on what users
                                                  like. However, we felt
                                                  that recommendations
                                                  alone were not enough.

  Group Travel Planner    Considered              We found that planning
                                                  with friends or family
                                                  can be difficult
                                                  because everyone has
                                                  different preferences
                                                  and budgets. This gave
                                                  us the idea to include
                                                  group planning
                                                  features.

  All-in-One AI Travel    Chosen                  We combined the
  Planner                                         strongest parts of the
                                                  previous ideas into one
                                                  application. The final
                                                  concept includes
                                                  itinerary planning, AI
                                                  recommendations, group
                                                  preferences, budgeting,
                                                  expense splitting and
                                                  AI re-planning.
  -----------------------------------------------------------------------

### 

### 

###  **Iteration and Idea Evolution**

Our idea developed through several versions as we understood problem
better.

#### [Version 1 --- Single Itinerary Generator]{.underline}

The initial concept was a simple tool that takes a destination and
travel dates and generates an AI-powered itinerary. The main function at
this stage was:

generateTripItinerary

This solved the AI-generated itinerary part of the problem, but we
realised that it mainly focused on one person\'s itinerary. It did not
properly address the difficulties of planning with other people,
especially when group members have different preferences, schedules and
budgets.

#### [Version 2 --- Added Budgeting and Group Sync]{.underline}

We then expanded the concept by adding budgeting and group planning
features.The main components introduced were:

-   BudgetView

-   GroupView

This changed the product from a simple **\"itinerary generator\"** into
a **\"group trip coordinator\"**.

Instead of treating a trip as one person\'s plan, Traveler could now
consider multiple travellers, shared costs and different preferences.
This made the idea more useful for group travel.

#### [Version 3 --- Added Adaptive Re-planning]{.underline}

The final major change was adding adaptive re-planning.

We realised that travel plans can change during the trip. For example, a
flight can be delayed, an activity can be cancelled, the weather can
become unsuitable or a traveller can be running late. To address this,
we introduced:

-   generateReplanSuggestion

-   AIReplanModal

When a disruption happens, Traveler can provide an AI-generated
suggestion for adjusting the itinerary instead of requiring the user to
manually rebuild the whole plan.

This became one of the main features that makes Traveler different from
a normal itinerary planner.

### **Breadth of Exploration**

Apart from the main ideas above, our team also explored several other
travel-related concepts before deciding on the final direction.

1.  **Solo-only itinerary app** --- Rejected because it does not address
    > the group budget, preference and schedule coordination problems.

2.  **Flight/hotel price tracker** --- Rejected because it mainly
    > focuses on the booking and price-tracking part of travel rather
    > than the complete planning process.

3.  **Booking aggregator with itinerary autofill** --- Rejected because
    > it organises existing bookings but does not provide enough support
    > for upfront planning, budgeting, group coordination or adapting
    > plans when something changes.

Through this process, we decided to combine the strongest parts of the
ideas instead of focusing on only one part of travel planning. This led
to our final concept, **Traveler**.

### **2.2 Ideation Boards**

Our ideation boards show how our team explored the travel planning
problem and developed the final concept.

**IMPORTANT:** You can express this in any way you like, including but
not limited to:

1.  Mindmaps

2.  Problem trees

3.  Flowcharts

4.  User flows

5.  Crazy eights

6.  Affinity diagrams

7.  SCAMPER grids

8.  Fishbone diagrams

9.  5 Whys chains

10. Any other scribbles :)

You can embed images in markdown like so:

\![Mindmap\](mindmap.png)

### **2.3 Mentor Consultation**

  -----------------------------------------------------------------------
  **Date**          **Mentor**        **Feedback        **What Was
                                      Received**        Changed**
  ----------------- ----------------- ----------------- -----------------
                                                        

  -----------------------------------------------------------------------

Even if you disagreed with a piece of feedback, you can say so and
explain why. You will not be penalised for doing something against a
mentor's advice, it will still count as engaging with it.

## 

## 

## 

## **3. Design & Prototype**

**UI Prototype:** \[ [Public Link]{.underline} \]

Check that it opens in an incognito window. This can be a link to Figma,
Canva, Netlify, Vercel or any other board where you showcase your UI. It
can be clickable with hyperlinks or simply ordered screenshots.

We recommend you embed or link 4--8 key screens as images, with a
caption on each explaining the interaction

## **4. What Makes It Different**

List out novel features and explain briefly which each is original or
what the twist is.

You can have a comparison table to compare with existing solutions named
in section 1 but this is completely optional.

## **5. Technical Architecture & Feasibility**

**Tech stack**

Tell us your frontend, backend, database, APIs and services, as well as
how and where you will be hosting. For each, try to tell us why you
chose that technology, and what constraints you expect to face (For
example, you chose Supabase because it's free but you'll still need a
proxy)

**System architecture diagram** (Optional, if you feel it would help the
reviewers understand your architecture better)

**Build plan & scope**

Explicitly tell the reviewer what you plan to build during the building
phase. Narrow scope will read as realistic and feasible, not as a lack
of ambition.
