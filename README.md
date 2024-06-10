# Sales Forecasting with Machine Learning

This project focuses on developing a machine learning model to forecast quarterly sales for a steel manufacturer's customers. By leveraging customer-specific attributes, financial ratios, and economic indicators, the goal is to accurately predict sales and support data-driven decision-making.

## Dataset

The project utilizes the following datasets:

- `train.csv`: Training dataset containing historical sales data and customer information.
- `test.csv`: Test dataset for evaluating the model's performance on unseen data.
- `EconomicIndicators.csv`: Dataset containing relevant economic indicators for the corresponding time periods.

## Project Structure

The repository is structured as follows:

- `sales_forecasting.py`: Main script that orchestrates the entire sales forecasting pipeline.

## Dependencies

The project requires the following dependencies:

- Python (version 3.6 or higher)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using the following command:

pip install pandas numpy matplotlib seaborn scikit-learn

## Usage

To run the sales forecasting pipeline, execute the following command:

python sales_forecasting.py

The script will perform the following steps:

1. Load and preprocess the datasets.
2. Conduct exploratory data analysis and visualize the data.
3. Perform feature engineering to create relevant features.
4. Train and evaluate the Random Forest Regressor model.
5. Generate sales predictions for the test dataset.
6. Save the predictions to a CSV file named `submission_for_kaggle_forecasting.csv`.

## Results

The model's performance is evaluated using the Mean Absolute Error (MAE) metric. The validation MAE achieved by the Random Forest Regressor model is reported in the console output.

The final predictions for the test dataset are saved in the `submission_for_forecasting.csv` file.

## Future Enhancements

Some potential areas for future improvement include:

- Experimenting with other machine learning algorithms or ensemble methods.
- Incorporating additional external data sources to enhance the model's predictive power.
- Performing more extensive hyperparameter tuning to optimize the model's performance.
- Developing a web application or dashboard to visualize the sales forecasts.

## Contact

If you have any questions, suggestions, or feedback, please feel free to contact the project maintainer at [krutikadhananjaydeshpande@gmail.com](mailto:krutikadhananjaydeshpande@gmail.com).
