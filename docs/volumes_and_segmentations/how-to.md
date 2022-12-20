# How to

## Accessing Mol\*VS
Mol\*VS is free and open to all users. There is no login requirement for accessing the following Mol\*VS resources.

**[Mol\*VS landing page](https://molstarvolseg.ncbr.muni.cz/)**, a hub for all Mol\*VS resources, including a few interesting examples, documentation, and, most importantly, access to [Mol\* Viewer with the Mol\*VS extension](https://molstar.org/viewer/), which you will use to visualize the entries of the Mol\*VS internal database.

**[Mol\*VS documentation](http://molstar.org/viewer-docs/volumes_and_segmentations/overview/)**, which is integrated with the Mol\* documentation.

**[Mol\*VS development page on GitHub](https://github.com/molstar/molstar-volseg)**, where you can get the source code and raw documentation, as well as follow the development. 

Mol\*VS is an open-source project with a permissive MIT license, which means that you can use the source code to host Mol\*VS locally, derive your own solution built on top of Mol\*VS, incorporate Mol\*VS in your pipelines, all free of charge and with no login requirement. 

If you would like to contribute to the development of the Mol\*VS project by submitting issues, writing code, or preparing documentation, you will need a GitHub account.

![landing_page](how_to/landing_page.png)

## Accessing database entries

All entries in the Mol\*VS internal database are accessible via Mol\* Viewer with the Mol\*VS extension, available free of charge and without login requirement at https://molstar.org/viewer/.

The Mol\*VS extension can be accessed in the **Home tab** of the **Main Menu**. Pick the source database and the entry and click **Apply**.
![loading_entries](how_to/loading_entries.png)

Check the Log Panel at the bottom of the page for the loading progress and any errors. Most entries will load in no more than a few seconds.
![loaded_entry](how_to/loaded_entry.png)

Once the data have loaded, you can manipulate the objects in the 3D scene, examine annotations, and load related macromolecular data. We will go over typical scenarios below, but you can always check the Mol\* Viewer documentation for extensive explanations about all graphical elements and how to get the best out of the visuals.

If the **State Tree** does not show any 3D representation, you can wait a bit or create it yourself.
![general](how_to/general.png)

If you encounter other trouble rendering, please try changing one or more settings as described in the [Known issues section](http://molstar.org/viewer-docs/volumes_and_segmentations/known-issues/). 

## Typical scenarios

Here are a few examples of how cross-scale microscopy data can be explored using Mol\*VS. If you are not familiar with Mol\* Viewer, it will take you a bit of time to get your brearings, and we hope that these examples will help you on your journey.

**From volumes to atoms**
(EMD-1014) with 3D models in the PDB
[Access a pre-made visualization state for emd-1014](https://molstar.org/viewer/?snapshot-url=https%3A%2F%2Fmolstarvolseg.ncbr.muni.cz%2Fsnapshots%2Femd-1014.molj&snapshot-url-type=molj&prefer-webgl1=1)

**Exploring very large data sets from tissue microscopy**
(EMPIAR-10070) clear annotations. Very responsive once loaded
[Access a pre-made visualization state for empiar-10070](https://molstar.org/viewer/?snapshot-url=https%3A%2F%2Fmolstarvolseg.ncbr.muni.cz%2Fsnapshots%2Fempiar-10070.molj&snapshot-url-type=molj&prefer-webgl1=1)

**Comparing segmentation outcomes produced by different approaches**
Manually in IMOD (EMD-9094001) versus default settings in Segger (EMD-9094002)
[Access a pre-made visualization state for emd-9094 with different segmentations](https://molstar.org/viewer/?snapshot-url=https%3A%2F%2Fmolstarvolseg.ncbr.muni.cz%2Fsnapshots%2Femd-9094.molj&snapshot-url-type=molj&prefer-webgl1=1)

**Large data set from light microscopy** 
(IDR-6001240)
[Access a pre-made visualization state for idr-6001240](https://molstar.org/viewer/?snapshot-url=https%3A%2F%2Fmolstarvolseg.ncbr.muni.cz%2Fsnapshots%2Fidr-6001240.molj&snapshot-url-type=molj&prefer-webgl1=1)
