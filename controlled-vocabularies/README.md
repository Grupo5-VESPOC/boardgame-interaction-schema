# Controlled Vocabularies

The controlled vocabularies used as values for the properties `interactionType` and
`socialDynamics` will be developed as a SKOS scheme and managed using VocBench.

These vocabularies will describe types of social interaction between players in board
games, such as cooperation, competition, negotiation, or conflict.

## Relationship with the metadata schema

The following diagram illustrates the relationship between the metadata schema and
the SKOS controlled vocabularies:

BoardGame
 ├── name
 ├── numberOfPlayers
 ├── playingTime
 ├── interactionType → SKOS Concept
 └── socialDynamics → SKOS Concept
