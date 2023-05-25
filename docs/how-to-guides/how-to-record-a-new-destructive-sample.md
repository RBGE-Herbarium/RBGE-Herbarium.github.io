---
parent: How-to guides
---

# How to record a new destructive sample

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

When sampling a Herbarium specimen or silica-dried sample, you will need to create a new Preparation for the new sample.

### How to create a new Preparation for an existing Collection Object

Search for the existing Collection Object using a [Query](https://rbge-herbarium.github.io/docs/queries/collection-object-queries.html).

_Tip: The [Collection Objects by country or collector Query](https://herb-rbge.specifycloud.org/specify/query/8/) may be helpful._

If the Collection Object already exists, open the record and click **Edit** at the bottom right of the Collection Object form. If it does not exist then you will need to create a new Collection Object record. See instructions in [How to enter specimen data](https://rbge-herbarium.github.io/docs/how-to-guides/how-to-enter-specimen-data.html).

To add a preparation to a record click on **+** next to Preparations

![image](https://user-images.githubusercontent.com/8005676/180241183-0d51c889-dcbb-409e-9ded-73e8ca5a1551.png)

The following information should be entered for a destructive sample record:

- **Prep Type** - select Destructive Sample
- **Barcode** - enter the destructive sample item number. This is constructed using the Destructive Sampling request number followed by a running number for each sample, separated by a colon (eg, 03306:2). The combination must be unique.
- **Remarks** - enter any remarks specific to the Preparation, not the Collection Object, here.
- **Internal Misc** – use this field for any internal curatorial information which is not to be shared.

### How to enter Destructive Sampling information

This section should only be completed for preparations created during destructive sampling.

- **Material type** - enter the type of material sample (e.g. Flower sample, Leaf sample, Pollen sample).
- **Derived from** - this is for preparations made for Destructive Sampling ONLY. Enter the barcode of the specimen from which the sample was taken.
- **Prepared By** – enter the person who prepared the sample.
-- _Tip: type in the last name and, if the person is already in the Agents table, their name should come up as one of the options in a list._
- **Prepared Date** – enter the date that the destructive sample was created.
- **Sample Number** – do not enter data here. This has been used for the destructive sample collector number migrated from BG-BASE. 
- **Legacy Number** – this is a read-only field for the BG-BASE specimen number.

For more information on entering data into the Preparation record see the **[Instructions](https://rbge-herbarium.github.io/docs/data-entry/collection-object-form.html#preparations-subform)** for entering a new **Preparation**

Enter any specific **Determinations** relating to this Preparation if required.

If the remaining information is the same as for the other preparations in the Collection Object record, then click **Save** and close the record.
