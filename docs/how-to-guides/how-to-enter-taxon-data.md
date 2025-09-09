---
parent: How-to guides
---

# How to enter taxon data

{: .no_toc }

  {: .no_toc .text-delta }
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

In Specify, all ranks of taxon names are managed in the Taxon table and form. Creating a record in the Taxon Form essentially creates the name as a nomenclatural element and does not include any taxonomic status for the name. Creating relationships between names with synonymy where you are building a taxonomic structure is done in the Taxon Tree.

The taxon form can be opened from the Data Entry button on the main menu, from within the Collection Object form and from within the Taxon tree. The two most common routes will be from within the Collection Object form and from the Taxon tree so these are covered below.

_Note: When entering a primary rank (Family, Genus, Species) new species or name, only use primary ranks as a parent. Secondary rank taxon records (Subfamily, Tribe, Subgenus section, etc) can be created but should only be used for determinations. Example a specimen that has been detted as Rhoododendron subgenus Vireya - this specimen can be used as a determination but any species within this Subgenus would be found within the genus Rhododendron._


## How to create a new Taxon record from the Collection Object form.

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

## How to create a new Taxon record from the Taxon form directly.

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

- **Name** - enter the name of the Taxon at the rank you want to add e.g. to add _Bellis perennis_ the name would be _perennis_. For cultivars and hybrids, please see additional below.

