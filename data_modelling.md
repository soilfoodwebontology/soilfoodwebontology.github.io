---
title: The Soil Food Web Ontology
layout: default
filename: data_modelling.md
--- 

# Data modelling in the SFWO

*[<<](https://soilfoodwebontology.github.io/) Back to home page*

The SFWO can be used to provide detailed descriptions of the trophic behaviour of an organism, including its diet, feeding guild, trophic group, trophic interactions in which it is involved, etc. The following diagram shows the data modelling approach adopted by the SFWO to represent the fact that "*Carabus auronitens* is a predator":

![Diagram illustrating trophic data modelling in the Soil Food Web Ontology.](/images/sfwo-data_modelling.png)

Note the diagram shows different ways to represent the same information:
- *Carabus auronitens*, is_a, predator (feeding guild)
- *Carabus auronitens*, has_quality, predaceous (diet)
- *Carabus auronitens*, member_of, Coleoptera.predators (trophic group)
- *Carabus auronitens*, capable_of, predation (trophic process)
These representations are logically equivalent within the SFWO, and any representation can be logically deduced from any other by inference.

The SFWO can also be used to describe trophic interactions between a consumer and a resource. The following diagram shows the data modelling approach adopted by the SFWO to represent the fact that "*Carabus auronitens* feeds on Lumbricidae".

![Diagram illustrating trophic data modelling in the Soil Food Web Ontology.](/images/sfwo-data_modelling-interaction.png)