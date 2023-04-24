---
parent: specify-at-rbge
---

# Carry Forward

Carry Forward allows data in selected fields to be copied between new records. The fields that are carried forward between records are defined by the user and can be adjusted depending on the task. 

## To Enable and configure Carry Forward

To enable Carry Forward for a Data entry form click on the cog ![image](https://user-images.githubusercontent.com/8155743/234029614-4b3ca9be-7f38-43d6-9880-ba423baee7d6.png) at the top right of the screen. This opens the Form Meta screen for the page:

![image](https://user-images.githubusercontent.com/8155743/234030501-e7170570-6a35-4eba-824a-b2249e64600d.png)

To enable the Carry Forward button select the tick box for showing Carry Forward. To configure which fields are included when the Carry Forward button is selected click on the cog next to Show Carry Forward button:

![image](https://user-images.githubusercontent.com/8155743/234031104-131d3a0f-524b-41c7-86b9-f4daef0e8a63.png)

This opens up the 'Configure fields to carry forward (Table Name) screen. The first time you open this screen a large number of fields will be selected:

![image](https://user-images.githubusercontent.com/8155743/234031587-c1420da5-27a2-42b3-bfed-e6326e666c8f.png)

It is strongly advised that all fields are **deselected** before configuring carry forward for the first time. 

The screen that is initially opened relates to the table you started in e.g. if you are in the Collection Object table, the configuration will be for the Collection Object table. To configure any sub tables e.g. Preparations you will need to click on the cog next to that table in the Relationships section. This opens up another 'Configure fields to carry forward (Table Name) screen. It is again strongly advised that all fields are **deselected** before configuring carry forward.

To select a field to carry forward click on the field name, selected fields will have an orange tick to the left of field name.

![image](https://user-images.githubusercontent.com/8155743/234042154-b0a7e21b-6511-4c16-9c16-f41151b80fc0.png)

To ensure that values from a sub table are included in Carry Forward the sub table needs to be selected. 
![image](https://user-images.githubusercontent.com/8155743/234042271-2f37d7f7-96e6-4be4-b793-4c1bd10c9c95.png)

Once all fields have been selected for a particular table, click close at the bottom right, the settings are automatically saved. Once you have completed configuration for all tables click close on the Form Meta screen. 

You should now see a button for carry forward at the bottom right of the data entry screen.

![image](https://user-images.githubusercontent.com/8155743/234039432-bad49a5d-03b1-4c84-846b-9c982d24d676.png)

## Using Carry Forward

Once you have configured carry forward you will be able to start using it. After saving a record where you want to Carry Forward the data  for your selected fields, click on the Carry Forward button. This will create a new record with the selected fields already filled in with the **same** data as the previous record.

## Guidlines for using Carry Forward

- The Carry Forward button will only copy data for fields that have been selected in the configuration screens. 
- When selecting fields be aware of which ones will be the same between records and which will be unique. Only set Carry Forward for the values that will be the same between records.
- Before using Carry Forward for a new task check which fields are selected
