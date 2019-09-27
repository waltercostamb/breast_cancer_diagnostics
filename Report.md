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

INSERT INTO `CSV_DB`.`TBL_NAME` (`id`, `diagnosis`, `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`, `compactness_mean`, `concavity_mean`, `concave points_mean`, `symmetry_mean`, `fractal_dimension_mean`, `radius_se`, `texture_se`, `perimeter_se`, `area_se`, `smoothness_se`, `compactness_se`, `concavity_se`, `concave points_se`, `symmetry_se`, `fractal_dimension_se`, `radius_worst`, `texture_worst`, `perimeter_worst`, `area_worst`, `smoothness_worst`, `compactness_worst`, `concavity_worst`, `concave points_worst`, `symmetry_worst`, `fractal_dimension_worst`) 
VALUES 
(842302, 'M', 17.99, 10.38, 122.8, 1001, 0.1184, 0.2776, 0.3001, 0.1471, 0.2419, 0.07871, 1.095, 0.9053, 8.589, 153.4, 0.006399, 0.04904, 0.05373, 0.01587, 0.03003, 0.006193, 25.38, 17.33, 184.6, 2019, 0.1622, 0.6656, 0.7119, 0.2654, 0.4601, 0.1189),
...
 (92751, 'B', 7.76, 24.54, 47.92, 181, 0.05263, 0.04362, 0, 0, 0.1587, 0.05884, 0.3857, 1.428, 2.548, 19.15, 0.007189, 0.00466, 0, 0, 0.02676, 0.002783, 9.456, 30.37, 59.16, 268.6, 0.08996, 0.06444, 0, 0, 0.2871, 0.07039);

