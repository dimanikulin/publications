# Headline
GenAI Assistant for Solution Architects

# Table of contents

- [Tags](./!Template.md#tags)
- [Definitions, Acronyms, Abbreviations](./!Template.md#definitions-acronyms-abbreviations)
- [Overview](./!Template.md#overview)
- [Introduction](./!Template.md#introduction)
- [References](./!Template.md#references)

# Tags

TBD

# Definitions, Acronyms, Abbreviations

| # | Abbreviation or Acronym | Definition     |
| - | ------------------------|:--------------:|
| 1 |

# Overview

TBD

or ---

# Introduction
 I was a software developer in embedded area. So I worked as a *lead software developer* in big medical product and meanwhile I took part in mentorship in GL Architecture mentorship. During mentorship I got a business case to implement - service marketplace platform. You might know in Ukraine we have **Kabanchic** - it helps to connect people like plumbers, electric engineer and with other people like their customer so they connect each other to get provide/get the services with/in.
In Europe we have **UrbanSitter**.

# Service marketplace platform

 So *customer* wanted implementing this marketplace platform. They wanted from us to have **Visa cards** to integrate(payment using the cards), web money and bitcoins. Also they wanted to have **Google Analytics** and put some advertisement in their platform.
 
 <img src="./Images/AIForSWArchitects1.jpg" alt="TBD" />

# ChatGPT Solutions Architect Assistant

Fortunatly during implementation I got access to video to recording from **DOU Days 2024**.
DOU is a big IT society in Ukraine and they have some conference in May 2024 year. There was an architect from other company and he shown us architecture assistant based on generative AI. It helped him a lot to increase speed and decrease time of spent by to create architecture vision in times. What he said exactly he had to spend days to implement architecture and now using this assistant he had to spend just hours.

<img src="./Images/AIForSWArchitects2.jpg" alt="TBD" />

He provided example of simple solution to implement and he said before it it was 4 days and now using this assistant *It was able to make my architecture vision in four hours*. It was really challening for me. So I decided to check it to create Solution Architecture for my business case. It's based on **ChatGPT** so you prompt solution assistant, then you have response from it and so communication is done with this approach.
It accepts the input information in three forms we have usually for pre-sales so it's **RFP,** **RFI** and usual text (just plain text).
And what is good you can use some output from stage input for another stage. As the output it provides diagrams, tables and text description for everything. Also it migth provide the output in **Markdown** or **PlantUML** format.

## Preparation to use assistant

<img src="./Images/AIForSWArchitects3.png" alt="TBD" />

But before you can use it you need to do some preparation and one is anonimization. So you need to remove any **PI information** because something can go wrong and your information or commercial details maybe will be known by other people.
So you need to remove any **PI information** and prepare input in form of **RFI** or another text for this assistante.

# Service marketplace platform - Success story
So it was success story and also there was not so success story but I will tell it a little bit a bit later.
I had five rounds of working with this assistant because when you have only one round information output can go in one wrong way and so on and had it in several rounds. Then I merged results and it was much more valuable and exact for me. By round I mean when you start working with assistant saying *hi let's start creation architecture vision* and until it tells *everything done so any clarification is welcome*. So from for *first* question to *the last* question it's one round for me.

## Service marketplace platform, Inputs

<img src="./Images/AIForSWArchitects4.png" alt="TBD" />

I used СhatGPT to help me create RFI. It had overview, some background information about marketplace platform, when I'm going to implement it. Also there was project scope and requirements - key features, functionality and so on technical requirements. And as usual there were terms and condition. I was able just to attach file so I had its input as a file and not in plain text copied from an editor. So it parsed it.


## Service marketplace platform, Outputs
This this assistant output is based on standard classic approach like descibed by Microsoft or Software Institute.
So it started from business goal and constrains. then it moved to discussion use cases and main features with quality attribute scenarios.
And then it made me happy when I got design with several views with operation plan, solution road map and team composition.
<img src="./Images/AIForSWArchitects5.png" alt="TBD" />

What was good with this assistant at communication -  I felt like I'm speaking with a human architect who quite is experienced in this area because I was not experienced. Still I was able to challenge it. For example I asked this assistant to prove that this point is acceptable for me. Why it choose for example Azure as a cloud platform and it explained it. So it was a kind of real communication with a kind of real architect.

As I said there were several diagrams and now you can see functional decomposition.
it's layered architecture with front end layer, backend services and databases layer.

<img src="./Images/AIForSWArchitects6.png" alt="TBD" />

 Also there is integration layer with third parties like **payment gateways**, **Ad API** and **Google Analytics**.

So it made three layer functional decomposition with description for each layer.

And here is another functional decomposition with less details from another round.
<img src="./Images/AIForSWArchitects7.png" alt="TBD" />

 I just meontioned it here so you see it outputs differently in different rounds of working with that.
 
 And as final step of working with resistant you will have architecture vision document. 
 There will fundamental text description for each area - for team composition, for diagrams etc.

# Final Deck

Based on output I had from five rounds working with architecture assistant I created final deck.

## Context View
It generated **Context View** so we see users like - *suppliers*, *customers* and *admins*
Also we have *core components* with some details inside of platform - *web services*, *admin panel*, *notification service*
And we have integration part - so *payment gateways*, *analytics* and *advertisement API*.
<img src="./Images/AIForSWArchitects8.png" alt="TBD" />

## Decomposition View
The next view is the Decomposition one - quite detailed view. And I was really happy to have it.
We have again *backend services* layer, we have *front end* layer, we have *integration* with *external* system and *database* layer. 

For *back end* we have several services order management notific
Dmytro Nikulin: ification analytic user services working with padman so integration and product services and it communicates it work with user data product data and ordering data. in front end we have two interfaces for admin and for another people.  So for supplier and for customer and again we have communication integration with payments to payments like it was required from customer.
Dmytro Nikulin: And again Google API deployment view no no it's not about using architecture in our solution.

<img src="./Images/AIForSWArchitects9.png" alt="TBD" />


## Deployment View

## Work breakdown structure


## Core Team Composition

## Roadmap

# Conclusion
it doesn't fit with our global logic styles but it's a kind of automatic applying of styles for any diagram
## Timing

## What was good and what was not good

# Data Platform - Not success case

## Data Platform
TBD

# References

| # | Name                 | Source                | Release date           |  Author                 | Description   |
| - | ---------------------|---------------------- |----------------------- | ----------------------- |:-------------:|
