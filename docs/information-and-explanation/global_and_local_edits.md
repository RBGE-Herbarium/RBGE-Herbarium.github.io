---
parent: Information and explanation
title: Global and local edits
---

# Global and local edits

When you edit data in Specify it is helpful to be aware of whether the change will be local or global.

> **Local**: These are edits at that impact an individual collection object and subforms within it

> **Global**: These edits are accessed within an individual collection object but can impact many collection objects 

To know whether a change you are making is acting at a local or global level, it helps to understand a bit about the forms and fields being used.

## Form & Subform

> **Form**: This is the main form where you are carrying out data entry

> **Subform**: This is a form nested within the main form, sometimes be seen as an expanding section

## Fields types

There are five field types in Specify

> **Plain Text**

> **Picklist**

> **Date Format and Date Field**

> **Checkboxes** (often automated in the background)

> **Query combo box** (to be handled with caution!)


## Local Edits

In the example of the Collection Object form, some of the subforms here are seen in the diagram below. Each preparation record for example is actually held in the Preparation table, but can be added and edited within the Collection Object form. The same is true for determinations.

![image](https://user-images.githubusercontent.com/6713716/195291514-ef229875-aa2a-48f4-bca0-9312547bc384.png) 

A determination can be deleted from subform within the Collection Object and it will only really impact this Collection Object record - it's essentially a local edit.

![image](https://user-images.githubusercontent.com/6713716/195292783-c397eb6e-94cf-4e9b-9cc8-fe051c571c99.png)

Similarly, an entire Collection Object can be deleted as a local edit.

![image](https://user-images.githubusercontent.com/6713716/195293061-2b59dc4a-315d-471a-b8cc-12de81e6d9ef.png)

## Global Edits

Some changes, however, may impact more than a local record. These are changes that are made to data that a large number of other records are attached to. These changes can be made in a form or subform, often when in a Query Combo box.

When entering or editing data in a Query Combo box, search and replace a pre-existing value with another one.

> ** Do not edit the value in a Query Combo box.**

A good example of this is the storage location in the Collection Object form. The storage location is used to record where in the building the specimen is stored (_as well as storing the specimen on which physically linked specimens are stored_). In this case, a large number of specimens are explicitly recorded as being stored in the Main Herbarium.

![image](https://user-images.githubusercontent.com/6713716/195838174-f958f575-3f8e-4a23-8b01-d4e4d605ade3.png)

If the correct storage location for this specimen is the Long Store and the Storage Location is edited to reflect this, rather than selecting the correct pre-existing value, the edit will apply to all the specimens currently stored under the Main Herbarium.

![image](https://user-images.githubusercontent.com/6713716/195838326-fe517403-1d14-43ad-80ab-f908b04513b4.png)

The main fields to watch out for in the Collection Object form are shown below.

![image](https://user-images.githubusercontent.com/6713716/195839721-c7ecb188-59ec-4647-86f7-4400ff7180cc.png)





