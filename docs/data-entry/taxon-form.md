---
parent: Data Entry
---

# Taxon Form

Creating a record in the Taxon Form essentially creates the name as a nomenclatural element and does not include any taxonomic status for the name. Creating relationships between names with synonymy where you are building a taxonomic structure is done in the Taxon Tree.

The taxon form can be opened from the Data Entry button on the main menu, from within the Collection Object form and from within the Taxon tree. The two most common routes will be from within the Collection Object form and from the Taxon tree so these are covered below.


## To create a new Taxon record from the Collection Object form.

Before creating a new Taxon record, ensure that the name does not already exist.

- Start typing the name in the Taxon box to see the drop down list of options

  _Tip: There is currently a limit to the number of taxon names listed in the drop down, so for large genera you will not see all species. In this case, continue to add the beginning of the specific epithet or use wild cards to limit the number of results_
  
![img align="right"](https://user-images.githubusercontent.com/8005676/180251406-cc13332e-e143-49b6-b510-15c74d872dbe.png)

  - Use wildcards (%) to search names more easily

![image](https://user-images.githubusercontent.com/8005676/180251592-5eedf934-acd3-443c-8cea-977032d107af.png)

  - Also use wildcards (%) to check spelling variants or uncertainty

![image](https://user-images.githubusercontent.com/8005676/180251739-f63c7172-d0a1-4d3d-8341-a64622978d0e.png)

  - If it does not come up, then there is an option to do an additional search by clicking on the magnifying glass to the right of the Taxon field.

![image](https://user-images.githubusercontent.com/8005676/180252413-279bcff3-d42e-459b-bdd3-b9d5ca4e2f8a.png)

- This will bring up a pop-up window where you can search for the Full Name or the Common Name. When searching use the following options:
  - Caesalpinia - will bring up the record that has only the characters Caesalpinia in it, ie the genus record.
  - Caesalpinia% - will bring up all the records that start with Caesalpinia
  - “Caesalpinia a%” - will bring up all the records that start with Caesalpinia a, ie all the Caesalpinia species beginning with “a” (NB, using Caesalpnia a% without the quotation marks will bring up records starting with “A” and ignores the Caesalpinia text.

- If you are sure that the name is not in the system, then a new taxon name can be created. Click the **+** button to open the Taxon form. Follow the Instructions for entering a new Taxon.

----

## To create a new Taxon record from the Taxon form directly.

If the name is not in the database then we need to check that the name has been published. 

There are rules governing the creation and publication of new names. In most cases it can be straightforward to find a name and decide about adding it to the database. However, in some cases, it can be a bit more complex and you may want to check. See the section below on Checking names online before entering a new name.

Click on the Data Entry button on the main menu bar and select Taxon from the pop up.

This will open the Taxon entry screen.

![image](https://user-images.githubusercontent.com/8005676/180252691-320b9487-171c-4be5-a4f1-43965d7279ae.png)

- **Full Name** - this is automatically calculated from the information entered below and is a read only field.
- **Parent of Taxon** - enter the direct parent of the taxon being entered.
  - for a family this would usually be the appropriate order
  - for a genus this would usually be the appropriate family
  - for a species this would usually be the appropriate genus, e.g. the parent of _Bellis perennis_ would be the genus _Bellis_
  - for a subspecies this would usually be the appropriate species

- **Name** - enter the name of the Taxon at the rank you want to add e.g. to add _Bellis perennis_ the name would be _perennis_. For cultivars and hybrids, please use the following options:
  - **Cultivar** - enter the cultivar name directly into this field without the single quotation marks. Only the cultivar name should be entered into the Taxon field, eg, if the cultivar is of a species, the species would be the parent.
  - 
  _Tip: Where possible, copy and paste the name from the online resource to reduce typing errors. Ensure that there is no space before or after the name._
  
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

  _Tip: The nomenclatural status should be available in online nomenclators such as IPNI, TROPICOS, World Flora Online, Index Fungorum, MycoBank, Index Muscorum, AlgaeBank, etc._

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

----

## To create a new Taxon record from the Taxon Tree.

Before creating a new Taxon record, ensure that the name does not already exist within the Taxon Tree.

click on the parent of the name being created. Then click on the **add Child** option at the top Right:

![image](https://user-images.githubusercontent.com/6713716/192742249-1e679caa-8882-4989-be8b-7ad057d84256.png)

This will open the Taxon form and the instructions above can be followed.

## To edit the taxonomic status of a Taxon record in the Taxon Tree.

When a new Taxon is created in Specify, by default it will be created as an Accepted taxon.

To transform it into a synonym, select the taxon to by synonymised.
Click the Synonimize button in the top right of the Taxon Tree window

![image](https://user-images.githubusercontent.com/6713716/192743285-981c270a-13f9-4876-a22b-655da9a95087.png)

Click on the Accepted name

![image](https://user-images.githubusercontent.com/6713716/192743514-dbfb6d6c-6820-4ca7-a48f-627fac9090ec.png)

Then click on the Make a synonym button (this will provide clear information about what synonymy event is about to be carried out)

![image](https://user-images.githubusercontent.com/6713716/192743604-40e83b2e-b1c9-446f-9d24-8551e442141a.png)

----

## Checking the name online.

If the name is not in the database then we need to check that the name has been published. 

There are rules governing the creation and publication of new names. In most cases it can be straightforward to find a name and decide whether to add it to the database. However, in some cases, it can be a bit more complex and you may want to check. 

The main things to check for the name are: 

- Presence (can you find it at all?) 
- Spelling 
- Author 
- Nomenclatural status (valid, legitimate) 
- Taxonomic status (accepted, synonym) 
- Hybrid (hybrid formula or nothotaxon/collective name) 

The main resources to use for checking names are listed below: 

### Angiosperms

First option 

IPNI - https://www.ipni.org/ 

This aims to be a complete listing of all vascular plant names that have been published 

- It’s not yet complete, particularly with infraspecific names 
- It provides nomenclatural information (ie, whether a name is legitimate and/or valid) 
- It also provides type information for an increasing number of names 
- It also provides a link to the protologue (where the name was originally published) for an increasing number of names 

Second option (if you can’t find the name in IPNI or are uncertain about information there) 

Tropicos - www.tropicos.org 

- This is stronger on infraspecific names and names in the Americas 
- It has more type information 
- It also provides a link to the protologue 
- It also includes taxonomic information which is less relevant for this project 

Other options 

The World Flora Online - http://www.worldfloraonline.org/ 

Plants of the world online (POWO) - http://www.plantsoftheworldonline.org/  

### Fungi/Lichens

Index fungorum - http://www.indexfungorum.org/

### Bryophytes

Index of Mosses Database (W3MOST) - http://www.mobot.org/mobot/tropicos/most/iom.shtml

### Algae

Algaebase - https://www.algaebase.org/

## Checking spelling 

Similar to the search done in Specify, it makes sense to use a less specific search in these resources to be more likely to find the name in the case of names that have been misspelt or that are difficult to read. 

- Use wildcards, usually an asterisk, to make the search less specific.
- Consider searching for the genus only and looking down the resulting list of species in the genus. 
- Some names have been spelled differently in the literature (not just on labels). These are considered as orthographic (spelling) variants and should have separate name records. 

## Checking author	 

There are a number of names that are identical but where the author may be different. These are not treated as the same name. 

Sometimes, it can be difficult to be sure about these because the author may appear to be different if it’s abbreviated in one version or one of the pieces of the authorship may be missing in one. For example, the parenthetical author (the author in brackets) may be missing in IPNI. 

## Checking status 

The status of the name may be nomenclatural or taxonomic. 

Nomenclatural status is about whether the name is allowed to be used (legitimate, valid) 

Taxonomic is about whether people have decided to use it (accepted, synonym) 

In Specify, the status of the name in the Taxon table will be the nomenclatural status.  

The Taxonomic status of a name is managed through the Taxon tree.  

## Checking hybrids 

If a name is a hybrid name then it can be either: 

Hybrid formula (eg, Magnolia denudata × liliiflora) 

Nothotaxon or collective name (eg, Magnolia × soulangeana) 

- Note the use of the symbol × instead of the letter x 
- In the online resources you will often see the name with the hybrid × sign missing. Please treat these as the same name (there is often disagreement whether a species is a hybrid or not) 

See the section on entering hybrid names for more information 

## Results of the name checking 

If you find the name and it appears to have been published and is both legitimate and valid and is not already in Specify then a new record can be created. 
- If the name is being used as the Filed As determination, then they are generally considered to be Accepted. As names are added they are all considered to be Accepted. It is possible to use a name that is not accepted as a Filed As determination. 
- If there appears to be a spelling mistake and you are confident that they are the same name, then use the correct version of the name for the name record. The misspelt version can be included in remarks in the name record. 
- If the alternative spelling has been used in the literature and can be considered as an orthographic variant, then this can be created as a separate name record, and linked to the correctly spelled version of the name (see the section on linking names for how to do this). 

If you find the name and it is not accepted for a nomenclatural reason (e.g. it is invalid or illegitimate then the appropriate status value should be used, see the Appendix for more information), but the name should still be used as the filing name. 

If you find the name and it does not appear to have been published, then we can still use it but it can be recorded as a Manuscript name. The specimen may have MSS after the name on the label. 

If you don’t find the name in the resources, then again we can still use it but we need to record it as Not found in literature. Include the specimen as a data source. In remarks add the following text ‘Name only found on specimen [barcode]’. 

Follow the instructions above for adding the name to Specify. 
