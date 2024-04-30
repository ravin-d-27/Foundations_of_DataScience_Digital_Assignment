# AQI Forecasting using LSTMs

## Overview
This project focuses on analyzing Air Quality Index (AQI) data to understand the average AQI levels for each state in the US. The project involves data loading, preprocessing, calculation of average AQI levels, building LSTM model and visualization of the results.

## Files
- `AQI_Forecasting.ipynb`: Jupyter Notebook containing the Python code for data analysis and visualization.
- `README.md`: This file, providing an overview of the project and instructions.

## Dependencies
- pandas
- matplotlib
- seaborn
- numpy
- tensorflow
  

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/ravin-d-27/Foundations_of_DataScience_Digital_Assignment.git
   cd Foundations_of_DataScience_Digital_Assignment
   ```

2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib seaborn numpy tensorflow
   ```

3. Dataset Link: Since the Dataset is huge, I am attaching the link. Please download it if it is required.
   - Google Drive Link: https://drive.google.com/file/d/1ymUwmE23yFpx1a5fvjg7jnQfxremiT-2/view?usp=sharing

4. Run the Jupyter Notebook `AQI_Forecasting.ipynb` to execute the code and generate the bar plot of average AQI levels for each state.

## Code Structure
- Data Loading and Preprocessing
- Calculation of Average AQI Levels by State
- Visualization (Bar Plot of Average AQI Levels)
- Data Normalization
- Data Splitting
- Model Building
- Training and Testing
- Visualizing the predictions

## Results
The graph generated from the LSTM model displays the actual and predicted AQI levels, and it is capable of capturing the trend for each time line for US.

![image](https://github.com/ravin-d-27/Foundations_of_DataScience_Digital_Assignment/assets/94217598/fa07f55b-ce6f-4943-8cc5-965fc3f8e04a)


## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Note
This project is implemented for my University Course Assignment - "Foundations of Data Science".

You can customize this Readme.md file by replacing placeholders like `your-username`, updating dependencies, adding more details about the analysis steps, and including any additional information relevant to your project.
