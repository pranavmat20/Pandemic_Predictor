![image](https://user-images.githubusercontent.com/82716880/228934319-f7d6d1a8-7648-4504-9a62-f79f42ecf225.png)
# Pandemic_Predictor

Initially, we have gathered information about the numerous viruses, such as monkey pox, covid, zika, etc., from keggle and weka.
After that, we took data from four other countries—Russia, India, China, and the USA—and removed the columns for death and state.

Adding a new column called the rate of growth = (final-initial/initial)*100 from the current data

Using Seaborn, we have plotted the rate growth vs. date graph.

After that, we utilise an ARIMA model to forecast the growth of some well-known viruses for the following 30 days before using the Intel One api's Scikit Learn module to determine squared errors.

The mean squared error was easy to find using the Intel One api.
