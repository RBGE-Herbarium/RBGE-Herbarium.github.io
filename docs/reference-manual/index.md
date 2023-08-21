---
parent: Reference manual
---

# Specify manual

## Collection Object 

<table>
  <tr>
   <th><strong>Specify caption</strong>
   </th>
   <th><strong>Field Name</strong>
   </th>
   <th><strong>Description</strong>
   </th>
   <th><strong>Field Type</strong>
   </th>
   <th><strong>On Form</strong>
   </th>
   <th><strong>Hidden</strong>
   </th>
   <th><strong>BG-BASE mapping</strong>
   </th>
  </tr>
  <tr>    
   <td>Registration Num
   </td>
   <td>accession
   </td>
   <td>Registration number is the number allocated to a group of specimens as they enter the herbarium collection.
   </td>
   <td>ManyToOne to Collection Object 
   </td>
   <td>On form
   </td>
   <td>Visible
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Agent1 
   </td>
   <td>agent1
   </td>
   <td>to be added
   </td>
   <td>ManyToOne to Collection Object 
   </td>
   <td>to be added
   </td>
   <td>to be added
   </td>
   <td>to be added
   </td>
  </tr>
  <tr>    
   <td>Accession Number
   </td>
   <td>altCatalogNumber
   </td>
   <td>Enter the RBGE accession number (8 figure number starting with a year) of the plant from which this specimen has been made if it comes from the living collections at E. If it has a pre-1968 accession number, please contact the Plant Records Officer. 
   </td>
   <td>String, 64 
   </td>
   <td>On form
   </td>
   <td>Visible
   </td>
   <td>Specimens > acc_num 
Specimens > acc_num_qual 
   </td>
  </tr>
   <tr>    
   <td>Appraisal
   </td>
   <td>appraisal
   </td>
   <td>to be added
   </td>
   <td>ManyToOne to Collection Object
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Location Sensitive
   </td>
   <td>Availability
   </td>
   <td>For specimens of protected species, select how much information should be suppressed in the online catalogue 
   </td>
   <td>String, 32
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>Specimens > location_sensitive 
   </td>
  </tr>
  <tr>    
   <td>Catalog Number
   </td>
   <td>catalogNumber
   </td>
   <td>Automatically allocated by system. Read only.
   </td>
   <td>String, 32 
   </td>
   <td>On form
   </td>
   <td>Visible
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Cataloged Date
   </td>
   <td>catalogedDate
   </td>
   <td>Cataloged Date
   </td>
   <td>Date
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Cataloged Date Precision
   </td>
   <td>catalogedDatePrecision
   </td>
   <td>Cataloged Date Precision
   </td>
   <td>Byte
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>catalogedDateVerbatim
   </td>
   <td>catalogedDateVerbatim
   </td>
   <td>Cataloged Date Verbatim
   </td>
   <td>String, 32
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Cataloger
   </td>
   <td>cataloger
   </td>
   <td>Cataloger
   </td>
   <td>ManyToOne to Collection Object
   </td>
   <td>Not on form
   </td>
   <td>n/a
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Collecting Event
   </td>
   <td>collectingEvent
   </td>
   <td>Collecting Event
   </td>
   <td>ManyToOne to Collection Object
   </td>
   <td>On form
   </td>
   <td>Visible
   </td>
   <td>n/a
   </td>
  </tr>
  <tr>    
   <td>Collection
   </td>
   <td>collection
   </td>
   <td>Collection
   </td>
   <td>ManyToOne to Collection Object 
   </td>
   <td>to be added
   </td>
   <td>to be added
   </td>
   <td>to be added
   </td>
  </tr>
  <tfoot>
   <tr>
    <td style="font-weight:400;text-align:left" colspan="7" >
     Note:	Test note.
    </td>
   </tr>
  <tfoot>
</table>
