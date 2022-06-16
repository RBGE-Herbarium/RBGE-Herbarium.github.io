---
parent: Data Entry
---

# Collection Object Form

In Specify, specimens considered to be part of the same collecting event and assigned the same collector number are entered as individual Preparations with a Collection Object. Preparations currently being stored in Specify include Herbarium sheets/packets (duplicates and multi-sheet specimens), Spirit material and Carpological specimens. Silica-dried material will be held in Specify in the future.

When entering a specimen, consider whether it is possible that there may already be data in Specify for it. Data may have been imported if electronic data were received with the specimens, or there may be a separate related preparation already in the database. If you think that this might be the case, use a query to check. If you need to create a new Collection Object for the Preparation follow the instructions immediately below. If a Collection Object already exists and you want to add a Preparation, then follow the instructions at the bottom of this page.

## Creating a new Preparation in a new Collection Object

To create a new record click on the Data Entry button on the main menu bar:

  ![image](https://user-images.githubusercontent.com/6713716/173833776-fba15b61-20b5-4c79-8eb9-c95759db4f37.png)

Select Collection Object from the pop up:

This opens the Collection Object entry screen

![image](https://user-images.githubusercontent.com/6713716/173834828-ccf9d3c3-e247-450b-b975-0c28894fd896.png)

At any point, to save the record click Save in the bottom right of the screen. The Save and Add Another button saves the record and creates a duplicate - this should not generally be used at present.

![image](https://user-images.githubusercontent.com/6713716/173834912-cc6a6118-0352-4b59-a1ad-6b6abf6b39aa.png)

  _Tip: If you are in a subform as a pop-up window, such as Preparations, then you will need to click Accept first to return to the Collection Object form to click Save._

![image](https://user-images.githubusercontent.com/6713716/173835805-f0a36625-4dd6-4d12-a50e-d40cb28f52d8.png)

The Collection Object form will open as a single form with several sections. Some of these sections are subforms which can be expanded, such as Preparations, Determinations etc. Each of these will expand when you click on Add to the right of the section heading.

![image](https://user-images.githubusercontent.com/6713716/173835949-3955cc71-ad07-436f-936c-e6c5c7b48e86.png)

## Entering data into the record.

Registration Num: Enter the Registration Number if this specimen has been registered in the Registration table. The Registration table is now being used for incoming specimens. Any records from Incoming Gifts/Exchanges in BG-BASE have been migrated here.

_Tip: In Specify, this table was called Accessions, but due to possible confusion for RBGE, it has been renamed Registrations. However, the icon for this table is still ACC._

### Preparations subform

To start adding preparations to a record click on Add next to Preparations

![image](https://user-images.githubusercontent.com/6713716/173838324-cabe9f1c-b314-48b1-902e-4e61a019a9ba.png)

![image](https://user-images.githubusercontent.com/6713716/173838346-871a3128-042c-42e1-b845-1e2502d90c6d.png)

This expands the Preparation entry form as part of the Collection Object form. For each additional preparation needed click Add. The fields are explained below:

- **Prep Type** - select the kind of material (e.g. Herbarium specimen/sheet, Carpological).
- **Barcode** - scan the barcode of the specimen or enter the destructive sample item number. Both should be unique.
- **Is On Loan** - this is a read-only field. It will be automatically ticked if the preparation is on loan
- **Label status** – Enter the status of the label information for this record (e.g. Complete, Partial, Minimal, Unknown)
- **Sheet Number** - enter the number of the sheet in the set if marked on specimen
- **Number in Set** - enter the number of sheets in the set if marked on specimen

- **Storage** – enter the storage location of the specimen (e.g. Main Herbarium, Long Store, Spirit Room, Silica Room, Carpological Collection). For physically linked specimens (where there is more than one specimen permanently mounted on a sheet), the lowest barcode should be created as a storage location and used to store all the specimens on the sheet.
- **Physically linked** - This is a read-only field used for data migrated from BG-BASE. If there is more than one specimen on the herbarium sheet or in the spirit jar (i.e. more than one barcode), this field will have the barcodes of the other specimens with a comma between each barcode.

- **Donor** - enter the name of the Institute/collection that directly donated the specimen to RBGE. (e.g. Glasgow, Herb of John Ball). More guidance will be provided on the use of this field.
- **Herbarium Collection** – enter the name of the Herbarium Collection (e.g. Herb. Greville, Herb. Wight, Herb. Wallich, Herb. Drege) where the herbarium collection differs from the donor and collector. More guidance will be provided on the use of this field.
  - _Tip: Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew and the Herbarium Collection should be entered here. In future, we will be aiming to use the Registrations table to hold more information about these collections._
- **Collection Series** - only enter if a collection series is known.
- **Project** - if applicable select the project from the dropdown list.
- **Label Header** - enter the label header here, eg Flora of Nepal.
- **Label Footer** - enter the label footer here.
- **Remarks** - this currently includes data previously held in: Specimens (associated_mat_misc, curatorial_misc, keyword, misc, other_label_information) and Des_Items (keyword, status_full (linked via specimen_num - denied (D), unavailable (U), no longer required (N) , may be available in the future (F), pending (P), Status_by_full)
- **Internal Misc** – use this field for any internal curatorial information. This currently holds data previously held in: Specimens (int_misc).
 
### Destructive Sampling section

This section should only be completed for preparations created during destructive sampling.

- **Material type** - enter the type of material sample (e.g. Flower sample, Leaf sample, Pollen sample).
- **Derived from** - this is for preparations made for Destructive Sampling ONLY. Enter the barcode of the specimen from which the sample was taken.
- **Prepared By** – enter the person who prepared the sample.
-- _Tip: type in the last name and, if the person is already in the Agents table, their name should come up as one of the options in a list._
- **Prepared Date** – enter the date that the destructive sample was created.
- **Sample Number** – this will be a read-only field for the destructive sample collector number migrated from BG-BASE.
- **Legacy Number** – this is a read-only field for the BG-BASE specimen number.

### Adding more preparations

If there are multiple preparations to add to the Collection Object click add again to add an additional record. Once they are added, preparations will be displayed above the Preparation section of the form.

![image](https://user-images.githubusercontent.com/6713716/173849054-2f3dd2be-13fa-46ef-98b8-ce3eecf0a42e.png)

### Preparation attributes subform

This subform holds additional information about an individual specimen. 

![image](https://user-images.githubusercontent.com/6713716/173849091-5681eaa5-705d-415f-b376-2407db3c44fa.png)

**Please be aware that this subform is not working properly at present and should not be used until the bug is fixed.**

The fields in this section are:

- **Phenology** – enter the phenological state of the specimen. More guidance will be provided for this in future.
- **Treatment** – enter the treatment applied to the specimen during collection, if known.
- **Packet Content** – enter the packet content.
- **Sex** – enter the sex of the plant, if known.

### Preparation attachments

Click on the icon to open up the Preparation Attachments form and add attachments to an individual preparation.

![image](https://user-images.githubusercontent.com/6713716/173849200-f2ca8470-c5b2-462e-95e5-130488e7fedc.png)

Guidance will be provided on the file types to be uploaded. 


### Remove a preparation

Only delete records created in error at present. To remove a Preparation from a record click the dustbin icon next to the Preparation.

![image](https://user-images.githubusercontent.com/6713716/173849269-efc4d1e7-315f-4852-b583-ea424eab5b24.png)

More guidance will be provided on removing preparations, but please use with caution.

## Determinations 

Any name that has been applied to a specimen is treated as a Determination. This includes the Label Name, the BG-BASE Filing Name, Typification names as well as any additional determinations.

![image](https://user-images.githubusercontent.com/6713716/173849431-14a25a9c-13bd-4ee3-9dda-6c91be998db3.png)

To add a determination click on Add next to Determinations. A new determination should be added for each name being applied to the specimen.

  _Tip: The most recently added Determination will be automatically ticked as the Filed As name. Therefore it is recommended to enter the determinations in the following order: 1) Label name, 2) Det. slips in chronological order with the most recent more likely to be where the specimen is filed._

The fields are explained below:

![image](https://user-images.githubusercontent.com/6713716/173849484-622cd430-bdc3-40cb-804a-e0c6e9db05ac.png)

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

![image](https://user-images.githubusercontent.com/6713716/173852934-6d219506-18d1-4594-babd-9e2bf464871c.png)

  _Tip: If the name you are looking for is not in the list then check by clicking on the magnifying glass to search more thoroughly. If you still don’t see the record then you will need to add a new Taxon (see Adding a New Taxon Name)_

- **Filed as** – this is automatically ticked as each new determination record is added. Once all determinations have been entered, check that the determination which holds the name under which the specimen is filed is ticked here.

  _Tip: it may be that several determinations have the same taxon name which is where the specimen is filed. If this is the case, as a general rule the most recent determination should have the Filed as box ticked._

- **Prefered Taxon** - if the name entered into Taxon Name is a Synonym, the Prefered Taxon will be displayed here. This is a read only field.
  _Tip: You can copy and paste the Preferred Taxon name even though the field is grayed out.  Then you can paste it into a new Filing Name determination._
  
- **Determination Qualifier** – enter the qualifier if present in the determination (e.g. cf., aff. ?, forsan)
- **Determination Addendum** – enter the taxon addendum if present (e.g. sensu latu (s.l.), sensu strictu (s.s.), auct. non Brit. etc.)
- **Determined by** – enter the name of the person who made the determination if known. This is not required for Label name, Data Capture name or Typification determinations.
  _Tip: for determinations made by more than one person, enter their names into Verbatim Determined By at present._

- **IH Code** – enter the Index Herbarium Code of the determiner if known.
- **Determined Date** - enter the date the determination was made if known. Use the dropdown to the left to select whether it is a Full Date, Mon/Year or Year. This is not required for Label name, Data Capture name or Typification determinations.
- **Det. Barcode** - enter the barcode of the specimen the determination is from. For collection objects which have more than one preparation, this will ensure that it is known which individual specimen was seen and identified.
- **Verbatim Determination** - this is a read only field for data migrated from BG-BASE
- **Verbatim Determined By** – If there are multiple determiners, enter their names here. This also contains the name of the determiner from BG-BASE
- **Type Status** – for a Typification determination, enter the kind of type (e.g. Holotype, Isotype, Syntype, etc.)
- **Det. Note** - enter any miscellaneous information associated with the determination (e.g. unusually large leaves for this species).
- **Det. Citation** – this holds the citation information relating to the determination as a temporary measure until the Taxon Citation table is in place.
- **Family No.** – this is a calcuated field for the RBGE family filing number.
- **Genus No.** – this is a calculated field for the RBGE genus filing number.

- **Free Text Name** - this is a read only field for data migrated from BG-BASE

When all the determinations have been added, check that the correct name has been ticked as the Filed As name.

Be aware that the Filed As name is applied to all Preparations within the Collection Object. This should not be an issue for most of the spirit collection, silica-dried collection and much of the carpological collection. If there are other Herbarium Sheet preparations within the Collection Object, they should be checked to ensure that they are physically filed under the Filed As name being selected.

To help decide which name should be used as the filing name, the following guidance can be used:

When creating a new Collection Object for a Preparation
- If there is only a single name associated with the Collection Object then use this by default
- If there is more than one name associated with the Collection Object then use the most recent det. if it is not a synonym by default
- If the most recent det. is a synonym, then check if there are any other specimens currently filed under this name or the accepted name. If there are, then a decision will need to be made about the curation of these specimens.

When creating a new Preparation under an existing Collection Object
- If the most recent det. agrees with the existing filing name then this name should be used by default
- If the most recent det. does not agree with the existing filing name then a decision will need to be made whether the other specimens can be recurated.

When laying away, the Filed As name should be used.

The number of Determinations is indicated next to the **Determinations** heading

![image](https://user-images.githubusercontent.com/6713716/173853746-3cee7847-9512-4a72-9d3e-bce755e3da17.png)

To view the different determinations use the scroll bar at the bottom of the Determinations section to move between records

![image](https://user-images.githubusercontent.com/6713716/173853837-95cebefc-9b06-49aa-a709-e6047750af26.png)

### Removing a Determination

To remove a **Determination** from a record click **Delete**.

![image](https://user-images.githubusercontent.com/6713716/173853884-9c46f6e6-a273-429f-8134-c616a7b4e7b1.png)

## Collecting Event

This section contains information about the Collectors and the Collecting Event (where and when the specimens were collected).

![image](https://user-images.githubusercontent.com/6713716/173854369-c78c398b-3da9-4b08-afa2-478070d29f0a.png)

### Collectors

In Specify, all collectors are held in the Agents table, along with expeditions, organisations and institutes.
Where the specimen has been collected under the number series of a primary collector, then all individuals should be entered as separate collectors by adding them in the Collection Object.
  _Tip: the use of the term ‘collected with’ is a good indicator of this kind of number series._

Where the specimen has been collected under the number series of an expedition (whether the expedition is named or uses the surnames of the collectors) then the expedition agent record should be selected. This will have the individuals recorded in the record in the Agents table. For more information on this, please see the guidance on adding new agents.

Where you are not sure whether collectors should be entered as an expedition or as separate individuals, then the following options may help:
- Search for the expedition name first
- Search for the primary collector and check the drop-down list for records which look like groups collecting as an expedition
- Click on the edit symbol to look more closely at any agent record (but remember that any changes made to the record will affect all records in the database attached to that agent!)

To add a Collector to the record click on the Add button next to the Collectors header

![image](https://user-images.githubusercontent.com/6713716/173854446-690a695a-a6ae-44ab-855d-2cfa0ae3eace.png)

This expands the Collectors part of the form

![image](https://user-images.githubusercontent.com/6713716/173855088-dd79a12a-99c4-4beb-9f9f-d90234114d83.png)

- **Agent**: enter the name of the collector or expedition. Start typing the last name of the collector or the name of the expedition and a dropdown of all of the matching names will appear. This is refined as you keep typing.

![image](https://user-images.githubusercontent.com/6713716/173855129-c6ccdec8-c2ce-4cff-bbf6-5b88f2feaad5.png)

  If the name you are looking for is not in the list, then check by clicking on the magnifying glass to search more thoroughly. If you still don’t see the record then you will need to add a new Agent (see Adding a New Agent)
  When there are several collectors listed the first collector is assumed to be the primary collector, with the collection number being theirs.
- **Verbatim Collector Name** - this is a read-only field for the free text collector name in BG-BASE. 
- **Collector Number** - this is the number given to the collection by the collector. This includes any prefixes or suffixes. Do not enter any spaces between any prefixes and suffixes.
- **Collection Date** - enter the date the collection was made in the following format DD/MM/YYYY. Use the dropdown to the left to select whether it is a Full Date, Mon/Year or Year.
- **Second Collection Date** – enter a second date if a range of dates are given on the specimen e.g. 1891-92. Use the dropdown to the left to select whether it is a Full Date, Mon/Year or Year
- **Date as Given** – enter the Collection date here if it cannot be expressed in the Collection Date and Second Collection Date fields e.g. Summer 1893
- **Filing Region** – enter the region under which the specimen is filed. If the specimen is filed under a physically linked specimen mounted from a different region, then select the region under which it would be filed if separate. If the specimen is Cultivated, then select the ‘Cultivated’ option from the drop-down list, unless it is filed under the geographical filing region (there are a small number of families where cultivated specimens are being filed under the wild collected region).
  _Tip: Unless it is known that the specimen is filed different, select the standard geographical filing region._

- **Locality** - All records should have a value in here. This field links to the Locality table and is not equivalent to the free text locality in BG-BASE. It currently includes Country, Sub-Country 1, Sub-Country 2 and Sub-Country 3. Search for the lowest known value and select it from the dropdown. Any locality information below the value entered here should be entered in the Verbatim Locality field below. As a minimum, enter the country here.

![image](https://user-images.githubusercontent.com/6713716/173855222-4b3dfbac-0034-4618-aa3c-f2c7fb31488f.png)

- **Verbatim Locality** – enter any locality information not included in the Locality field above. 
  _Tip: this field equates to the free text locality in BG-BASE. When entering data you will need to make a decision about division of locality and habitat in some cases._
  
- **Landowner** – enter the name of the owner of the land where the collection was made if known. Use the following format: Surname, First name (Cubey Robert) or Surname Initials (Cubey, R.W.) – where the first name is unknown.
- **Habitat** - enter the description of the Habitat in which the specimen was found.
- **Substrate/Host** – enter the substrate or host if the specimen was found growing on another species or substrate e.g. a lichen growing on an Oak branch
- **Collection Misc.** - enter miscellaneous information about the collecting event here.

### Collecting Event Attribute

The Collecting Event Attribute part of the form is used to record information relating to Altitude, Latitude, Longitude and Geo-Referencing.
To add information to the Collecting Event Attribute record click on the Add button next to the Collecting Event Attribute header.

![image](https://user-images.githubusercontent.com/6713716/173856653-8254a378-0440-4ca7-a76b-a2f16fd9d011.png)

This expands the Collecting Event Attribute part of the form

![image](https://user-images.githubusercontent.com/6713716/173856690-2b897dab-adfd-41e1-a48c-c3bdae1121f6.png)

- **Country as Given** - enter the Country as it was given by the collector as it appears on the label (e.g. Burma, German East Africa).
- **Altitude Minimum** - enter the altitude. If a range is given enter the lower value in this field. Enter the unit and any qualifiers in separate fields.
- **Altitude Maximum** – enter the second value if an altitude range is given.
- **Altitude Unit** – enter the measurement unit of the altitude (e.g. m, ft, unknown).
- **Altitude Qualifier** – enter the qualifier for the altitude (e.g. above/greater than, below/less than, ca)
- **Altitude** – this is a temporary read-only field for a direct export from BG-BASE. This is a temporary field and is a read only field. Once the data from BG-BASE have been cleaned to fit the structure of Specify it will be removed.
- **Altitude in Meters** - this is a read-only field for the calculated field from BG-BASE when the altitude on the label was not in meters.
- **Latitude and Longitude**
  Enter the values into the relevant fields. If the latitude and longitude are in decimel minutes (eg 39° 26.23’) then use the DMS option rather than the Decimel Degrees option.
  - Latitude degrees/minutes/seconds
    - **Degrees** - enter the degrees of the Latitude
    - **Minutes** - enter the minutes of the Latitude
    - **Seconds** - enter the seconds of the Latitude
    - **Direction** - enter the direction of the Latitude
  - **Decimal Latitude** - enter the Latitude if it is given as Decimal Degrees
    - **Direction** - enter the direction of the Decimal Latitude
  - **Latitude as Decimal** - this is the calculated field from BG-BASE. This field is read only

  - Longitude degrees/minutes/seconds
    - **Degrees** - enter the degrees of the Longitude
    - **Minutes** - enter the minutes of the Longitude
    - **Seconds** - enter the seconds of the Longitude
    - **Direction** - enter the direction of the Longitude
  - **Decimal Longitude** - enter the Longitude if it is given as Decimal Degrees
    - **Direction** - enter the direction of the Decimal Longitude
  - **Longitude as Decimal** - this is the calculated field from BG-BASE. This field is read only

- **GPS Datum** - enter the datum used, if given (e.g. WGS84). If not explicitly stated then leave as Unknown.
- **GeoRef Source** – enter the source of the georeference (e.g. label, gazetteer, map).
- **National grid** - enter the national grid, if given, for where the specimen was collected
- **Accuracy** – enter the accuracy of the geocoordinate information if known (e.g. <5km from coordinates, 5-20km from corrdinates, > 20km from coodrindates, GPS accuracy, no information).
- **Certainty** – enter the certainty of the geocoordinate information (e.g. Certain, etc.).
 
### Collection Object Information continued

The Description and Number of Duplicates form part of the Collection Object information. These are positioned on the form after the Determinations and Collecting Event information

![image](https://user-images.githubusercontent.com/6713716/173856747-692836b5-34c9-4bbb-8e6d-39b919b66d5f.png)

- **Description** - enter the description of the specimen as given on the label.
- **Number of Duplicates** - enter the number of duplicates that were made when the specimen was collected if known.

- **Remarks** - (this field is currently being added to the form) - enter any additional information about the Collection Object, including Associated Material. When adding Associated material:
  - If the associated material is a **duplicate, spirit or a destructive sample held at RBGE** then a separate **preparation** should be created if not already done
  - If the associated material is **silica gel** then it should be entered into the **silica-dried material database** - a note can be made in **Remarks**.
  - If the associated material is a **DNA sample**, then it should be entered into **EDNA database** - a note can be made in **Remarks**.
  - If the associated material is a **photograph or illustration**, then it should be entered as a note in **Remarks**, prefixed with Associated_mat if possible.
  - If the associated material is a **duplicate herbarium specimen in another institute**, this should be entered as a note in **Remarks**, prefixed with Associated_mat if possible.


## Cultivated Information

In Specify, all cultivated specimen collection data are treated at the same level as wild-collected collection data using the same fields. The specimens are then linked to show the relationship. 

For RBGE cultivated specimens, it is a priority to ensure that the Accession Number and Qualifier are entered.

If the specimen is cultivated enter the Accession Number and Cultivated Source. For cultivated specimens also check the Cultivated tick box.

- **Accession Number** – enter the full 8 digit Accession Number with the Qualifier if known. There should be no space or punctuation between them. Enter the RBGE accession number and qualifier (8 figure number starting with a year) followed by the qualifier of the individual plant from which this specimen has been made, if it comes from the living collections at E. There should be no space or punctuation between the accession number and qualifier. If the qualifier is not known then just enter the accession number alone. If it has a pre-1968 accession number please contact the Plant Records Officer
- **Cultivated Source** – enter the name of the donor of the cultivated material if known.
- **Cultivated** – tick the Cultivated check box if the specimen is cultivated
- **Cultivated From** – enter the wild collected Collection Object record number (not barcode) if known.

### Collection Object Attribute

The Collection Object Attribute part of the form is used to record information relating to Phenology, Abundance, Sample size, Population and Area of Occupancy
To add information to the Collection Object Attribute record click on the Add button next to the Collection Object Attribute header.

This expands the Collection Object Attribute part of the form

- **Sample** - select an option from the dropdown to describe the genetic variability of the specimen
- **Abundance** - select an option from the dropdown to describe the abundance of this taxon where it was collected
- **Population Size** - enter the number of individuals of this taxon found in this population
- **Population Size Qualifier** - select an option from the dropdown to qualify the estimate of the population size
- **Area of Occupancy** - enter the size of the area occupied by this population
- **Area of Occupancy Qualifier** - select an option from the dropdown specifying the unit for the area of occupancy 

### Collection Object Properties

The Collection Object Properties part of the form is used to record information relating to Uses and Local Name

To add information to the Collection Object Properties record click on the Add button next to the Collection Object Properties header.

This expands the Collection Object Properties part of the form

- **Local name or usage** – select whether the property is a local name or use.
- **Text** – for local names, enter any local (vernacular) names associated with this specimen if noted. For usage, enter a description of the use if known.
- **Language** - enter the language of the Local name or use if noted

Please note: if there is both a Use and a Local Name given enter one and then add an additional record to add the other.

### Collection Object Attachments

It is possible to attach documents and images to a Collection Object record.

Additional Record Data
- **Catalogue Number** - this is automatically added to the record when it is saved
- **GUID** - a unique identifier, generated by Specify. This field is read only
- **Record Created By** - name of the Agent who created the record. This field is read only
- **Created Date** - the date the record was created. This field is ready only
- **Record Modified By** -  name of the Agent who modified the record. This field is read only
- **Modified Date** - the date the record was modified. This field is read only 

## To create a new Preparation for an existing Collection Object

