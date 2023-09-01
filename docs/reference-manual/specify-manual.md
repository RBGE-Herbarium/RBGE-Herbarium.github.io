---
parent: Reference manual
---

# Specify reference manual

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

## Collection Object Form

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Specify table</strong>
   </th> 
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Registration Num
   </td>
    <td>Collection Object
   </td>
  <td>Registration number is the number allocated to a group of specimens as they enter the herbarium collection.
   </td>
   <td>Examples to be added
   </td>
  </tr>
</table>

### Preparation subform

<table>
    <tr>
        <th>Prep type</th>
        <td>Preparation</td>
        <td>Select the kind of material (e.g. Herbarium sheet, Carpological)</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Barcode</th>
        <td>Preparation</td>
        <td>For Herbarium sheets the format is E + 8 digits, which are assigned from the physical barcodes. For Destructive samples the format is the Destructive sampling request number followed by a running number for each sample with no leading 0s.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Is on loan</th>
        <td>Preparation</td>
        <td>This is an automatically calculated field which pulls information from the Loans table. This is read only. It will be checked if the preparation is currently out on loan.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Show Interactions</th>
        <td>Preparation</td>
        <td>This is a button which automatically queries the Loan and Destructive Sampling tables, opening a pop-up window which lists any transactions for this preparation.</td>
        <td></td>
    </tr>
    <tr>
        <th>Label status</th>
        <td>Preparation</td>
        <td>This is used to indicate the level of transcription carried out from the specimen labels. The options are Minimal, Partial, Complete or Unknown.</td>
        <td></td>
    </tr>
    <tr>
        <th>Sheet Num.</th>
        <td>Preparation</td>
        <td>This is used to record the number of the sheet when it is part of a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the sheet number should be recorded here, the total number in the set should be recorded separately.</td>
        <td></td>
    </tr>
    <tr>
        <th>Num. in Set</th>
        <td>Preparation</td>
        <td>This is used to record the total number of sheets when there is a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the total number in the set should be recorded here, the individual sheet numbers should be recorded separately.</td>
        <td></td>
    </tr>
    <tr>
        <th>Storage</th>
        <td>Preparation</td>
        <td>This is used to record the storage location of the specimen (e.g. Main Herbarium, Long Store, Spirit Room, Silica Room, Carpological Collection). For lichens which are classified taxonomically under the fungal element, this is used to record the specimens that are physically stored as lichenised fungi. For physically linked specimens (where there is more than one specimen permanently mounted on a sheet), the lowest barcode should be created as a storage location and used to store all the specimens on the sheet. For the spirit collection, this is used to record the running number for each of the specimens.</td>
        <td></td>
    </tr>
    <tr>
        <th>Physically Linked</th>
        <td>Preparation</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>Donor</th>
        <td>Preparation</td>
        <td>This is used to record the name of the Institute/collection that directly donated the specimen to RBGE. (e.g. Glasgow, Herb of John Ball). More guidance will be provided on the use of this field. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew.</td>
        <td></td>
    </tr>
    <tr>
        <th>Herbarium Collection</th>
        <td>Preparation</td>
        <td>This is used to record the name of the Herbarium Collection (e.g. Herb. Greville, Herb. Wight, Herb. Wallich, Herb. Drege) where the herbarium collection differs from the donor and collector. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew and the Herbarium Collection should be entered here. More guidance will be provided on the use of this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Series</th>
        <td>Preparation</td>
        <td>Enter the former herbarium collection series number. This is a running number assigned to each specimen used by some herbaria (not practised RBGE) and often differs from the collector number.</td>
        <td></td>
    </tr>
    <tr>
        <th>Project</th>
        <td>Preparation</td>
        <td>This is used to record a project for the Preparation. If applicable select the project from the dropdown list. At present it is only possible to select a single project so this field should be used with caution.</td>
        <td></td>
    </tr>
    <tr>
        <th>Label Header</th>
        <td>Preparation</td>
        <td>This is used to record the label header. It enables the correct formatting of labels if they are being printed from Specify.</td>
        <td></td>
    </tr>
    <tr>
        <th>Label Footer</th>
        <td>Preparation</td>
        <td>This is used to record the label footer. It enables the correct formatting of labels if they are being printed from Specify.</td>
        <td></td>
    </tr>
    <tr>
        <th>Remarks</th>
        <td>Preparation</td>
        <td>This is used to record any remarks relevant to the individual Preparation. Any information entered here may be visible to the general public. For remarks relevant to the Collection Object as a whole, use the Remarks field below Specimen Description.</td>
        <td></td>
    </tr>
    <tr>
        <th>Internal Misc</th>
        <td>Preparation</td>
        <td>This is used to record any internal information relevant to the individual Preparation. Any information entered here will not be visible to the general public.</td>
        <td></td>
    </tr>
    <tr>
        <th>Count</th>
        <td>Preparation</td>
        <td>This is an internal administrative field and should not be edited. The field does not have a caption and by default it will contain the integer &quot;1&quot;.</td>
        <td></td>
    </tr>
