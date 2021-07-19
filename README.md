# Wikidata-TypeRec

This is a dataset for the training of a type classifier on Wikidata entity types.
It is derived from [Wikidata-Disamb](https://github.com/ContextScout/ned-graphs/tree/master/dataset) by [Cetoli et el. (2019)](https://arxiv.org/pdf/1810.09164.pdf).

The train set has 100,000 samples.
The test and the dev set have 10,000 samples each.
Each sample has four values:

- A natural language sentence s
- A mention m (referring to an entity e)
- The entity e (to which the mention m refers)
- The entity type t of the entity e

## Dataset Parts

There are three versions for each part of the dataset:

- <tt>small</tt>: small part of the dataset for debugging
- <tt>medium</tt>: larger part of the dateset for tests and debugging
- <tt>full</tt>: full dataset

## Entity Types

The types are a predefined set derived from [Wikidata Concept Monitor taxonomy](https://wikitech.wikimedia.org/wiki/Wikidata_Concepts_Monitor#WDCM_Taxonomy):

|Wikidata item|Type|
|---|---|
|http://www.wikidata.org/entity/Q215627|person|
|http://www.wikidata.org/entity/Q163875|cardinal|
|http://www.wikidata.org/entity/Q838948|work of art|
|http://www.wikidata.org/entity/Q13442814|article in scholarly journal|
|http://www.wikidata.org/entity/Q571|book|
|http://www.wikidata.org/entity/Q618123|geographical feature|
|http://www.wikidata.org/entity/Q43229|organization|
|http://www.wikidata.org/entity/Q811979|architectural structure|
|http://www.wikidata.org/entity/Q16521|taxon|
|http://www.wikidata.org/entity/Q1656682|event|
|http://www.wikidata.org/entity/Q83620|thoroughfare|
|other|other|
