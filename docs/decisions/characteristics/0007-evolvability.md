status: accepted
date: 2022-11-04
deciders: Kavya, Susmitha, Uma, Miguel, Shari

# Evolvability as a Core Architectural Characteristic

## Context and Problem Statement

There are some core use cases documented in the Requirements that the system must support. However there are also discussions of potential for the future. This includes things like:

- Concection to Municipalities to support redemption of points for things like fine reduction
- Connection to 3rd party social media systems, which may evolve to different systems in the future
- Connection to 3rd party systems for Business Catalogs, which may evolve over time
- Support to use the operational data to feed Machine Learning and AI model, who's insights may drive further evolution of the system

The above documents some need for external interoperability alongside extensibility (and there are more examples of interoperability with things like geolocation/mapping, identity/access etc). Both of these needs are also present internally with what is expected to be a heterogenous internal architecture.

## Decision Drivers

- {decision driver 1, e.g., a force, facing concern, …}
- {decision driver 2, e.g., a force, facing concern, …}
- … <!-- numbers of drivers can vary -->

## Considered Options

- {title of option 1}
- {title of option 2}
- {title of option 3}
- … <!-- numbers of options can vary -->

## Decision Outcome

Chosen option: "{title of option 1}", because
{justification. e.g., only option, which meets k.o. criterion decision driver | which resolves force {force} | … | comes out best (see below)}.

<!-- This is an optional element. Feel free to remove. -->

### Consequences

- Good, because {positive consequence, e.g., improvement of one or more desired qualities, …}
- Bad, because {negative consequence, e.g., compromising one or more desired qualities, …}
- … <!-- numbers of consequences can vary -->

<!-- This is an optional element. Feel free to remove. -->

## Validation

{describe how the implementation of/compliance with the ADR is validated. E.g., by a review or an ArchUnit test}

<!-- This is an optional element. Feel free to remove. -->

## Pros and Cons of the Options

### {title of option 1}

<!-- This is an optional element. Feel free to remove. -->

{example | description | pointer to more information | …}

- Good, because {argument a}
- Good, because {argument b}
<!-- use "neutral" if the given argument weights neither for good nor bad -->
- Neutral, because {argument c}
- Bad, because {argument d}
- … <!-- numbers of pros and cons can vary -->

### {title of other option}

{example | description | pointer to more information | …}

- Good, because {argument a}
- Good, because {argument b}
- Neutral, because {argument c}
- Bad, because {argument d}
- …

<!-- This is an optional element. Feel free to remove. -->

## More Information

{You might want to provide additional evidence/confidence for the decision outcome here and/or
document the team agreement on the decision and/or
define when this decision when and how the decision should be realized and if/when it should be re-visited and/or
how the decision is validated.
Links to other decisions and resources might here appear as well.}