</table>

#### Preparation Attribute section

<table>
    <tr>
        <th>Phenology</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the phenological state of the specimen. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Treatment</th>
        <td>Preparation Attribute</td>
        <td>This is used to record any treatment used during the collection or preparation process.</td>
        <td></td>
    </tr>
    <tr>
        <th>Packet Content</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the contents of the packet or capsule attached to the specimen.</td>
        <td></td>
    </tr>
    <tr>
        <th>Sex</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the sex of the specimen.</td>
        <td></td>
    </tr>
</table>

#### Destructive Sampling section

<table>
    <tr>
        <th>Material type</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the type of material of the sample. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Derived From</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the barcode of the specimen from which the sample was taken. This is for preparations made for Destructive Sampling only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Prepared Date</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the date on which the sample was taken. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
</table>

#### Preparation subform (continued)

<table>
    <tr>
        <th>Legacy Number</th>
        <td>Preparation</td>
        <td>This has been used to record the Specimen number of the record in BG-BASE. It is read only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Preparation attachments</th>
        <td>Preparation</td>
        <td>This button is used to upload attachments relevant to the individual Preparation. Any attachments relevant to the Collection Object as a whole should be uploaded using the Collection Object attachments button at the foot of the form.</td>
        <td></td>
    </tr>
    <tr>
        <th>Counter</th>
        <td>Preparation</td>
        <td>This is for Specify management purposes. It is automatically filled and should not be edited.</td>
        <td></td>
    </tr>
</table>

### Collecting Event subform

#### Collectors section

<table>
    <tr>
        <th>Agent</th>
        <td>Collector</td>
        <td>This field links to the Agent table. The look-up has been formatted to search for the last name. The results have been formatted to include the full name, abbreviation, and dates to help select the correct record. All collectors are held in the Agents table, along with expeditions, organisations and institutes. Where the specimen has been collected under the number series of a primary collector, then a Group Agent record should not be used and each individual should be entered as a separate collector in the Collection Object record. The first collector entered is treated as the primary collector. Expeditions are treated as Group Agent records in the Agents table. Expeditions are defined by a having a unique collection number series that doesn’t belong to a particular individual. They may have an expedition name or the name may be a list of the surnames of the collectors. All collectors that took part in an expedition should be added as participants to a Group Agent record. Account for day-to-day discrepancies by added abscences of particular individuals in the remarks field of the Group Agent record. For more information on this, please see the guidance on adding new agents.</td>
        <td></td>
    </tr>
    <tr>
        <th>Verbatim Collector Name</th>
        <td>Collecting Event</td>
        <td>This has been used to record the free text collector name from BG-BASE. Where this is the case, the name will be prefixed by &quot;From BG-BASE&quot; and the Collector Code.</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Date</th>
        <td>Collecting Event</td>
        <td>This is used to record the date on which the Collection Object was collected. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Second Collection Date</th>
        <td>Collecting Event</td>
        <td>This is used to record a second collection date if the Collection Object was collected over a period of time. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Date as given</th>
        <td>Collecting Event</td>
        <td>This is used to record the date on which the Collection Object was collected if it does not align with a standard date.</td>
        <td>Spring, Summer, Autumn, Winter</td>
    </tr>
