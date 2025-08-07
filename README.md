# ML-Heart-Desease
Рассматривался датасет, представляющий собой информацию о пациентах клиники.<br> 
Цель - научиться предсказывать наличие болезни сердца в зависимости от 11 показателей, используя алгоритмы классического ML <br/>
Данные датасета:
1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]
<br/>
Были рассмотрены различные модели: <br/>
1. Логистическая регрессия
2. Метод опорных векторов (SVC)
3. Дерево решений
4. Случайный лес
5. Метод k ближайших соседей (k=3)
   
<br/>
Лучше всего себя показали логистическая регрессия, метод опорных векторов и случайный лес. Была достигнута точность 90% по метрике accuracy.
