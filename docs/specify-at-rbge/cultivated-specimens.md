---
parent: Specify at RBGE
title: Cultivated Specimens
---

# Managing cultivated specimen data

## Overview of cultivated specimens

Essentially cultivated specimens comprise two or more collecting events which are related. The primary collecting event in terms of citations and location of the specimen is the most recent event from the plant growing in cultivation. Previous collecting events may or may not be recorded.

In Specify, the cultivated specimen is created as a Collection Object with the collecting event from the plant growing in cultivation recorded in this record. Depending on the specimen and the data available, the information relating to previous collecting events will be managed as follows.

**1. Cultivated specimen created from RBGE living collection with data in Iris**

   The Accession Number and Qualifier is recorded in the cultivated specimen record in Specify to provide the link to the data in Iris. The wild collection data in the record in Iris would not be expected to be updated. The data could be brought together for labels via the html exports.

**2. Cultivated specimen (not from RBGE) with previous collecting event information on the label**

   A separate Collection Object record for this will be created in Specify and the catalogue number should be recorded in the cultivated record. We can use an integer for Their Number if there is a non-RBGE accession number listed (eg http://data.rbge.org.uk/herb/E00632264)

**3. Cultivated specimen (not from RBGE) with limited or no previous collecting event information on label**

   Any information that is available should be entered into the cultivated specimen record in Specify, in the relevant field, eg Description, Habitat, Collecting Event?, Collection Misc.

**4. Cultivated specimen created from RBGE living collection with no data in Iris.**

   If the Accession Number and Qualifier are available these should be added and no additional Collection Object record will be required since these data will be going into Iris in the coming year. If there is no Accession Number and Qualifier but still some wild collecting event data present, then a separate Collection Object record for this should be created in Specify and the catalogue number should be recorded in the cultivated record. 

## Cultivated specimen scenarios

**Scenario 1: Cultivated specimen created from RBGE living collection with data in Iris**

Example: http://data.rbge.org.uk/herb/E00247738

_A living plant collected in the field (as rooted plant, seed, cutting, etc) and brought back to RBGE._

When it was collected it would be assigned a collection number in the field, and it would then receive an Accession Number when it arrived at RBGE. When a plant is grown on from that material it would then be assigned a qualifier.

All information relating to these events would be held in Iris at RBGE.
Create a cultivated Collection Object record and enter the RBGE Accession number and Qualifier

The use of a weblink button will enable the user to see this record on the RBGE Catalogue.

Workflow:

  1.	Plant material arrives at RBGE and is accessioned, assigned an accession number with the collecting event recorded.
  2.	Individuals grown and assigned qualifiers which are children of the accession.
  3.	A specimen is made from one of the individuals, and comes to the Herbarium.
  4.	At this point, the specimen would be accessioned (registered).
  5.	A search would be made on the Collector and Collector number and date to see if there was an existing Collection Object.
  6.	A new Collection Object would be created with the garden collecting event recorded.
  7.	The RBGE Accession number and Qualifier would be entered into this Cultivated record.
  8.	A label would then be created, which would include both sets of Collecting Event information.



**Scenario 2: Cultivated specimen (not from RBGE) with previous collecting event information on the label**

eg, Bogor Botanic Garden, private garden (native or introduced)
_Wild collected data on the label_

Create a wild collected Collection Object record, if not already in the database. Then create a cultivated Collection Object record and enter the catalogue number of the Wild Collection Object

Workflow:

  1.	Check the cultivated specimen for wild collected information.
  2.	If there is information about the wild collection event, including a collector and number, then run a quick query to check that there is not a specimen from the wild collection in the database already.
  3.	If not, then create a wild collected Collection Object to hold this information – there will be no Preparation attached to this Collection Object record since we don’t have an actual specimen.
  4.	Now create the cultivated Collection Object record.
  5.	Enter the Specify Collection Object catalogue number into the Cultivated from field.