</table>

### Collecting Event subform (continued)

<table>
    <tr>
        <th>Filing Region</th>
        <td>Collecting Event</td>
        <td>This is used to record the Filing Region used in the Herbarium for Vascular plants. Since the Cultivated specimens are filed under Cultivated as an equivalent to the filing region, this is included in this field. Although carpological and spirit material are not filed under Filing Regions, this information would be present if there are Herbarium Sheets within the Collection Object. It would normally be left blank for cryptogam specimens.</td>
        <td></td>
    </tr>
    <tr>
        <th>Locality</th>
        <td>Collecting Event</td>
        <td>This field links to the Locality table which contains the geographic locality data according to the GADM standard. It includes administrative areas of all countries and currently includes Country, Sub-Country 1, Sub-Country 2 and Sub-Country 3. The Locality table is locked so new values can not be added by all users. Search for the lowest known value and select it from the dropdown. Any locality information below the value entered here should be entered in the Verbatim Locality field below. As a minimum, enter the country here.</td>
        <td></td>
    </tr>
    <tr>
        <th>Verbatim locality</th>
        <td>Collecting Event</td>
        <td>This is used to record any locality information not included in the Locality field above. When entering data a decision will need to be made about division of locality and habitat in some cases.</td>
        <td></td>
    </tr>
    <tr>
        <th>Habitat</th>
        <td>Collecting Event</td>
        <td>This is used to record the description of the Habitat in which the specimen was found.</td>
        <td></td>
    </tr>
    <tr>
        <th>Substrate/Host</th>
        <td>Collecting Event</td>
        <td>This is used to record the substrate or host if the specimen was found growing on another species or substrate e.g. a lichen growing on an Oak branch.</td>
        <td></td>
    </tr>
    <tr>
        <th>Landowner</th>
        <td>Collecting Event</td>
        <td>This is used to record the name of the owner of the land where the collection was made if known. Use the following format: Surname, First name or Surname Initials where the first name is unknown.</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Misc.</th>
        <td>Collecting Event</td>
        <td>This is used to record miscellaneous information about the Collecting Event.</td>
        <td></td>
    </tr>
</table>

### Collecting Event Attribute section

<table>
    <tr>
        <th>Country as Given</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the country name as it appears on the label, particularly if it does not correspond to a country in the Localities table.</td>
        <td>New Holland</td>
    </tr>
    <tr>
        <th>Altitude min.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the altitude at which the specimen was collected. This field should be used if there is only a single value, or for the lower value if there are two altitudes given.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude max.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the maximum altitude at which the specimen was collected if there are two values given.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude Unit</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the measurement unit of the altitude. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude Qual.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the any qualifier given for the altitude value. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>Transcribed type</th>
        <td>Collecting Event Attribute</td>
        <td>This field is used to record the format of the geographical coordinates, i.e. Decimal Degrees or Degrees Minutes Seconds.</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Degrees</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the degrees of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Minutes</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the minutes of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Seconds</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the seconds of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Degrees</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the degrees of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Minutes</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the minutes of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Seconds</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the seconds of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Decimal Latitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the latitude of Decimalitude</td>
        <td></td>
    </tr>
    <tr>
        <th>DLat Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Decimal Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Decimal Longitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the Decimal Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>DLong Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Decimal Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>GPS Datum</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the GPS datum</td>
        <td></td>
    </tr>
    <tr>
        <th>GeoRef Source</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the source of the geocoordinates</td>
        <td></td>
    </tr>
    <tr>
        <th>National Grid</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the National Grid location</td>
        <td></td>
    </tr>
    <tr>
        <th>Accuracy</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the accuracy of the geocoordinates</td>
        <td></td>
    </tr>
    <tr>
        <th>Certainty</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the certainty of the geocoordinates</td>
        <td></td>
    </tr>
</table>

### Collection Object form (continued)

