# Obesity Level Prediction

## Task
Develop a machine learning model to predict a person's obesity level based on various personal and lifestyle details.

## Dataset
- **Files**:
  - `train.csv`: Training set with details and obesity levels.
  - `test.csv`: Test set with details but without obesity levels.
  - `sample_submission.csv`: Sample file showing the correct submission format.

- **Columns**:
  - `id`: Identifier for each sample.
  - `uid`: Unique identifier for each sample.
  - `Location`: Area of person's residence.
  - `Gender`: Self-explanatory.
  - `Age`: Self-explanatory.
  - `Height`: Self-explanatory.
  - `Weight`: Self-explanatory.
  - `SMOKE`: Whether a person smokes (boolean).
  - `Water`: Person's water intake levels.
  - `Hash`: Unknown field.
  - `FHO`: Family history of obesity.
  - `CHCF`: Consumption of high caloric value food.
  - `CV`: Consumption of vegetables.
  - `NCP`: Number of main meals.
  - `CBC`: Consumption of beverages with caloric value.
  - `CAEC`: Consumption of food between meals.
  - `CA`: Consumption of alcohol.
  - `FAF`: Physical activity frequency.
  - `TI`: Time spent on the internet.
  - `Mode`: Person's mode of transport.
  - `Obesity_level`: Target value (only in the training set).

## Submission
Make predictions on the test dataset and submit a CSV file containing the `Obesity_Level` predictions mapped against the identifiers (`ID`). Check `sample_submission.csv` for the correct format.
