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


## Collection Object 

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
  <tr>    
   <td>Accession Number
   </td>
   <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer. 
   </td>
   <td> Examples to be added
   </td>
  </tr>
</table>

### Preparation 

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
   <td
   </td>
  </tr>
  <tr>    
   <td>Label status
   </td>
   <td>This is used to indicate the level of transcription carried out from the specimen labels. The options are Minimal, Partial, Complete or Unknown.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Sheet Num. 
   </td>
   <td>This is used to record the number of the sheet when it is part of a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the sheet number should be recorded here, the total number in the set should be recorded separately.
   </td>
   <td
   </td>
  </tr>
  <tr>    
   <td>Num. in Set
   </td>
   <td>This is used to record the total number of sheets when there is a set of sheets for a single specimen. It can be common for some large plants or plants with complex morphology for each duplicate to comprise separate sheets for the flower, root, leaves, fruit, stem, etc. Only the total number in the set should be recorded here, the individual sheet numbers should be recorded separately.
   </td>
   <td
   </td>
  </tr>
  <tr>    
   <td>Storage
   </td>
   <td>This is used to record the storage location of the specimen (e.g. Main Herbarium, Long Store, Spirit Room, Silica Room, Carpological Collection). For lichens which are classified taxonomically under the fungal element, this is used to record the specimens that are physically stored as lichenised fungi. For physically linked specimens (where there is more than one specimen permanently mounted on a sheet), the lowest barcode should be created as a storage location and used to store all the specimens on the sheet. For the spirit collection, this is used to record the running number for each of the specimens.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Physically Linked
   </td>
   <td>This is a read-only field used for data migrated from BG-BASE. Do not enter data into this field.
   </td>
   <td
   </td>
  </tr>
  <tr>    
   <td>Donor
   </td>
   <td>This is used to record the name of the Institute/collection that directly donated the specimen to RBGE. (e.g. Glasgow, Herb of John Ball). More guidance will be provided on the use of this field. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Herbarium Collection
   </td>
   <td>This is used to record the name of the Herbarium Collection (e.g. Herb. Greville, Herb. Wight, Herb. Wallich, Herb. Drege) where the herbarium collection differs from the donor and collector. Some of the Herbarium Collections will have been donated from a third party, such as Kew, Glasgow, etc. In these cases the Donor will be Kew and the Herbarium Collection should be entered here. More guidance will be provided on the use of this field.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Collection Series
   </td>
   <td>More guidance to be provided on the use of this field.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Project
   </td>
   <td>This is used to record a project for the preparation. If applicable select the project from the dropdown list. At present it is only possible to select a single project so this field should be used with caution.
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Label Header
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Label Footer
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Remarks
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
  <tr>
   <td>Internal Misc
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
</table>

### Preparation Attribute

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
   <td>
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
</table>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td
   </td>
  </tr>
</table>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td
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
