---
parent: Data Entry
---

# Collection Object Form

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

_Tip: The most recently added Determination will be automatically ticked as the Filed As name. Therefore it is recommended to enter the determinations in the following order: 1) Label name, 2) Det. slips in chronological order with the most recent more likely to be where the specimen is filed. _

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

Please note that we are no longer creating a separate ‘Filing Name’ entry. The ‘Filed as’ tick box will now serve this purpose.

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
