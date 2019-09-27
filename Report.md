# Report

This report contains all steps and specifics of the project, along with important links and parameters.

## Step 1: 

I used the PHPAdmin environment to import the .csv table into the mySQL environment using the Windows PC from alphatraining.

In the PHPAdmin, I clicked in the import data, and got the following command line:

    CREATE TABLE IF NOT EXISTS `CSV_DB`.`TBL_NAME` (
    `id` int(9), 
    `diagnosis` varchar(1), 
    `radius_mean` int(5), 
    `texture_mean` int(5), 
    `perimeter_mean` int(5), 
    `area_mean` int(5), 
    `smoothness_mean` int(7), 
    `compactness_mean` int(7), 
    `concavity_mean` int(9), 
    `concave points_mean` int(8), 
    `symmetry_mean` int(6), 
    `fractal_dimension_mean` int(7), 
    `radius_se` int(6), 
    `texture_se` int(6), 
    `perimeter_se` int(6), 
    `area_se` int(5), 
    `smoothness_se` int(8), 
    `compactness_se` int(8), 
    `concavity_se` int(9), 
    `concave points_se` int(8), 
    `symmetry_se` int(8), 
    `fractal_dimension_se` int(9), 
    `radius_worst` int(5), 
    `texture_worst` int(5), 
    `perimeter_worst` int(5), 
    `area_worst` int(5), 
    `smoothness_worst` int(7), 
    `compactness_worst` int(7), 
    `concavity_worst` int(8), 
    `concave points_worst` int(8), 
    `symmetry_worst` int(6), 
    `fractal_dimension_worst` int(7)
    ) DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;

