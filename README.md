# Acoustic-Extinguisher---Flame-extinction-classification

The dataset was obtained as a result of the extinguishing tests of four different fuel flames with a sound wave extinguishing system. The sound wave fire-extinguishing system consists of 4 subwoofers with a total power of 4,000 Watt placed in the collimator cabinet. There are two amplifiers that enable the sound come to these subwoofers as boosted. Power supply that powers the system and filter circuit ensuring that the sound frequencies are properly transmitted to the system is located within the control unit. While computer is used as frequency source, anemometer was used to measure the airflow resulted from sound waves during the extinguishing phase of the flame, and a decibel meter to measure the sound intensity. An infrared thermometer was used to measure the temperature of the flame and the fuel can, and a camera is installed to detect the extinction time of the flame. A total of 17,442 tests were conducted with this experimental setup. The experiments are planned as follows:

1. Three different liquid fuels and LPG fuel were used to create the flame.

2. 5 different sizes of liquid fuel cans are used to achieve different size of flames.

3. Half and full gas adjustment is used for LPG fuel.

4. While carrying out each experiment, the fuel container, at 10 cm distance, was moved forward up to 190 cm by increasing the distance by 10 cm each time.

5. Along with the fuel container, anemometer and decibel meter were moved forward in the same dimensions.

6. Fire extinguishing experiments was conducted with 54 different frequency sound waves at each distance and flame size.

Throughout the flame extinguishing experiments, the data obtained from each measurement device was recorded and a dataset was created. The dataset includes the features of fuel container size representing the flame size, fuel type, frequency, decibel, distance, airflow and flame extinction. Accordingly, 6 input features and 1 output feature will be used in models. The explanation of a total of seven features for liquid fuels in the dataset is given in Table 1, and the explanation of 7 features for LPG fuel is given in Table 2.
The status property (flame extinction or non-extinction states) can be predicted by using six features in the dataset. Status and fuel features are categorical, while other features are numerical. 8,759 of the 17,442 test results are the non-extinguishing state of the flame. 8,683 of them are the extinction state of the flame. According to these numbers, it can be said that the class distribution of the dataset is almost equal."
