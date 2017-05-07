<h2>TwikiHandles Classification Dataset</h2>

This repository includes data exracted from Wikidata via SPARQL query on April 15, 2017. All available Twitter handles are collected along with their wikidata entry id and instanceof-information of those entries.

TwikiHandles dataset is created for the purpose of classifying entity type of Twitter handles in the context of named entity recognition task. Twitter handles are grouped into following categories: person, location, organization, product and character. This is done by detecting which wikidata entries correspond to these entity types and then checking if wikidata entry that contains Twitter handle information is instance of such wikidata entry.
