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
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Catalog Number
   </td>
   <td>Format is 8 digits. An automatically incremental value is allocated by the system. Read only. Be aware that this may not be the same number as the value in the Collection url.
   </td>
   <td>Examples to be added
   </td>
  </tr>
  <tr>    
   <td>Registration Num
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
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Prep type
   </td>
   <td>Select the kind of material (e.g. Herbarium sheet, Carpological) 
   </td>
   <td>Examples to be added
   </td>
  </tr>
  <tr>    
   <td>Barcode
   </td>
   <td>For Herbarium sheets the format is E + 8 digits, which are assigned from the physical barcodes. For Destructive samples the format is the Destructive sampling request number followed by a running number for each sample with no leading 0s.
   </td>
   <td>Examples to be added
   </td>
  </tr>
  <tr>    
   <td>Is on loan
   </td>
   <td>This is an automatically calculated field which pulls information from the Loans table. This is read only. It will be checked if the preparation is currently out on loan. 
   </td>
   <td> Examples to be added
   </td>
  </tr>
  <tr>    
   <td>Show Interactions
   </td>
   <td>This is a button which automatically queries the Loan and Destructive Sampling tables, opening a pop-up window which lists any transactions for this preparation.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Label status
   </td>
   <td>This is used to indicate the level of transcription carried out from the specimen labels. The options are Minimal, Partial, Complete or Unknown.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sheet Num. 
   </td>
   <td>This is used to record the number of the sheet when it is part of a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the sheet number should be recorded here, the total number in the set should be recorded separately.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Num. in Set
   </td>
   <td>This is used to record the total number of sheets when there is a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the total number in the set should be recorded here, the individual sheet numbers should be recorded separately.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Storage
   </td>
   <td>This is used to record the storage location of the specimen (e.g. Main Herbarium, Long Store, Spirit Room, Silica Room, Carpological Collection). For lichens which are classified taxonomically under the fungal element, this is used to record the specimens that are physically stored as lichenised fungi. For physically linked specimens (where there is more than one specimen permanently mounted on a sheet), the lowest barcode should be created as a storage location and used to store all the specimens on the sheet. For the spirit collection, this is used to record the running number for each of the specimens.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Physically Linked
   </td>
   <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Donor
   </td>
   <td>This is used to record the name of the Institute/collection that directly donated the specimen to RBGE. (e.g. Glasgow, Herb of John Ball). More guidance will be provided on the use of this field. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Herbarium Collection
   </td>
   <td>This is used to record the name of the Herbarium Collection (e.g. Herb. Greville, Herb. Wight, Herb. Wallich, Herb. Drege) where the herbarium collection differs from the donor and collector. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew and the Herbarium Collection should be entered here. More guidance will be provided on the use of this field.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Collection Series
   </td>
   <td>More guidance to be provided on the use of this field.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Project
   </td>
   <td>This is used to record a project for the Preparation. If applicable select the project from the dropdown list. At present it is only possible to select a single project so this field should be used with caution.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Label Header
   </td>
   <td>This is used to record the label header. It enables the correct formatting of labels if they are being printed from Specify.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Label Footer
   </td>
   <td>This is used to record the label footer. It enables the correct formatting of labels if they are being printed from Specify.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Remarks
   </td>
   <td>This is used to record any remarks relevant to the individual Preparation. Any information entered here may be visible to the general public. For remarks relevant to the Collection Object as a whole, use the Remarks field below Specimen Description.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Internal Misc
   </td>
   <td>This is used to record any internal information relevant to the individual Preparation. Any information entered here will not be visible to the general public. 
   </td>
   <td>
   </td>
  </tr>
</table>

#### Preparation Attribute section

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>
   <td>Phenology
   </td>
   <td>Please be aware that this subform is not working properly at present and should not be used until the bug is fixed.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Treatment
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Packet Content
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sex
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>

#### Destructive Sampling section

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>
   <td>Material type
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Derived From
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Prepared Date
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>

#### Preparation subform (continued)

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>
   <td>Legacy Number
   </td>
   <td>This has been used to record the Specimen number of the record in BG-BASE. It is read only.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Preparation attachments
   </td>
   <td>This button is used to upload attachments relevant to the individual Preparation. Any attachments relevant to the Collection Object as a whole should be uploaded using the Collection Object attachments button at the foot of the form.
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Counter
   </td>
   <td>This is for Specify management purposes. It is automatically filled and should not be edited.
   </td>
   <td>
   </td>
  </tr>
</table>

### Collecting Event subform

#### Collectors section

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Agent
   </td>
   <td>This field links to the Agent table. The look-up has been formatted to search for the last name. The results have been formatted to include the full name, abbreviation, and dates to help select the correct record. All collectors are held in the Agents table, along with expeditions, organisations and institutes
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Verbatim Collector Name
   </td>
   <td>This has been used to record the free text collector name from BG-BASE. Where this is the case, the name will be prefixed by "From BG-BASE" and the Collector Code.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Collection Date
   </td>
   <td>This is used to record the date on which the Collection Object was collected. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Second Collection Date
   </td>
   <td>This is used to record a second collection date if the Collection Object was collected over a period of time. A qualifier field enables the format of the date to be selected, ie Full date, Month / Year, or Year only.
   </td>
   <td>
   </td>
  </tr>
  <tr>    
   <td>Date as given
   </td>
   <td>This is used to record the date on which the Collection Object was collected if it does not align with a standard date.
   </td>
   <td>Spring, Summer, Autumn, Winter
   </td>
  </tr>
</table>

### Collecting Event subform (continued)

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Accession Number
   </td>
   <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer. 
   </td>
   <td> Examples to be added
   </td>
  </tr>
</table>

#### Cultivated Information subform (Collection Object)

<table>
  <tr>
   <th><strong>Specify field</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Examples</strong>
   </th>
  </tr>
  <tr>    
   <td>Accession Number
   </td>
   <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer. 
   </td>
   <td> Examples to be added
   </td>
  </tr>
</table>



<!--- <tfoot>
 <tr>
 <td style="font-weight:400;text-align:left" colspan="3" >
 Note:	Test note.
 </td>
  </tr>
 </tfoot>
 -->