_Tip: Where possible, copy and paste the name from the online resource to reduce typing errors. Ensure that there is no space before or after the name._

  - **Cultivar** - enter the cultivar name directly into this field without the single quotation marks. Only the cultivar name should be entered into the Taxon field, eg, if the cultivar is of a species, the species would be the parent.
  - It is not uncommon for the specific epithet to be dropped. This is because the wild ancestry of the plant is not always known. 
  - The name will be the cultivar name which should be capitalised, e.g. Midwinter 
  - Select Cultivar from the taxonomic rank dropdown 
  - Do not include the single quotes, these will be added automatically

    _Tip: RHS plant finder can be used to check cultivar names: [https://www.rhs.org.uk/plants](https://www.rhs.org.uk/plants)_

  ![image](https://user-images.githubusercontent.com/6713716/174128098-249a8bb9-2093-49f9-b827-533a87f3527a.png)

  - **Hybrids** - enter the information as below as well as the Hybrid Information fields.
  - **Hybrid formula** should be entered into this field using the standard x key.
    - The Parent would be the lowest rank of the name that is already in the system e.g. _Streptocarpus_ 
    - The name would be the first parent x second parent e.g. _confusus_ × _polyanthus_ 
    - The taxonomic rank would be the level at which the name should sit e.g. _Streptocarpus confusus_ × _polyanthus_ would be a species 
    - In most cases, the authors should be left blank since it is not easy to record the authors of both epithets in Specify. 
    - Tick the Is Hybrid check box to indicate that this name is a hybrid.
    - Add these names into the Hybrid Parent 1 and 2 fields (see below) to record the authors.
 
 ![image](https://user-images.githubusercontent.com/6713716/193086203-e05cb132-5bbc-48b6-977f-037c0ebe4bae.png)

  - **Nothotaxon/Collective names** should be entered into this field including the x in front of the name.
    - The Parent would be the lowest rank of the name that is already in the system e.g. Salix 
    - The name would be the collective name e.g. _Salix_ x _ambigua_ 
    - The taxonomic rank would be the level at which the name should sit e.g. _Salix_ x _amibigua_ would be a species 
    - Enter the author as it is given in the online resource
    - Tick the Is Hybrid check box to indicate that this name is a hybrid
    - Add the parents into the Hybrid Parent 1 and 2 fields (see below) if known
 
 ![image](https://user-images.githubusercontent.com/6713716/193085724-781101d2-8236-4e6d-82ba-3f192dcff1bd.png)
 
 ![image](https://user-images.githubusercontent.com/8005676/180253543-3964eaaf-c3fd-4838-8e3e-ade538cf56a0.png)
  
  - **Intergeneric hybrid names** should be entered into this field including the x placed before the name of an intergeneric hybrid. An intervening space is optional. e.g.: _Sorbaronia_ or x _Sorbaronia_ is the name of hybrids between the genera Sorbus and Aronia.

  - **Graft chimaera names** should be entered into this field including a + sign in front of the name.

- **Taxonomic Rank** - enter the rank of the Taxon you are adding e.g. the rank would be **species** for _Bellis perennis_. The available options are presented in the dropdown list. Currently the default is the next rank below the parent.
- **Is Accepted** - this is a read only field for the taxonomic status of the name and this is not edited within the Taxon form. The taxonomy of names are managed separately in the Taxon Tree.
- **Author** - enter the author of the Taxon. Enter the Author of the name as it was found in the online resource. Copy and paste the author from online resource. Please ensure to copy this across exactly with any full stops at the end of the author name as they are often abbreviated to a standard form that is internationally recognised.
  - There should not be any spaces between initials and the last name. 
  - There should be a space between the second bracket and the author name after the brackets 
  - If there are any accents or other diacritical in the name, copying and pasting should ensure that they are maintained in the record. 
  - If you see the same name in two resources, but one resource has additional authors in the name, either in brackets (parenthetical authors), or prefixed by ex or in, please include these in the Author field. Ask if unsure. 
  - If you see the same name in two resources but the author abbreviation is different, please use the abbreviation in IPNI if possible. Ask if unsure. 
 
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

### How to create a taxon record for an unknown species 

If the specimen is filed as an unknown species OR an unknown genus you will only need to create a new taxon record if the genus or family isn’t already in the system. 
- For an unknown species database the specimen using the Genus record e.g. _Bellis_ sp. would be databased as _Bellis_
- For an unknown Genus database the specimen using the Family record e.g. Compositae unk. would be databased as Compositae

### How to create a taxon record for label names with Orthography (spelling variants) or unpublished names 

**How to create a taxon record for an orthographic variant**

For a spelling variant that differs from accepted spelling on one of the online recommended resources. An orthographic name record should only be created for a genuine variant spelling and not for a typo. If it is not clear which it is, then assume it is a typo and use the correct name record if the incorrect spelling occurs on multiple specimens add the variant to the Taxon record in the remarks field. 

E.g. Tropicos has a record for _Scutellaria caerulea_ Moc. & Sessé ex Benth. which is an orthographic variant of _Scutellaria coerulea_ Moc. & Sessé ex Benth. 

Open a new Taxon record and create the name as outlined in the ‘Creating a new Taxon record’ section.  
- For Status select ‘Orthographic Variant’ 

![image](https://user-images.githubusercontent.com/6713716/193086789-b4335363-d099-4945-b555-c69091c19268.png)


**How to create a taxon record for unpublished names or names not found in the literature**

Create a new Taxon record as outlined above 

For a name that is found but does not appear to have been published, eg the IPNI record states that it is a Manuscript name, or the name on the label has MS, or MSS after it, select Manuscript Name from the status dropdown.
- Enter the author if present, otherwise leave blank.

For a name that is not found, enter select Not Found in Literature from the status dropdown and add the following text "Name only found on specimen [barcode]" in the Remarks field.
- Enter the author if present, otherwise leave blank.

----

## To create a new Taxon record from the Taxon Tree.

Before creating a new Taxon record, ensure that the name does not already exist within the Taxon Tree. You cannot currently search for a binomial in the tree search.

![image](https://user-images.githubusercontent.com/6713716/197758149-6e54ab4b-3aae-4f98-b8ba-658c314db17f.png)

click on the parent of the name being created. Then click on the **add Child** option at the top Right:

![image](https://user-images.githubusercontent.com/6713716/197754042-78dc65e3-961a-4b7e-a280-3ee09251351f.png)

This will open the Taxon form and the instructions above can be followed.

## To edit the taxonomic status of a Taxon record in the Taxon Tree.

When a new Taxon is created in Specify, by default it will be created as an Accepted taxon.

To transform it into a synonym, select the taxon to be synonymised.

![image](https://user-images.githubusercontent.com/6713716/197754898-2d81c882-504c-404b-9fec-0817dbea40c5.png)

Click the Synonimize button in the top right of the Taxon Tree window

![image](https://user-images.githubusercontent.com/6713716/192743285-981c270a-13f9-4876-a22b-655da9a95087.png)

Click on the Accepted name

![image](https://user-images.githubusercontent.com/6713716/197754387-30a5b9f9-e5e7-4e8a-b4f1-48704a2d8977.png)

Then click on the Make a synonym button (this will provide clear information about what synonymy event is about to be carried out)

![image](https://user-images.githubusercontent.com/6713716/192743604-40e83b2e-b1c9-446f-9d24-8551e442141a.png)

The synonymised name will now appear in red in the tree and the preferred name will appear when hovering over. In the taxon record, the Accepted Taxon will be automatically updated.

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

IPNI - [https://www.ipni.org/](https://www.ipni.org/)

This aims to be a complete listing of all vascular plant names that have been published 

- It’s not yet complete, particularly with infraspecific names 
- It provides nomenclatural information (ie, whether a name is legitimate and/or valid) 
- It also provides type information for an increasing number of names 
- It also provides a link to the protologue (where the name was originally published) for an increasing number of names 

Second option (if you can’t find the name in IPNI or are uncertain about information there) 

Tropicos - [www.tropicos.org](www.tropicos.org)

- This is stronger on infraspecific names and names in the Americas 
- It has more type information 
- It also provides a link to the protologue 
- It also includes taxonomic information which is less relevant for this project 

Other options 

The World Flora Online - [http://www.worldfloraonline.org/](http://www.worldfloraonline.org/)

Plants of the world online (POWO) - [http://www.plantsoftheworldonline.org/](http://www.plantsoftheworldonline.org/)

Royal Horticultural Society (RHS) - [https://www.rhs.org.uk/plants/search-form](https://www.rhs.org.uk/plants/search-form)

### Fungi/Lichens

Index fungorum - [http://www.indexfungorum.org/](http://www.indexfungorum.org/)

### Bryophytes

Index of Mosses Database (W3MOST) - [http://www.mobot.org/mobot/tropicos/most/iom.shtml](http://www.mobot.org/mobot/tropicos/most/iom.shtml)

### Algae

Algaebase - [https://www.algaebase.org/](https://www.algaebase.org/)

## Checking spelling 

Similar to the search done in Specify, it makes sense to use a less specific search in these resources to be more likely to find the name in the case of names that have been misspelt or that are difficult to read. 

- Use wildcards, usually an asterisk, to make the search less specific.
- Consider searching for the genus only and looking down the resulting list of species in the genus. 
- Some names have been spelled differently in the literature (not just on labels). These are considered as orthographic (spelling) variants and should have separate name records. 

## Checking author

There are a number of names that are identical but where the author may be different. These are not treated as the same name. 

Sometimes, it can be difficult to be sure about these because the author may appear to be different if it’s abbreviated in one version or one of the pieces of the authorship may be missing in one. For example, the parenthetical author (the author in brackets) may be missing in IPNI. These should not be added as separate names, but the correct version of the name should be used.

## Checking status

A name will have both a nomenclatural and taxonomic status. 

Nomenclatural status is about whether the name is allowed to be used (legitimate, valid). It is also used to record if the name has not been found in the literature.

Taxonomic is about whether people have decided to use it (accepted, synonym) 

In Specify, the status field for the name in the Taxon table will be the nomenclatural status.  

The Taxonomic status of a name is managed through the Taxon tree.  

## Checking hybrids 

If a name is a hybrid name then it can be either: 

Hybrid formula (eg, _Magnolia denudata_ × _liliiflora_) 

Nothotaxon or collective name (eg, _Magnolia_ × _soulangeana_) 

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