<table>
    <tr>
        <th>Specimen Description</th>
        <td>Collection Object</td>
        <td>This is used to record the description on the label of the organism</td>
        <td></td>
    </tr>
    <tr>
        <th>Remarks</th>
        <td>Collection Object</td>
        <td>This is used to record any remarks relating to the Collection Object as a whole</td>
        <td></td>
    </tr>
    <tr>
        <th>Num. Duplicates</th>
        <td>Collection Object</td>
        <td>This is used to record the number of duplicate specimens</td>
        <td></td>
    </tr>
    <tr>
        <th>Duplicates</th>
        <td>Collection Object</td>
        <td>This is used to record the locality of the duplicate specimens</td>
        <td></td>
    </tr>
    <tr>
        <th>Associated Material</th>
        <td>Collection Object</td>
        <td>This is used to record Associated Material which are not Preparations recorded in Specify</td>
        <td></td>
    </tr>
</table>

#### Cultivated Information subform

<table>
    <tr>
        <th>RBGE Living Collection Accession No.</th>
        <td>Collection Object</td>
        <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Wild Data</th>
        <td>Collection Object</td>
        <td>This is used to record the wild collecting event information if there are insufficient data to create a separate Collection Object record</td>
        <td></td>
    </tr>
    <tr>
        <th>Cultivated From</th>
        <td>Collection Object</td>
        <td>This is used to record the catalogue number of the Collection Object from the wild collecting event</td>
        <td></td>
    </tr>
</table>

### Collection Object Attribute section

<table>
    <tr>
        <th>Sample</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the genetic variability of the sample</td>
        <td></td>
    </tr>
    <tr>
        <th>Abundance</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the abundance of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Population Size</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the population size of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Population Size Qual.</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the qualifier for the measurement of the population size of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Area of Occupancy</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the area occupancey for the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Area of Occupancy Unit</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the unit of measurement of the area of occupancy for the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>HRP Num.</th>
        <td>Collection Object Attribute</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field. It has been used to record the Herbarium Restriction Permit Number.</td>
        <td></td>
    </tr>
    <tr>
        <th>Tree Number</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the tree number from which the specimen was collected</td>
        <td></td>
    </tr>
</table>

### Collection Object Properties section

<table>
    <tr>
        <th>Local name or use</th>
        <td>Collection Object Property</td>
        <td>This is used to record the local name or use of the species collected</td>
        <td></td>
    </tr>
    <tr>
        <th>Text</th>
        <td>Collection Object Property</td>
        <td>This is used to record additional text relating to the use of the species</td>
        <td></td>
    </tr>
    <tr>
        <th>Language</th>
        <td>Collection Object Property</td>
        <td>This is used to record the language of the local name</td>
        <td></td>
    </tr>
</table>

### Collection Object form (continued)

<table>
    <tr>
        <th>Attachment</th>
        <td>Collection Object</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <th>Created By Agent</th>
        <td>Collection Object</td>
        <td>This automatically records the name of the person creating the Collection Object record from the log-in information</td>
        <td></td>
    </tr>
    <tr>
        <th>Created Date</th>
        <td>Collection Object</td>
        <td>This automatically records the date and time when the Collection Object record was created</td>
        <td></td>
    </tr>
    <tr>
        <th>Modified By Agent</th>
        <td>Collection Object</td>
        <td>This automatically records the name of the person modifying the Collection Object record from the log-in information</td>
        <td></td>
    </tr>
    <tr>
        <th>Modified Date</th>
        <td>Collection Object</td>
        <td>This automatically records the date and time when the Collection Object record was modified</td>
        <td></td>
    </tr>
    <tr>
        <th>Catalog Number</th>
        <td>Collection Object</td>
        <td>Format is 8 digits. An automatically incremental value is allocated by the system. Read only. Be aware that this may not be the same number as the value in the Collection url.</td>
        <td></td>
    </tr>
    <tr>
        <th>GUID</th>
        <td>Collection Object</td>
        <td>This is used to record the Globally Unique Identifier (GUID) which is assigned automatically</td>
        <td></td>
    </tr>
</table>

## A-Z

