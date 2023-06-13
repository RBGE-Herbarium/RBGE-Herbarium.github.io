---
parent: How-to guides
---

# How to manage a Destructive Sampling request

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

This workflow will take you through recording a basic destructive sampling request where the sampling will be undertaken in-house. The workflow will involve the following basic steps:

1.	Create the Destructive Sampling Request record 
2.	Record receipt of a signed CBD form 
3.	Record the assessment of the Destructive Sampling Request
4.	Create a Record Set for all specimens requested
5.	Add the Destructive Samples to the Destructive Sample Request record
7.	Add the additional information to the Destructive Sampling Request record
8.	Record notification that the samples have been received

## Step 1: Create the Destructive Sampling Request record

With the destructive sampling request at hand, open Specify 7 to create a new destructive sampling request record.

Click on Interactions and select Destructive Sampling from the menu at the top.

The next step is a workaround, and will be improved in time:
Destructive sampling records can only be created with a specimen being selected on the next screen.  However, assuming you haven’t yet selected any specimens to sample, the below workaround allows you to create a blank record:
Enter a catalog number - all catalog numbers are eight digits  (any valid number but 00000001 may be easiest to remember).  Click ok.

![image](https://user-images.githubusercontent.com/8005676/180242115-914103a8-187e-4163-a054-4f5857b99906.png)

On the next screen, **do not tick any preparations**, and then click **Apply**.  This will ensure that no preparations are added to the Destructive Sampling request at this stage: 

![image](https://user-images.githubusercontent.com/8005676/180242175-bb10f324-6aba-44f4-9d44-5f931dcf03d4.png)

This will open the **Destructive Sampling** form with a Destructive Sampling record where you can enter the information about the request. 
- At this point in time, you may not have all the information to be entered.
- This record can be saved at any time and completed at a later time. Click Save at the bottom right of the screen.
- The **Destructive Sampling Request Number** will be automatically allocated when the record is saved. Take a note of this to find the record more quickly later.

![image](https://github.com/RBGE-Herbarium/RBGE-Herbarium.github.io/assets/6713716/c35a82f4-dc7c-48fc-b584-48a89788f55e)


**Status**: Select the current status from the dropdown menu (Complete, Denied, Pending)
![image](https://github.com/RBGE-Herbarium/RBGE-Herbarium.github.io/assets/6713716/93ed0620-fa33-4535-91b6-997dec263530)

- **Purpose**: Select a value from a dropdown menu. Only select one of the following options. If you need a different value, please ask.
  - molecular research (DNA, gene sequencing, etc.)
  - anatomical research
  - phytochemical research
  - general research (when not molecular, anatomical or phytochemical)
  - teaching
  - illustration
- **Description**: Enter a short summary of the intended research, and a general taxonomic or geographic summary.
- **Loan Num**: Enter the associated Loan number if the request originated from a Loan Request or if it triggers a Loan Request.
- **Their Num**: Enter the other institute’s reference number, if known.
- **Legacy Number**: This is read only, do not enter data.
- **Remarks**: Enter any additional information or notes relating to the destructive sampling request. Any information relating to any particular samples should be entered into the Preparation record. This field may be used as part of the report to be sent to the Requester.
- **Internal Misc**: This can be used to help with the management process of the request and notes in here do not have to be retained. This would not be included in any report to the Requester.

- **Destructive Sampling Agents**: Enter the following information if known:
  - Herbarium making request: Agent = Herbarium; Role = Herbarium
  - Individual researcher named on request: Agent = individual name; Role = Requester
  - Supervisor if named on request: Agent = individual name; Role = Supervisor
  - Person preparing the samples: Agent = individual name; Role = Preparer
  _Tip – if you want to search by institution code – you can enter in the agent box: %(CODE) – e.g. see screenshot below:_

![image](https://user-images.githubusercontent.com/8005676/180242530-43b21a1b-9991-4641-9d4f-936e19ca944f.png)

- **Date**: The default will be today’s date.
- **Remarks**: In the Remarks field under the Agent you can add any additional information about the agent/role/status relating to this particular request. Enter any more general remarks about the request to the higher level Request Remarks field.

Click **Save**

At this point any documentation can be attached to this record using the Attachment icon.
![image](https://user-images.githubusercontent.com/6713716/178465341-64b5b059-2674-4ca2-a4db-0b733542d204.png)

## Step 2: Record receipt of a signed CBD form

A CBD form should be sent to the requester and signed. The CBD documentation will need to be in place for any further progress to be made with the request.

The request number, internal contact and Herbarium code should be added to any CBD documentation. 

Tick the **CBD Form checkbox** to indicate that the CBD Form has been received.

Click **Save**

Make a note of the Destructive Sampling Number. You can find this number at the top of the form, but only after you have saved the form.

Add the following notes to the completed CBD form:
a.	Destructive Sampling Request number 
b.	Your name as the RBGE internal contact

## Step 3: Assess the Destructive Sampling Request

At this point you will need to assess the request.
- Assess specimens available
- Assess any permit or other restrictions for those specimens
- Approval by appropriate members of staff

If the request is fully or partially approved, then the specimens can be looked out and databased if required.

Record the name of the person who approves or denies the request in the Destructive Sampling record request record in the Agent field. In **Agent Remarks** enter any additional information relating to the agent in the context of the destructive sampling request, including the date and if the request is approved or denied.

![image](https://user-images.githubusercontent.com/6713716/178465754-0cbd1808-7fab-41ef-8e96-dd58022f87a9.png)

If the whole request has been denied select the Denied status in the Status field.

## Step 4: Create a Record Set for all specimens requested

This will make the management of the request and recording information easier.  The record set lets you easily view the records that have been requested in the destructive sampling request.  You can add samples to it, and remove items from it, as the scope of the request is refined.  

First, check whether a Collection Object and Preparation already exists for the each of the requested specimens.

If a specimen has not yet been databased, this should be done at this stage.

Once all requested specimens have been databased, the barcodes can be entered into a Query in Specify.  

_Note: This can be done manually, or using a barcode scanner if you have the specimens to hand._

Click on the queries in the Menu Ribbon

In the popup, click on the Barcode Query (exact name may vary depending on what you saved it as).

Enter the barcodes of the specimens that form part of the request separated by commas e.g. EXXXXXXXX, EXXXXXXXX, EXXXXXXXX to retrieve the Collection Object records for the specimens. Make sure the operator is set to “In”.

The query can be constructed to provide additional information for each record. If the information you want is not visible, then the query can be modified to include it. If you are unsure how to do this, please check the Query guidance or ask for help.

![image](https://user-images.githubusercontent.com/8005676/180243507-d245fb8f-1009-42db-95db-ad3515fd7bda.png)

These can then be saved as a Record Set to help manage the destructive sampling process.  If you did not want to save all the records, you could use the tick boxes on the left to select the records to add to the record set.  by default, all records are included.  

Click “Create Record Set”.

The Destructive Sampling request number can be used to name the Record Set. 

![image](https://user-images.githubusercontent.com/8005676/180243856-50ec2872-df42-4819-9e31-bee681315ade.png)

## Step 5: Carry out the Destructive Sampling if appropriate

Open the record set by clicking on the item in the Record Set menu. This will open all the specimen records in the Collection Object form view. These can be scrolled through using the Next Record buttons at the top of the window. ![image](https://user-images.githubusercontent.com/8005676/180244016-36b66f74-40c7-4a36-a7f7-f3ad054a4bbb.png)

The destructive sampling can then be undertaken if appropriate.

For each specimen that has been sampled, create a new Preparation in the Collection Object, by clicking **+**:

![image](https://user-images.githubusercontent.com/8005676/180244149-8c46d62c-0c9f-415f-a9e5-832d67e15c70.png)

Then fill in the new Preparation as follows:

![image](https://user-images.githubusercontent.com/8005676/180244246-7957337f-33c1-49d8-b448-a4ed3897af4b.png)

- **Preparation Type**: Select Destructive Sample
- **Barcode**: Enter the sample identifier which is currently the Request number + the item number, eg 03213:1, 03213:2, 03213:3, etc).
- **Remarks**: Enter any information relating to the destructive sample here.
- **Internal Misc**: This field may be used to keep a note of the sampling process if desired.


There is a section in the Preparation subform for Destructive Sampling. The following information should now be entered here.
- **Material type**: Select the type of sample from the dropdown menu.
- **Derived From**: Enter the barcode of the specimen from which the material was taken.
- **Prepared by**: Enter the person preparing the sample.
- **Prepared date**: Enter the date the sample was prepared.
- **Sample Number**: Enter the number assigned by the collector for the material being collected to fulfill this request
- **Legacy Number**: a read only field for the Des_Item number from BG-BASE

Once complete, Click Save in the bottom right of the Preparation window. 

You should now see the Preparation for the destructive sample in the list of Preparations in the Collection Object.

It is possible to check the numbering of the samples within the request at any time using the Query tool.

Click on Query on the top menu and Select Preparation from the Create Query menu on the left. If it is not visible, click on More Tables to select it.

Double click on Barcode, select contains as the Operator and enter the Destructive Sampling request number followed by a “:”

![image](https://user-images.githubusercontent.com/6713716/178466716-a67015c3-2da4-4318-8b81-2047d34325f4.png)

This will bring up all the Destructive Sample Preparation records that have been created for this request to date, helping to check for duplicates, missing numbers or where you reached with the sampling process.
 
If the request includes specimens that are not to be sampled then this can be recorded in the following ways:
1.	Specimens denied solely for this request: Record the barcodes of the specimens denied in the Remarks field. If a separate field would be useful for this then a request can be raised.
2.	Specimens denied for any request: Record this information in the Internal Misc field of the specimen Preparation record. If a separate field would be useful for this then a request can be raised.
3.	Specimens denied for any other reason: Consider whether it is appropriate for the information to be recorded against the request or the existing herbarium specimen and use one of the two options above if possible.
4.	Number of specimens denied. If numbers are required for reporting then it could be possible to include a field to record the number of specimens denied within a request.

## Step 6: Add the Destructive Samples to the Destructive Sample Request record

Once all the Destructive Samples have been created, these can be added to the Destructive Sample request record.

This can also be done individually as the sample records are created.

Open the Destructive Sampling Request record.  - Run a query, using the Destructive Sampling Request number, remembering to include any 0s at the start of the number, e.g. 03042.

![image](https://user-images.githubusercontent.com/6713716/178731998-6b0bd24b-9e7e-4075-9d28-a25aa94e76a9.png)

Click on the Result to open the record.

In the Destructive Sampling form, scroll down to the Destructive Sampling Preparations section. Click **+** to add Preparations.

Select "By Choosing a record set", then select the record set you created earlier:

![image](https://user-images.githubusercontent.com/8005676/180244936-b991bb1d-1668-4e0f-ab25-9c9511222f72.png)

You will now see a list of all samples in the Record Set.  This is a list of all preparations of all Collection objects in the list.  Select those that are to be used (this will normally be all the Destructive samples), by ticking the tick boxes, and click apply.

![image](https://user-images.githubusercontent.com/8005676/180245284-d44f9ea5-6bce-4dea-81bc-63bf58d287a1.png)

All the sample preparations will now be attached to the Destructive Sampling request record.

## Step 7: Add the additional information to the Destructive Sampling Request record

Additional information can be entered into the Destructive Sampling Request record.

This information can be entered at any point once the original record is created.


- **Special Conditions**: Enter any restrictions relating to the samples being sent. The Permit number could be included here.
- **Destructive Sample date**: Enter the date the Destructive Sample was sent.
- **Generate Invoice on Save**: This checkbox can be ticked prior to the final save to produce a packing list for sending the samples.

## Step 8: On receiving notification that the samples have been received

Open the Destructive Sampling record and add the following information.

- **Date received**: Enter the date the samples were received by the requesting institution.
- **Received Comments**: Enter the response from the receiving institute here. 

Click **Save**.




