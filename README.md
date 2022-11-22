# Hey-Blue

This repository will contain the artefacts produced by the "It Depends" team for the Autumn 2022 session of O'Reilly Architecture Katas. The project this season is to create a proposed architecture for "Hey Blue!", a system to facilitate moments of meaningful connection between police officers and members of their community.

## About ItDepends
We are minds of software engineers and architects who have come together across three continents to work collaberatively and produce this proposed architecture.

- Shari Lines
- Miguel Gasca
- Kavya Shivakumar
- Prashant Jasani
- Susmita Kunishetty
- Uma Kapoor

## Goal
To design a feasible mobile/web solution which helps community by enabling citizens and police officers to connect and earn points which can be redeemed in charities or retail store. 

## [Requirements](Requirements)

The directory linked to contains all artefacts related to functional and non-functional requiremens, as well as user story diagrams derived from the 4 processes documented in the original requirements.

- [Requirements and Goals](Requirements/Requirements_And_Goals.md)
- [Non Functional Requirements](Requirements/Non_Functional_Requirements.md)
- [User Stories](Requirements/UserStories)

### [Architectural Vision](Vision%20and%20Context)

- [Vision](Vision%20and%20Context/context%20and%20vision.jpg) is an abstract diagram illustrating the overall vision of Hey Blue!.
- [Evolutionary Considerations](Vision%20and%20Context/Evolutionary%20Considerations.md) takes note of potential directions of evoluion of Hey Blue! regarding Usability and scope of positive interactions.
- [Volummetric Analysis](Vision%20and%20Context/Volumetric.md) has some napkin calculations feeding into throughput and scale requirements of Hey Blue!

### [Proposed Solution](Solution/README.md)

### [Decisions](docs/decisions/README.md)

This contains all recorded decisions made during our process. Starting with the [first one](./docs/decisions/0000-use-markdown-any-decision-records.md) to adopt MADR format and guidelines.

- [Design principles](docs/decisions/principles/)
   - [0001-Technology-Choices](docs/decisions/principles/0001-technology-choices.md)
   - [0002-Opensource-HeyBlue](docs/decisions/principles/0002-opensource-heyblue.md)
- [Architectural Characteristics](docs/decisions/characteristics/)
   - [0003-Security](docs/decisions/characteristics/0003-security.md)
   - [0004-Affordability](docs/decisions/characteristics/0004-affordability.md)
   - [0005-Usability](docs/decisions/characteristics/0005-usability.md)
   - [0006-Elasticity](docs/decisions/characteristics/0006-elasticity.md)
   - [0007-Evolvability](docs/decisions/characteristics/0007-evolvability.md)
   - [0008-Observability](docs/decisions/characteristics/0008-observability.md)
   - [0009-Availability](docs/decisions/characteristics/0009-availability.md)
- [Structural Decisions](docs/decisions/structure/) including Architectural Style ADR

## Architectural Charecteristics

We have identified core architectural characteristics into this worksheet based on [Architecture Characteristics Worksheet](https://www.developertoarchitect.com/downloads/architecture-characteristics-worksheet.pdf) 

![ArchitecturalCharacteristics](docs/decisions/characteristics/ArchitecturalCharecteristics.PNG)

## Architectural Styles

We built a worksheet based off of the one found at Developer to Architect Styles Worksheet. We considered all styles listed there except for Layered (it was least well suited from the list and has poor domain to architecture isomorphism). We added to the list Serverless and also a hybrid Event-Based-Serverless. The results of our analysis with a table constrained to our core characteristics is as follows:  
(Detailed explaination in [0011 Architectural Styles](docs/decisions/structure/0011-architectural-style.md))

![StyleToCharacteristicAnalysis](docs/decisions/structure/ArchitecturalStyleCharacteristicComparisons.png)
