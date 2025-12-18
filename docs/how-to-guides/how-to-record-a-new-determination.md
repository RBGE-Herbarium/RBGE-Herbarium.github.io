---
parent: How-to guides
---

# Determinations - How to record a new determination

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

In Specify, determinations are applied to all Preparations within a Collection Object.

### How to create a new determination for an existing Collection Object

Any name that has been applied to a specimen is treated as a Determination. This includes the Label Name, the Filing Name, Typification names as well as any additional determinations.

![image](https://user-images.githubusercontent.com/8155743/216963564-a59451b8-e05f-4555-af47-07e980063eaf.png)

To add a determination click on Add next to Determinations. A new determination should be added for each name being applied to the specimen.

  _Tip: The most recently added Determination will be automatically ticked as the Filed As name. Therefore it is recommended to enter the determinations in the following order: 1) Label name, 2) Det. slips in chronological order with the most recent more likely to be where the specimen is filed._

The fields are explained below:

- **Name Usage** – enter the usage of the name being associated with the specimen (e.g. Label name, Curatorial annotation, Data Capture name, Det., Fide, Typification). Guidance for each option is given below:
  - **Label name**: The label name is the original name on the label. In some cases it may not be clear whether the name on the label has been added as a later det. If it is not clear, it is recommended to treat it as the label name by default. If there appears to be no label name, then create a record with Unknown as the taxon. The label name is not considered to be a det. and should not have any determiner or date information in it.
  - **Curatorial annotation**: A curatorial annotation refers to any name written on the specimen by curation staff that is not considered to be a det. This can include names written in pencil to indicate the name under which the specimen is filed.
  - **Data Capture Name**: A data capture name is used primarily for minimal data capture where the name entered is the name on the folder where the specimen is filed.
  - **Det.**: A det. name is a name resulting from a taxonomic determination and will be linked to a det slip on the specimen or potentially an electronic det received online or by e-mail.
  - **Fide**: A fide name is where the specimen has been cited in a revision or other taxonomic work.
  - **Typification**: The names for which the specimen is a type are treated as determinations in Specify. Typification determinations should include the type status.
  - **Legacy filing name**: The legacy filing name should not be used for future name usage. It was used during the migration to hold the BG-BASE Filing Name data.

Please note that we are no longer creating a separate ‘Filing Name’ entry. The ‘Filed as’ tick box will now serve this purpose. See the **Filed as** entry below for more information.

- **Taxon** – enter the name of the taxon. Start typing the taxon name and a dropdown of all of the matching names will appear. This is refined as you keep typing.

![image](https://user-images.githubusercontent.com/8005676/180239266-a3e1dccf-63b3-4198-aa4a-ca9c75f70d5e.png)

  _Tip: If the name you are looking for is not in the list then check by clicking on the magnifying glass to search more thoroughly. If you still don’t see the record then you will need to add a new Taxon (see Adding a New Taxon Name)_

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

_Note, you cannot enter the author name as part of the search. Enter the Genus, species name and any intraspecific epithets only._

- **Filed as** – this is automatically ticked as each new determination record is added. Once all determinations have been entered, check that the determination which holds the name under which the specimen is filed is ticked here.

  _Tip: it may be that several determinations have the same taxon name which is where the specimen is filed. If this is the case, as a general rule the most recent determination should have the Filed as box ticked._

- **Prefered Taxon** - if the name entered into Taxon Name is a Synonym, the Prefered Taxon will be displayed here. This is a read only field.
  _Tip: You can copy the Preferred Taxon name even though the field is grayed out, and paste it into a new Filing Name determination._
  
- **Determination Qualifier** – enter the qualifier if present in the determination (e.g. cf., aff. ?, forsan)
- **Determination Addendum** – enter the taxon addendum if present (e.g. sensu latu (s.l.), sensu strictu (s.s.), auct. non Brit. etc.)
- **Determiners** – enter the name(s) of the person(s) who made the determination if known. This is not required for Label name, Data Capture name or Typification determinations.
 - **Remarks** - enter any remarks specific to the determiner of this Preparation.
  To add a determiner click the green + and search for the agent in the query combo box. To add additional determiners click the green +

![image](https://user-images.githubusercontent.com/8155743/216964049-f803d0eb-adc9-41d7-97f1-ba3d0a6b4a62.png)

- **IH Code** – enter the Index Herbarium Code of the determiner if known.
- **Determined Date** - enter the date the determination was made if known. Use the dropdown to the left to select whether it is a Full Date, Mon/Year or Year. This is not required for Label name, Data Capture name or Typification determinations.
- **Det. Barcode** - enter the barcode of the specimen the determination is from. For collection objects which have more than one preparation, this will ensure that it is known which individual specimen was seen and identified. This should be entered for all Dets, Curatorial Annotations and Typification determinations. It is not required for Label name determinations.
- **Verbatim Determination** - this is a read only field for data migrated from BG-BASE
- **Verbatim Determined By** – if there are multiple determiners, enter their names here. This also contains the name of the determiner from BG-BASE
- **Type Status** – for a Typification determination, enter the kind of type (e.g. Holotype, Isotype, Syntype, etc.)
- **Det. Note** - enter any miscellaneous information associated with the determination (e.g. unusually large leaves for this species).
- **Det. Citation** – this holds the citation information relating to the determination as a temporary measure until the Taxon Citation table is in place.
- **Family No.** – do not enter data here. This is a calcuated field for the RBGE family filing number.
- **Genus No.** – do not enter data here. This is a calculated field for the RBGE genus filing number.

- **Free Text Name** - this is a read only field for data migrated from BG-BASE

When all the determinations have been added, check that the correct name has been ticked as the **Filed As** name.

_Note: Be aware that the **Filed As** name is applied to all Preparations within the Collection Object. This should not be an issue for most of the spirit collection, silica-dried collection and much of the carpological collection. If there are other Herbarium Sheet preparations within the Collection Object, they should be checked to ensure that they are physically filed under the Filed As name being selected._

To help decide which name should be used as the **Filed As** name, the following guidance can be used:

When creating a new Collection Object for a Preparation
- If there is only a single name associated with the Collection Object then use this by default
- If there is more than one name associated with the Collection Object then use the most recent det. if it is not a synonym by default
- If the most recent det. is a synonym, then check if there are any other specimens currently filed under this name or the accepted name. If there are, then a decision will need to be made about the curation of these specimens.

When creating a new Preparation under an existing Collection Object
- If the most recent det. agrees with the existing filing name then this name should be used by default
- If the most recent det. does not agree with the existing filing name then a decision will need to be made whether the other specimens can be recurated.

When laying away, **the Filed As** name should be used.

_Note: The number of Determinations is indicated in brackets next to the **Determinations** heading._

### How to remove a Determination

To remove a **Determination** from a record click the bin icon ![image](https://user-images.githubusercontent.com/8005676/180239866-35e869e6-04ec-4e94-9c52-8d23a3473c9f.png).
