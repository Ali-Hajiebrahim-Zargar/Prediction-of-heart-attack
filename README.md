# Heart Attack Prediction

This project aims to predict the likelihood of a heart attack based on medical information provided for an individual. The dataset containing the necessary information is stored in the `heart.csv` file.

## Features

1. **Age (Age):** Age of the individual.
2. **Sex (Sex):** Gender of the individual (1 for male, 0 for female).
3. **Exercise-induced chest pain (exang):** 
   - 1: Yes, chest pain starts with a particular activity.
   - 0: No, chest pain does not start with a particular activity.

4. **Number of major vessels (ca):** 
   - Range from 0 to 3.

5. **Chest pain type (cp):** 
   - 1: Typical angina (direct heart pain).
   - 2: Atypical angina (indirect heart pain).
   - 3: Non-anginal pain.
   - 4: Asymptomatic (without symptoms).

6. **Resting blood pressure (trtbps):** 
   - Blood pressure while at rest.

7. **Cholesterol level (chol):** 
   - Blood cholesterol level.

8. **Fasting blood sugar (fbs):** 
   - 1: High fasting blood sugar (indicating diabetes).
   - 0: Normal fasting blood sugar.

9. **Resting electrocardiographic results (rest_ecg):** 
   - 0: Normal.
   - 1: Abnormality in the ST-T wave.
   - 2: Probable or definite left ventricular hypertrophy.

10. **Maximum heart rate achieved (thalach):** 
    - Maximum heart rate during exercise.

11. **Heart attack chance (target):** 
    - 0: Low chance of a heart attack.
    - 1: High chance of a heart attack.

## How to Use

1. Ensure you have the required dependencies installed. You can install them using:

   ```bash
   pip install -r requirements.txt

 
