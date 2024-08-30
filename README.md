# Olympic Medals

## 1. About

<div align="center">
  <img src="assets/olympics.png" alt="Olympics logo"/>
</div>
<br>
<p align="justify">Olympic Medals is a Data Science authorial project, using Python and its libraries NumPy, Matplotlib and Pandas. The focus of this project is to analyze the number of medals won by each country in the Olympics 2024 based on the difference between the rank position of each country and their medals. For example, there are some countries that won more medals than others, but they are positioned below because the number of gold medals won by them was lesser than the others.</p>
  
<p align="justify">The dataset used on this project was taken from Kaggle. You can access its source by clicking on <a href="https://www.kaggle.com/datasets/berkayalan/paris-2024-olympics-medals/data" target="_blank" rel="noopener noreferrer">Olympic medals dataset</a>. Next you can see the author's analyzes and charts about the Olympic Medals topic organized in NumPy and Matplotlib and Pandas.</p>

## 2. NumPy and Matplotlib Analysis

<p align="justify">To analyze the Olympic Medals dataset first the medals were organized in gold, silver, bronze and total medals. After that, the mean, median and standard deviation of each part of the dataset were calculated. Then, bar and pie charts were made to demonstrate and visualize the distribution of data.</p>

### 2.1 Mean

<p align="justify">Next it’s possible to see the mean of each kind of medal (gold, silver and bronze) and even the total medals:</p>

<ul>
  <li>Gold: 3.6</li>
  <li>Silver: 3.6</li>
  <li>Bronze: 4.2</li>
  <li>Total medals: 11.4</li>
</ul>

<p align="justify">Looking at the means it’s possible to see that the gold and silver means were lower than the bronze mean. The number of countries that attended the Olympics 2024 and won at least one medal was eighty-four (84), so this can indicate that the sum of the bronze medals was bigger than the gold and silver medals.</p>

<p align="justify">The mean of the total medals was considerably lower than the total medals of the first place (USA) that won one hundred and twenty-six (126) medals and the second place (China) that won ninety-one (91) medals and was more than eleven times bigger than the total medals won by the last place (Zambia) that won one (1) medal. And because of that in this case the mean may not be a trust indicative.</p>

### 2.2 Median

<p align="justify">Next it’s possible to see the median of each kind of medal (gold, silver and bronze) and even the total medals:</p>

<ul>
  <li>Gold: 1.0</li>
  <li>Silver: 1.0</li>
  <li>Bronze: 2.0</li>
  <li>Total medals: 5.0</li>
</ul>

<p align="justify">Looking at the medians it’s possible to see that the gold and silver medals reached the same value and were lower than bronze value. The median of bronze medals were two times bigger than the median of gold and silver medals, and this can indicate that the number of bronze medals won individually by most countries was bigger than the gold and silver medals.</p>

<p align="justify">The median of the total medals won was more than two times bigger than the bronze medals and five times bigger than the gold and silver medals, and it was bigger than the sum of the median of the gold, silver and bronze medals. This can testify that every country in the dataset won at least one medal, but there were some countries that didn’t win any gold, silver or bronze medal. For example, the nineteenth place (Ireland) didn’t win any silver medal, but it won four (4) gold medals and three (3) bronze medals.</p>
