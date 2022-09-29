---
parent: Specify at RBGE (when ready)
title: Geography and Localities
---

# Geography and Localities

The geographical information in Specify is managed using a combination of Geography, Locality and Collecting Event information in the Collection Object.

## Geography Tree

The Geography is visualised using the Geography Tree. Each geography record needs to have a parent, similar to the Taxon Tree. Below country level, the terminology for the regions/provinces/states/counties varies within different countries and so a more general subcountry, subsubcountry, etc, terminology is currently being used.

![image](https://user-images.githubusercontent.com/6713716/193112633-f747fba6-6d31-41e9-819a-a8e16a3bdbb0.png)

The Geography Tree has been built based on GADM, the Database of Global Administrative Areas.

Part of the Geography Tree has been customised to include the Vice Counties within the British Isles.

![image](https://user-images.githubusercontent.com/6713716/193114870-1b2a82dc-08d4-4413-84a8-9e572fee0849.png)

## Localities

The Locality table is separate to the Geography Tree but is related to it. Each item in the Geography Tree has a corresponding Locality record.

![image](https://user-images.githubusercontent.com/6713716/193120405-2c622175-e29b-4e44-9e2c-eda650f79aff.png)

There are also a number of additional Locality records, each of which is connected to the Geography Tree. These have been created for the RBGE Garden locations.

![image](https://user-images.githubusercontent.com/6713716/193120259-16e38673-e6f8-4fc3-a012-6c92fa986698.png)

The Locality table is currently fixed. Any localties not included in here should be entered using the Verbatium Locality field in the Collection Object.
