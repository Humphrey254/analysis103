Dataset

The dataset used in this project is train.csv, which contains information about houses, including features like:

    LotArea: Lot size in square feet.

    OverallQual: Overall material and finish quality.

    YearBuilt: Original construction year.

    TotalBsmtSF: Total square feet of the basement area.

    GrLivArea: Above-grade (ground) living area square feet.

    SalePrice: The target variable, representing the sale price of the house.



Requirements

To run this project, you need the following Python libraries:

    pandas

    numpy

    matplotlib

    seaborn

    scikit-learn


    The script will:

        Load and inspect the dataset.

        Prepare the data.

        Visualize relationships between features and the target variable.

        Train and evaluate the model.

        Make predictions on new data.

Results

The model's performance is evaluated using:

    Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.

    R² Score: Indicates the proportion of variance in the target variable that is predictable from the features.

Example output:

Mean Squared Error: 12345678.90
R^2 Score: 0.85
Predicted SalePrice: 250000.00
