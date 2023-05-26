# Factorio Base Import Guide

Follow the following steps to export your factorio base and view it in FUE5.


### Step 1. Install the FUE5 Exporter Mod
![image](https://github.com/Inrixia/FUE5/assets/6373693/6b85ddc3-c32c-4ab8-9048-428f4dc17e1e)

### Step 2. Use the FUE5 Exporter to export a selection of your base.
You can use this in the map view if you want to export a large section of your base!

![image](https://github.com/Inrixia/FUE5/assets/6373693/30052d5c-49db-49d0-89d2-655f53a16129)
![image](https://github.com/Inrixia/FUE5/assets/6373693/14832964-4845-4d3a-b8ed-267bdf480998)

Once you make a selection you should see the text "Export Done" in the bottom left of your Factorio screen.

### Step 3. Copy the exported selection into the FUE5 Unreal Project
Your exported selection will exporter to a JSON file named `exported-entities.json` located in `script-output` of Factorio.
You can find this in `%APPDATA%/Factorio/script-output`

If you are on windowss you can get to this folder by pressing WIN+R and then entering in the path like so:

![image](https://github.com/Inrixia/FUE5/assets/6373693/d2f63201-ae29-4b9f-a4ea-c0352df528b8)

You can now copy the `exported-entities.json` into the FUE5 Unreal Project.

![image](https://github.com/Inrixia/FUE5/assets/6373693/b66ef0bc-0220-46b9-8cbd-4c590ab9ddc4)

Copy the `exported-entities.json` file from `%APPDATA%/Factorio/script-output` to `FUE5\Content\MyStuff\BLUEPRINTS\base-spawner`

The resulting folder should look something like this:

![image](https://github.com/Inrixia/FUE5/assets/6373693/bf3a75c3-4ca0-494b-849d-897cfe7d1695)

### Step 4. Load the exported section in FUE5
Open the FUE5 project in the Unreal Engine and click on `base-spawner` in the Outliner on the top right of the window.
Two checkboxes `Local-json` and `Net Load on Client` need to be checked to load your base. By default `Local-json` is unchecked, tick both boxes.

![image](https://github.com/Inrixia/FUE5/assets/6373693/6a47abef-0947-4ace-a213-6a695a5ceaaf)

After the box is checked your selection should be imported and be visible in the world somewhere. See the screenshot below for an example.

You may need to look around to find where the section imported.

![image](https://github.com/Inrixia/FUE5/assets/6373693/287bbe4f-9166-4c37-8a78-5f7d00d76965)



### Step 5. Profit?
You are done!
![image](https://github.com/Inrixia/FUE5/assets/6373693/7ac5d36d-dc9b-41b9-b718-29c6e0bda34d)
