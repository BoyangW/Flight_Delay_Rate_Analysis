### Flight Delay Rate Machine Learning Part
<p>Website: https://boywei.georgetown.domains/Flight_Delay_Analysis/machine_learning.html</p>

<H4>Dataset</H4>
<ul>
  <li>data_1.csv, data_2.csv, data_3.csv
    <ul>
      <li>Input data for weather_match_clean.py</li>
    </ul>
  </li>
  <li>weather.csv
    <ul>
      <li>Stores the dataframe of weather data linked to the flights' information</li>
      <li>Input data for weather_match_clean.py</li>
    </ul>
  </li>
  <li>cleaned_data.csv
    <ul>
      <li>Output data from weather_match_clean.py/li>
      <li>Cleaned data for Machine Learning</li>
    </ul>
  </li>
</ul>

<H4>Python Code</H4>
<ul>
  <li>weather_match_clean.py
    <ul>
      <li>Input data_1.csv, data_2.csv, data_3.csv, and weather.csv</li>
      <li>Concatenate three flight data files and match corresponding weather data</li>
	    <li>Further clean for missing and incorrect values are performed in this file and outputs cleaned_data.csv</li>
    </ul>
  </li>
  <li>machine_learning_binaryclass.py
    <ul>
      <li>Input cleaned_data.csv</li>
      <li>Create binary delay type data. Using different classifiers to predict departure or arrival delay. There is an option to choose whether to include weather data or not</li>
      <li>Logistic regression, and Recursive Feature Elemination is implmented. k-folds cross-validation during traning, accuracy socre, confusion matrices, testing report, and ROC curves are generated</li>
    </ul>
  </li>
  <li>machine_learning_multiclass.py
    <ul>
      <li>Input cleaned_data.csv</li>
      <li>Create multi-type delay level data. Using different classifiers to predict departure or arrival delay level. There is an option to choose whether to include weather data or not</li>
      <li>K-folds cross-validation during traning, accuracy socre, confusion matrices, testing report, and multi-type class ROC curves are generated</li>
    </ul>
  </li>
</ul>