<table>
    <tr>
        <th>Specify field</th>
        <td>Specify table</td>
        <td>Description</td>
        <td>Examples</td>
    </tr>
    <tr>
        <th>Abundance</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the abundance of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Accuracy</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the accuracy of the geocoordinates</td>
        <td></td>
    </tr>
    <tr>
        <th>Agent</th>
        <td>Collector</td>
        <td>This field links to the Agent table. The look-up has been formatted to search for the last name. The results have been formatted to include the full name, abbreviation, and dates to help select the correct record. All collectors are held in the Agents table, along with expeditions, organisations and institutes. Where the specimen has been collected under the number series of a primary collector, then a Group Agent record should not be used and each individual should be entered as a separate collector in the Collection Object record. The first collector entered is treated as the primary collector. Expeditions are treated as Group Agent records in the Agents table. Expeditions are defined by a having a unique collection number series that doesn’t belong to a particular individual. They may have an expedition name or the name may be a list of the surnames of the collectors. All collectors that took part in an expedition should be added as participants to a Group Agent record. Account for day-to-day discrepancies by added abscences of particular individuals in the remarks field of the Group Agent record. For more information on this, please see the guidance on adding new agents.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude max.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the maximum altitude at which the specimen was collected if there are two values given.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude min.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the altitude at which the specimen was collected. This field should be used if there is only a single value, or for the lower value if there are two altitudes given.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude Qual.</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the any qualifier given for the altitude value. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Altitude Unit</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the measurement unit of the altitude. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Area of Occupancy</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the area occupancey for the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Area of Occupancy Unit</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the unit of measurement of the area of occupancy for the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Associated Material</th>
        <td>Collection Object</td>
        <td>This is used to record Associated Material which are not Preparations recorded in Specify</td>
        <td></td>
    </tr>
    <tr>
        <th>Attachment</th>
        <td>Collection Object</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <th>Barcode</th>
        <td>Preparation</td>
        <td>For Herbarium sheets the format is E + 8 digits, which are assigned from the physical barcodes. For Destructive samples the format is the Destructive sampling request number followed by a running number for each sample with no leading 0s.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Catalog Number</th>
        <td>Collection Object</td>
        <td>Format is 8 digits. An automatically incremental value is allocated by the system. Read only. Be aware that this may not be the same number as the value in the Collection url.</td>
        <td></td>
    </tr>
    <tr>
        <th>Certainty</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the certainty of the geocoordinates</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Date</th>
        <td>Collecting Event</td>
        <td>This is used to record the date on which the Collection Object was collected. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Misc.</th>
        <td>Collecting Event</td>
        <td>This is used to record miscellaneous information about the Collecting Event.</td>
        <td></td>
    </tr>
    <tr>
        <th>Collection Series</th>
        <td>Preparation</td>
        <td>Enter the former herbarium collection series number. This is a running number assigned to each specimen used by some herbaria (not practised RBGE) and often differs from the collector number.</td>
        <td></td>
    </tr>
    <tr>
        <th>Count</th>
        <td>Preparation</td>
        <td>This is an internal administrative field and should not be edited. The field does not have a caption and by default it will contain the integer &quot;1&quot;.</td>
        <td></td>
    </tr>
    <tr>
        <th>Counter</th>
        <td>Preparation</td>
        <td>This is for Specify management purposes. It is automatically filled and should not be edited.</td>
        <td></td>
    </tr>
    <tr>
        <th>Country as Given</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the country name as it appears on the label, particularly if it does not correspond to a country in the Localities table.</td>
        <td>New Holland</td>
    </tr>
    <tr>
        <th>Created By Agent</th>
        <td>Collection Object</td>
        <td>This automatically records the name of the person creating the Collection Object record from the log-in information</td>
        <td></td>
    </tr>
    <tr>
        <th>Created Date</th>
        <td>Collection Object</td>
        <td>This automatically records the date and time when the Collection Object record was created</td>
        <td></td>
    </tr>
    <tr>
        <th>Cultivated From</th>
        <td>Collection Object</td>
        <td>This is used to record the catalogue number of the Collection Object from the wild collecting event</td>
        <td></td>
    </tr>
    <tr>
        <th>Date as given</th>
        <td>Collecting Event</td>
        <td>This is used to record the date on which the Collection Object was collected if it does not align with a standard date.</td>
        <td>Spring, Summer, Autumn, Winter</td>
    </tr>
    <tr>
        <th>Decimal Latitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the latitude of Decimalitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Decimal Longitude</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the Decimal Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Derived From</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the barcode of the specimen from which the sample was taken. This is for preparations made for Destructive Sampling only.</td>
        <td></td>
    </tr>
    <tr>
        <th>DLat Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Decimal Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>DLong Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Decimal Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Donor</th>
        <td>Preparation</td>
        <td>This is used to record the name of the Institute/collection that directly donated the specimen to RBGE. (e.g. Glasgow, Herb of John Ball). More guidance will be provided on the use of this field. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew.</td>
        <td></td>
    </tr>
    <tr>
        <th>Duplicates</th>
        <td>Collection Object</td>
        <td>This is used to record the locality of the duplicate specimens</td>
        <td></td>
    </tr>
    <tr>
        <th>Filing Region</th>
        <td>Collecting Event</td>
        <td>This is used to record the Filing Region used in the Herbarium for Vascular plants. Since the Cultivated specimens are filed under Cultivated as an equivalent to the filing region, this is included in this field. Although carpological and spirit material are not filed under Filing Regions, this information would be present if there are Herbarium Sheets within the Collection Object. It would normally be left blank for cryptogam specimens.</td>
        <td></td>
    </tr>
    <tr>
        <th>GeoRef Source</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the source of the geocoordinates</td>
        <td></td>
    </tr>
    <tr>
        <th>GPS Datum</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the GPS datum</td>
        <td></td>
    </tr>
    <tr>
        <th>GUID</th>
        <td>Collection Object</td>
        <td>This is used to record the Globally Unique Identifier (GUID) which is assigned automatically</td>
        <td></td>
    </tr>
    <tr>
        <th>Habitat</th>
        <td>Collecting Event</td>
        <td>This is used to record the description of the Habitat in which the specimen was found.</td>
        <td></td>
    </tr>
    <tr>
        <th>Herbarium Collection</th>
        <td>Preparation</td>
        <td>This is used to record the name of the Herbarium Collection (e.g. Herb. Greville, Herb. Wight, Herb. Wallich, Herb. Drege) where the herbarium collection differs from the donor and collector. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew and the Herbarium Collection should be entered here. More guidance will be provided on the use of this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>HRP Num.</th>
        <td>Collection Object Attribute</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field. It has been used to record the Herbarium Restriction Permit Number.</td>
        <td></td>
    </tr>
    <tr>
        <th>Internal Misc</th>
        <td>Preparation</td>
        <td>This is used to record any internal information relevant to the individual Preparation. Any information entered here will not be visible to the general public.</td>
        <td></td>
    </tr>
    <tr>
        <th>Is on loan</th>
        <td>Preparation</td>
        <td>This is an automatically calculated field which pulls information from the Loans table. This is read only. It will be checked if the preparation is currently out on loan.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Label Footer</th>
        <td>Preparation</td>
        <td>This is used to record the label footer. It enables the correct formatting of labels if they are being printed from Specify.</td>
        <td></td>
    </tr>
    <tr>
        <th>Label Header</th>
        <td>Preparation</td>
        <td>This is used to record the label header. It enables the correct formatting of labels if they are being printed from Specify.</td>
        <td></td>
    </tr>
    <tr>
        <th>Label status</th>
        <td>Preparation</td>
        <td>This is used to indicate the level of transcription carried out from the specimen labels. The options are Minimal, Partial, Complete or Unknown.</td>
        <td></td>
    </tr>
    <tr>
        <th>Landowner</th>
        <td>Collecting Event</td>
        <td>This is used to record the name of the owner of the land where the collection was made if known. Use the following format: Surname, First name or Surname Initials where the first name is unknown.</td>
        <td></td>
    </tr>
    <tr>
        <th>Language</th>
        <td>Collection Object Property</td>
        <td>This is used to record the language of the local name</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Degrees</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the degrees of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Minutes</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the minutes of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Lat Seconds</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the seconds of Latitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Legacy Number</th>
        <td>Preparation</td>
        <td>This has been used to record the Specimen number of the record in BG-BASE. It is read only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Local name or use</th>
        <td>Collection Object Property</td>
        <td>This is used to record the local name or use of the species collected</td>
        <td></td>
    </tr>
    <tr>
        <th>Locality</th>
        <td>Collecting Event</td>
        <td>This field links to the Locality table which contains the geographic locality data according to the GADM standard. It includes administrative areas of all countries and currently includes Country, Sub-Country 1, Sub-Country 2 and Sub-Country 3. The Locality table is locked so new values can not be added by all users. Search for the lowest known value and select it from the dropdown. Any locality information below the value entered here should be entered in the Verbatim Locality field below. As a minimum, enter the country here.</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Degrees</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the degrees of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Direction</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the direction of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Minutes</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the minutes of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Long Seconds</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the seconds of Longitude</td>
        <td></td>
    </tr>
    <tr>
        <th>Material type</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the type of material of the sample. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Modified By Agent</th>
        <td>Collection Object</td>
        <td>This automatically records the name of the person modifying the Collection Object record from the log-in information</td>
        <td></td>
    </tr>
    <tr>
        <th>Modified Date</th>
        <td>Collection Object</td>
        <td>This automatically records the date and time when the Collection Object record was modified</td>
        <td></td>
    </tr>
    <tr>
        <th>National Grid</th>
        <td>Collecting Event Attribute</td>
        <td>This is used to record the National Grid location</td>
        <td></td>
    </tr>
    <tr>
        <th>Num. Duplicates</th>
        <td>Collection Object</td>
        <td>This is used to record the number of duplicate specimens</td>
        <td></td>
    </tr>
    <tr>
        <th>Num. in Set</th>
        <td>Preparation</td>
        <td>This is used to record the total number of sheets when there is a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the total number in the set should be recorded here, the individual sheet numbers should be recorded separately.</td>
        <td></td>
    </tr>
    <tr>
        <th>Packet Content</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the contents of the packet or capsule attached to the specimen.</td>
        <td></td>
    </tr>
    <tr>
        <th>Phenology</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the phenological state of the specimen. There is a predefined set of options which should be used.</td>
        <td></td>
    </tr>
    <tr>
        <th>Physically Linked</th>
        <td>Preparation</td>
        <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.</td>
        <td></td>
    </tr>
    <tr>
        <th>Population Size</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the population size of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Population Size Qual.</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the qualifier for the measurement of the population size of the species in the collecting area</td>
        <td></td>
    </tr>
    <tr>
        <th>Prep type</th>
        <td>Preparation</td>
        <td>Select the kind of material (e.g. Herbarium sheet, Carpological)</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Preparation attachments</th>
        <td>Preparation</td>
        <td>This button is used to upload attachments relevant to the individual Preparation. Any attachments relevant to the Collection Object as a whole should be uploaded using the Collection Object attachments button at the foot of the form.</td>
        <td></td>
    </tr>
    <tr>
        <th>Prepared Date</th>
        <td>Destructive Sampling</td>
        <td>This is used to record the date on which the sample was taken. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Project</th>
        <td>Preparation</td>
        <td>This is used to record a project for the Preparation. If applicable select the project from the dropdown list. At present it is only possible to select a single project so this field should be used with caution.</td>
        <td></td>
    </tr>
    <tr>
        <th>RBGE Living Collection Accession No.</th>
        <td>Collection Object</td>
        <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer.</td>
        <td>Examples to be added</td>
    </tr>
    <tr>
        <th>Registration Num</th>
        <td>Collection Object</td>
        <td>Registration number is the number allocated to a group of specimens as they enter the herbarium collection.</td>
        <td></td>
    </tr>
    <tr>
        <th>Remarks</th>
        <td>Collection Object</td>
        <td>This is used to record any remarks relating to the Collection Object as a whole</td>
        <td></td>
    </tr>
    <tr>
        <th>Remarks</th>
        <td>Preparation</td>
        <td>This is used to record any remarks relevant to the individual Preparation. Any information entered here may be visible to the general public. For remarks relevant to the Collection Object as a whole, use the Remarks field below Specimen Description.</td>
        <td></td>
    </tr>
    <tr>
        <th>Sample</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the genetic variability of the sample</td>
        <td></td>
    </tr>
    <tr>
        <th>Second Collection Date</th>
        <td>Collecting Event</td>
        <td>This is used to record a second collection date if the Collection Object was collected over a period of time. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.</td>
        <td></td>
    </tr>
    <tr>
        <th>Sex</th>
        <td>Preparation Attribute</td>
        <td>This is used to record the sex of the specimen.</td>
        <td></td>
    </tr>
    <tr>
        <th>Sheet Num.</th>
        <td>Preparation</td>
        <td>This is used to record the number of the sheet when it is part of a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the sheet number should be recorded here, the total number in the set should be recorded separately.</td>
        <td></td>
    </tr>
    <tr>
        <th>Show Interactions</th>
        <td>Preparation</td>
        <td>This is a button which automatically queries the Loan and Destructive Sampling tables, opening a pop-up window which lists any transactions for this preparation.</td>
        <td></td>
    </tr>
    <tr>
        <th>Specimen Description</th>
        <td>Collection Object</td>
        <td>This is used to record the description on the label of the organism</td>
        <td></td>
    </tr>
    <tr>
        <th>Storage</th>
        <td>Preparation</td>
        <td>This is used to record the storage location of the specimen (e.g. Main Herbarium, Long Store, Spirit Room, Silica Room, Carpological Collection). For lichens which are classified taxonomically under the fungal element, this is used to record the specimens that are physically stored as lichenised fungi. For physically linked specimens (where there is more than one specimen permanently mounted on a sheet), the lowest barcode should be created as a storage location and used to store all the specimens on the sheet. For the spirit collection, this is used to record the running number for each of the specimens.</td>
        <td></td>
    </tr>
    <tr>
        <th>Substrate/Host</th>
        <td>Collecting Event</td>
        <td>This is used to record the substrate or host if the specimen was found growing on another species or substrate e.g. a lichen growing on an Oak branch.</td>
        <td></td>
    </tr>
    <tr>
        <th>Text</th>
        <td>Collection Object Property</td>
        <td>This is used to record additional text relating to the use of the species</td>
        <td></td>
    </tr>
    <tr>
        <th>Transcribed type</th>
        <td>Collecting Event Attribute</td>
        <td>This field is used to record the format of the geographical coordinates, i.e. Decimal Degrees or Degrees Minutes Seconds.</td>
        <td></td>
    </tr>
    <tr>
        <th>Treatment</th>
        <td>Preparation Attribute</td>
        <td>This is used to record any treatment used during the collection or preparation process.</td>
        <td></td>
    </tr>
    <tr>
        <th>Tree Number</th>
        <td>Collection Object Attribute</td>
        <td>This is used to record the tree number from which the specimen was collected</td>
        <td></td>
    </tr>
    <tr>
        <th>Verbatim Collector Name</th>
        <td>Collecting Event</td>
        <td>This has been used to record the free text collector name from BG-BASE. Where this is the case, the name will be prefixed by &quot;From BG-BASE&quot; and the Collector Code.</td>
        <td></td>
    </tr>
    <tr>
        <th>Verbatim locality</th>
        <td>Collecting Event</td>
        <td>This is used to record any locality information not included in the Locality field above. When entering data a decision will need to be made about division of locality and habitat in some cases.</td>
        <td></td>
    </tr>
    <tr>
        <th>Wild Data</th>
        <td>Collection Object</td>
        <td>This is used to record the wild collecting event information if there are insufficient data to create a separate Collection Object record</td>
    </tr>
</table>




<!--- Use this website to create the html version https://tableconvert.com/excel-to-html -->


<!--- <tfoot>
 <tr>
 <td style="font-weight:400;text-align:left" colspan="3" >
 Note:	Test note.
 </td>
  </tr>
 </tfoot>
 -->
