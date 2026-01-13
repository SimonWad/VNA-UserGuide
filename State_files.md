# What is a state file?

> **NOTE:** Please understand that a state-file is not your data, read this section carefully to avoid any accidental file deletion/overwriting.

A state file is the main way to save your digital experimental setup, the filetype extension is `.sta`. Saving one of these files means saving the calibration, the markers you set, the frequency ranges and every other setting that fits your experiment. This way you can avoid having to set up every time you sit down with the VNA.

# Make your own state files

This guide will help you start your project from a premade ground state. As the laws tell us, we must expend energy to move from the ground state.

> It is important to not save over any of the standard files!

For use with the VNA in Network Analyzer mode (NA) a **2-way calibrated SOLT** [**S**hort **O**pen **L**oad **T**hrough] file is available as a starting point.

## 2-way calibrated SOLT start

To recall states, first we must navigate to the folder containing the state files:

&rarr; Press **9: Save/Recall**

&rarr; Press **More** on the screen select buttons

&rarr; Press **Manage Folders** on the screen select buttons

&rarr; Use the scroll disc to highlight the **USER STATES** folder

&rarr; Press **Change Folder** on the screen select buttons (The top should now say `[INTERNAL]:\USER STATES`)

&rarr; Press **🢐Back**

&rarr; Press **Back** on the screen select buttons

&rarr; Press **Recall** on the screen select buttons

&rarr; Navigate to **2-way_SOLT.sta**

&rarr; press **recall** on the screen select buttons.

Then the VNA should load the file and you are ready to format your own state.

> Here the VNA will not save what you change unless you do so manually, shutting down the device will void all changes to you work.

To save your state:

&rarr; Make sure that the VNA is in the `[INTERNAL]:\USER STATES` directory

&rarr; push the **9: Save/Recall** button

&rarr; press **File Type** on the screen select buttons

&rarr; select **state**

&rarr; press **save** on the screen select buttons

&rarr; Add your SDU ID (Please note that it should be whatever is before the @ in your University mail)

> Example user is USER@sdu.dk.
>
> press **save** &rarr; 2026-01-12.15_32_57_USER.sta

&rarr; press **Done** and your file is saved.

When returning to the device you can recall the file to continue from the last save point.
