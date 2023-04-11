# Heart Attack 

informações retiradas do kaggle (https://www.kaggle.com/captainozlem/framingham-chd-preprocessed-data)
O objetivo do projeto é estudar modelos de machine learning para classificar ataques de coração.


Dados:

Demográfico:

- Male: 1 ou 0 (Nominal)
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
Educação:

no further information provided

Hábitos:

- Current Smoker: whether or not the patient is a current smoker (Nominal)
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can
have any number of cigarettes, even half a cigarette.)

Histórico médico:

- BP Meds: whether or not the patient was on blood pressure medication (Nominal)
- Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
- Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
- Diabetes: whether or not the patient had diabetes (Nominal)


Condições médicas:

- Tot Chol: total cholesterol level (Continuous)
- Sys BP: systolic blood pressure (Continuous) (pressão arterial)
- Dia BP: diastolic blood pressure (Continuous) (descanso entre as batidas)
- BMI: Body Mass Index
- Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
- Glucose: glucose level (Continuous)

Target variable to predict:

10 year risk of coronary heart disease (CHD) - (binary: “1”, means “Yes”, “0” means “No”)
