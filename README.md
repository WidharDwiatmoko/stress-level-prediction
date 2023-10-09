<h2 align="center"> Stress Level Prediction Web Application</h2>

### Project Overview
This project includes the analysis of sleep health and lifestyle dataset and an application for predicting stress levels using machine learning.

### Project Objectives
The main objectives of the project are to analyze the data related to health, lifestyle, and demographic factors, and predict stress levels of individuals using machine learning techniques.

### Project Features
- Sleep health metrics analysis: Explore factors related to sleep duration, quality, and regularity.
- Lifestyle factors analysis: Investigate physical activity levels, stress levels, and BMI categories.
- Cardiovascular health analysis: Examine blood pressure and resting heart rate measurements.
- Sleep disorder analysis: Determine the presence of sleep disorders such as insomnia and sleep apnea.

<details>
    <summary align="left">
            <b>About the Dataset</b>
    </summary>
    
<div align="left">
The dataset consists of 400 rows and 13 columns, containing various variables related to sleep health and lifestyle. The columns and their descriptions are as follows:

1. Person ID: Unique identifier for each individual.
2. Gender: Gender of the person (Male/Female).
3. Age: Age of the person in years.
4. Occupation: Person's occupation or profession.
5. Sleep Duration (hours): Number of hours slept by the person in a day.
6. Sleep Quality (scale: 1-10): Subjective evaluation of sleep quality on a scale from 1 to 10.
7. Physical Activity Level (minutes/day): Number of minutes spent on daily physical activity.
8. Stress Level (scale: 1-10): Subjective evaluation of stress level on a scale from 1 to 10.
9. BMI Category: BMI category of the person (e.g., Underweight, Normal, Overweight).
10. Blood Pressure (systolic/diastolic): Measurement of blood pressure represented through diastolic over systolic pressure.
11. Resting Heart Rate (bpm): Resting heart rate of the person in beats per minute.
12. Daily Steps: Number of steps taken by the person in a day.
13. Sleep Disorder: Presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).

</details>
</div>

## Getting Started

To get started with this project, you can follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/WidharDwiatmoko/stress-level-prediction.git
   ```
2. Create virtual environment and install dependencies (using conda)
   ```
   conda create --name venv --file requirements.txt
   ```

3. Run streamlit app by using 
`cd streamlit/streamlit run app.py`


5. Streamlit deployment link (TBU)


Feel free to modify the code and experiment with different models and techniques to improve the prediction accuracy.

## Acknowledgments

- The dataset used in this project is obtained from https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data.