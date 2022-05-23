# AP_HW2
A simple repository for the second 2021/22 Asset Pricing home assignment.

*Authors:* Petr Čala, Tereza Čechová, Vilém Krejcar

### How to run:

#### Option 1:
1. Clone the folder into your computer (using `git clone https://github.com/PetrCala/AP_HW2.git`).
2. Into the `data/` folder, add a file called `Asset_pricing_Hw_2_data.RData`, which can be downloaded through Moodle.

#### Option 2:
1. Choose a **master folder** under an arbitrary path. The name of this folder does not matter.
2. In the master folder, create an empty folder and **put the script into a new folder** (this is the file `scripts/HW_2_Cala_Cechova_Krejcar.ipynb`). **Name this new folder `scripts`**. Remember to mind the capitalization.
3. In the master folder, create a subfolder `data/` and **into this folder** put the following files *(all available in Moodle)*:
   1. `61505008_data_download.csv`
   2. `Asset_Pricing_HW_2_data.RData`
   3. `third_factor_rand.csv` 
4. Your master folder should look as follows:

```
|---scripts/
   |  HW2_Cala_Cechova_Krejcar.ipynb
|---data/
   |  61505008_data_download.csv
   |  Asset_Pricing_HW_2_data.RData
   |  third_factor_rand.csv
```

From here on, you should be able to run all cells without any issues. Make sure to keep the working directory in the master folder, as additional files (such as factor data) will be added in to the `data/` folder during running of the script.
