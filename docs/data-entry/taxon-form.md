---
parent: Data Entry
---

# Taxon Form

Creating a record in the Taxon Form essentially creates the name as a nomenclatural element and does not include any taxonomic status for the name. Creating relationships between names with synonymy where you are building a taxonomic structure is done in the Taxon Tree.

The taxon form can be opened from the Data Entry button on the main menu, from within the Collection Object form and from within the Taxon tree. The two most common routes will be from within the Collection Object form and from the Taxon tree so these are covered below.


## To create a new Taxon record from the Collection Object form.

Before creating a new Taxon record, ensure that the name does not already exist.

Start typing the name in the Taxon box to see the drop down list of options

<p align="right" width="100%">
    <img width="33%" src="[https://user-images.githubusercontent.com/8005676/180251406-cc13332e-e143-49b6-b510-15c74d872dbe.png]">
</p>

![img align="right"](https://user-images.githubusercontent.com/8005676/180251406-cc13332e-e143-49b6-b510-15c74d872dbe.png)

Use wildcards (%) to search names more easily

- ![image](https://user-images.githubusercontent.com/8005676/180251592-5eedf934-acd3-443c-8cea-977032d107af.png)

Also use wildcards (%) to check spelling variants or uncertainty

- ![image](https://user-images.githubusercontent.com/8005676/180251739-f63c7172-d0a1-4d3d-8341-a64622978d0e.png)

If it does not come up, then there is an option to do an additional search by clicking on the magnifying glass to the right of the Taxon field.

![image](https://user-images.githubusercontent.com/8005676/180252413-279bcff3-d42e-459b-bdd3-b9d5ca4e2f8a.png)

This will bring up a pop-up window where you can search for the Full Name or the Common Name. When searching use the following options:
- Caesalpinia - will bring up the record that has only the characters Caesalpinia in it, ie the genus record.
- Caesalpinia% - will bring up all the records that start with Caesalpinia
- “Caesalpinia a%” - will bring up all the records that start with Caesalpinia a, ie all the Caesalpinia species beginning with “a” (NB, using Caesalpnia a% without the quotation marks will bring up records starting with “A” and ignores the Caesalpinia text.

If you are sure that the name is not in the system, then a new taxon name can be created. Click the **+** button to open the Taxon form. Follow the Instructions for entering a new Taxon.



## To create a new Taxon record from the Taxon form directly.

Click on the Data Entry button on the main menu bar and select Taxon from the pop up.

This will open the Taxon entry screen.

![image](https://user-images.githubusercontent.com/8005676/180252691-320b9487-171c-4be5-a4f1-43965d7279ae.png)

- **Full Name** - this is automatically calculated from the information entered below and is a read only field.
- **Parent of Taxon** - enter the direct parent of the taxon being entered.
  - for a family this would usually be the appropriate order
  - for a genus this would usually be the appropriate family
  - for a species this would usually be the appropriate genus, e.g. the parent of Bellis perennis would be the genus Bellis
  - for a subspecies this would usually be the appropriate species

- **Name** - enter the name of the Taxon at the rank you want to add e.g. to add Bellis perennis the name would be perennis. For cultivars and hybrids, please use the following options:
  - **Cultivar** - enter the cultivar name directly into this field without the single quotation marks. Only the cultivar name should be entered into the Taxon field, eg, if the cultivar is of a species, the species would be the parent.

  ![image](https://user-images.githubusercontent.com/6713716/174128098-249a8bb9-2093-49f9-b827-533a87f3527a.png)

  - **Hybrids** - enter the information as below as well as the Hybrid Information fields.

  - **Hybrid formula** should be entered into this field using the standard x key.

  - **Nothotaxon/Collective** names should be entered into this field including the x in front of the name.
 
 ![image](https://user-images.githubusercontent.com/8005676/180253543-3964eaaf-c3fd-4838-8e3e-ade538cf56a0.png)
  
  - **Infrageneric hybrid** names should be entered into this field including the + in front of the name.

- **Taxonomic Rank** - enter the rank of the Taxon you are adding e.g. the rank would be **species** for Bellis perennis. The available options are presented in the dropdown list. Currently the default is the next rank below the parent.
- **Is Accepted** - this is a read only field for the taxonomic status of the name and this is not edited within the Taxon form. The taxonomy of names are managed separately in the Taxon Tree.
- **Author** - enter the author of the Taxon. Use the standard form and check in IPNI if unsure.
- **LSID** - enter the Life Sciences Identifier (LSID) or equivalent for other taxonomic groups in here. Example of an LSID from IPNI below.
  ![image](https://user-images.githubusercontent.com/6713716/174129301-47a82242-b7af-4de1-919e-0c7e266b791e.png)

### Name Status Section

- **Accepted Taxon** - this is automatically calculated from the Taxon Tree. If the taxon is a synonym in the Taxon Tree the accepted taxon will be visible in this field. This is a read only field in the Taxon form.

  _Tip: To edit the taxonomy, see the section on the Taxon Tree below._

- **Is Hybrid** - tick this checkbox for all kinds of hybrids, eg hybrid formulae, nothotaxa/collective names, infra generic hybrids, etc.

- **Status** - select the nomenclatural status of the name from the picklist. If the name is considered to be legitimate (and therefore valid), this should be left blank. For invalid, illegitimate, not found names, select the appropriate option, e.g. illegitimate, invalid, nomen nudum, later homonym, not found in literature, manuscript name, etc.

  _Tip: Names should be checked in online nomenclators such as IPNI, TROPICOS, Index Fungorum, MycoBank, Index Muscorum, AlgaeBank, etc._

- **Genus Status** - This field was used to bring data across from BG-BASE and will need to be checked, transferred into Status or deleted.
- **Basionym** - Records that had a basionym recorded in BG-BASE had this name migrated here (15 records). We will be looking to see how we manage this in Specify going forwards.

- **Herbarium Num.** - enter the Herbarium Number for the taxon here as appropriate, eg Family number, Genus number, Species number.

- **Homonym?** - This was used for data being migrated from the BG-BASE Genera table. In future, Later Homonyms should be selected in the Status field.

### Hybrid Information

- **Hybrid Parent1** - enter the name of the first parent
- **Hybrid Parent1 Sex** - enter the sex of the first parent if known
- **Hybrid Parent2** - enter the name of the second parent
- **Hybrid Parent2 Sex** - enter the sex of the second parent if known

- **Parentage** - This information has been migrated from BG-BASE and will gradually be cleaned and transferred to the parent fields above.

At any point, to save the record click Save in the bottom right of the screen. The Save and Add Another button saves the record and creates a duplicate - this should not generally be used at present.

## To create a new Taxon record from the Taxon Tree.

Before creating a new Taxon record, ensure that the name does not already exist within the Taxon Tree.

click on the parent of the name being created. Then click on the **add Child** option at the top Right:

![image](https://user-images.githubusercontent.com/8005676/180253832-68875e19-45b8-4166-bd45-47dbf78e5d08.png)

This will open the Taxon form and the instructions above can be followed.
