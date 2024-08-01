Water Quality Dataset

Source
This dataset was obtained from Kaggle on January 14, 2021. It contains water quality metrics used to predict potability.

Format
The dataset is in CSV (Comma Separated Values) format, containing 3276 rows and 10 columns.

Description
The dataset includes the following variables:

pH: pH level of the water
Hardness: Water hardness
Solids: Total dissolved solids
Chloramines: Chloramine concentration
Sulfate: Sulfate concentration
Conductivity: Electrical conductivity of the water
Organic_carbon: Organic carbon content
Trihalomethanes: Trihalomethane concentration
Turbidity: Water turbidity
Potability: Binary indicator of water potability (0 for not potable, 1 for potable)

Preprocessing
The original dataset contained missing values in the pH, Sulfate, and Trihalomethanes columns. These missing values were removed during the analysis, resulting in a clean dataset of 2011 samples. The Potability variable was converted to a categorical type for modeling purposes.
