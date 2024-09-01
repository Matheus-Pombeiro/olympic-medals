# 1. About

<div align="center">
  <img src="assets/olympics.png" alt="Olympics logo"/>
</div>
<br>
<p align="justify">Olympic Medals is a Data Science authorial project, using Python and its libraries NumPy, Matplotlib and Pandas. The focus of this project is to analyze the number of medals won by each country in the Olympics 2024 based on the difference between the rank position of each country and their medals. For example, there are some countries that won more medals than others, but they are positioned below because the number of gold medals won by them was lesser than the others.</p>
  
<p align="justify">The dataset used on this project was taken from Kaggle. You can access its source by clicking on <a href="https://www.kaggle.com/datasets/berkayalan/paris-2024-olympics-medals/data" target="_blank" rel="noopener noreferrer">Olympic medals dataset</a>. Next you can see the author's analyzes and charts about the Olympic Medals topic organized in NumPy and Matplotlib and Pandas.</p>

# 2. NumPy and Matplotlib Analysis

<p align="justify">To analyze the Olympic Medals dataset using NumPy and Matplotlib first the medals were organized in gold, silver, bronze and total medals. After that, the mean, median and standard deviation of each part of the dataset were calculated. Then, bar and pie charts were made to demonstrate and visualize the distribution of data.</p>

## 2.1 Mean

<p align="justify">Next it’s possible to see the mean of each kind of medal (gold, silver and bronze) and even the total medals:</p>

<ul>
  <li>Gold: 3.6</li>
  <li>Silver: 3.6</li>
  <li>Bronze: 4.2</li>
  <li>Total medals: 11.4</li>
</ul>

<p align="justify">Looking at the means it’s possible to see that the gold and silver means were lower than the bronze mean. The number of countries that attended the Olympics 2024 and won at least one medal was ninety-one (91), so this can indicate that the sum of the bronze medals was bigger than the gold and silver medals.</p>

<p align="justify">The mean of the total medals was considerably lower than the total medals of the first place (USA) that won one hundred and twenty-six (126) medals and the second place (China) that won ninety-one (91) medals and was more than eleven times bigger than the total medals won by the last place (Zambia) that won one (1) medal. And because of that in this case the mean may not be a trust indicative.</p>

## 2.2 Median

<p align="justify">Next it’s possible to see the median of each kind of medal (gold, silver and bronze) and even the total medals:</p>

<ul>
  <li>Gold: 1.0</li>
  <li>Silver: 1.0</li>
  <li>Bronze: 2.0</li>
  <li>Total medals: 5.0</li>
</ul>

<p align="justify">Looking at the medians it’s possible to see that the gold and silver medals reached the same value and were lower than bronze value. The median of bronze medals were two times bigger than the median of gold and silver medals, and this can indicate that the number of bronze medals won individually by most countries was bigger than the gold and silver medals.</p>

<p align="justify">The median of the total medals won was more than two times bigger than the bronze medals and five times bigger than the gold and silver medals, and it was bigger than the sum of the median of the gold, silver and bronze medals. This can testify that every country in the dataset won at least one medal, but there were some countries that didn’t win any gold, silver or bronze medal. For example, the nineteenth place (Ireland) didn’t win any silver medal, but it won four (4) gold medals and three (3) bronze medals.</p>

## 2.3 Standard Deviation

<p align="justify">Next it’s possible to see the standard deviation of each kind of medal (gold, silver and bronze) and even the total medals:</p>

<ul>
  <li>Gold: 7.0</li>
  <li>Silver: 6.7</li>
  <li>Bronze: 6.5</li>
  <li>Total medals: 19.6</li>
</ul>

<p align="justify">Looking at the values of standard deviation it’s possible to realize that the first placed countries won considerably more medals than the last placed. The standard deviation of total medals was high and it can show an inequality of competitive power among the countries.</p>

## 2.4 Charts

<p align="justify">Next it’s possible to see the charts of each kind of medal (gold, silver and bronze) and even the total medals. After each chart there is an analysis about it.</p>

### 2.4.1 Gold Medals Chart

<div align="center">
  <img src="assets/gold-medals-bar.png" alt="Gold medals bar chart"/>
</div>
<br>
<p align="justify">Through the gold medals chart it’s possible to see that most countries didn’t win any gold medal, and there is a decline in the number won by each country. There is a jump from twenty (20) medals won to forty and it’s possible to see that the number of countries that won fifteen (15) medals or more was considerably lower than the other countries.</p>

<p align="justify">This can indicate an inequality of competitive power among the countries again and possibly a lower investment in sports by the governments and maybe by the companies responsible for those countries who won a lower number of gold medals. So, it can be better for companies to invest in athletes that won a bigger number of gold medals, specially those who compete for countries where there is a good sports culture between the population. For example, there are some countries, like Brazil, where soccer receives more attention than other modalities, like winter sports.</p>

### 2.4.2 Silver Medals Chart

<div align="center">
  <img src="assets/silver-medals-bar.png" alt="Silver medals bar chart"/>
</div>
<br>
<p align="justify">Through the silver medals chart it’s possible to see that again the most countries didn’t win any silver medal and up to the mark of ten (10) medals won there is a decline, but after that there is a variation, even that the number of countries that won more than it was below than twenty (20). This variation can testify that the main purpose between the athletes in Olympics is to win a gold medal, but sometimes the difference of preparation between them can be big and some countries, like the USA that won forty-four silver medals, can reach better results.</p>

### 2.4.3 Bronze Medals Chart

<div align="center">
  <img src="assets/bronze-medals-bar.png" alt="Bronze medals bar chart"/>
</div>
<br>
<p align="justify">Through the bronze medals chart it’s possible to see that, differently from the charts of gold and silver medals, most countries won from one (1) to three (3) medals, and the variation was smoother. This variation can indicate that the distribution of medals won among the countries was more egalitarian when talking about bronze medals, which is the lowest prize in an Olympic contest and again testifying the inequality of competitive power among the countries.</p>

### 2.4.4 Total Medals Charts

<div align="center">
  <img src="assets/total-medals-bar.png" alt="Total medals bar chart"/>
</div>
<br>
<p align="justify">Through the bar total medals chart it’s possible to see that every country in the dataset won at least one (1) medal and there is a decline of medals won, which has a kind of variation through the chart. The highest concentration is between one (1) medal and twenty (20) medals won, from this point there is a smaller number of countries.</p>

<div align="center">
  <img src="assets/total-medals-pie.png" alt="Total medals pie chart"/>
</div>
<br>
<p align="justify">Through the pie totals medals chart, that shows the percentage of each kind of medals (gold, silver and bronze) won by the countries in the Olympics 2024, it’s possible to see that thirty-one point six percent (31.6%) of the medals won was gold medals, thirty-one point five percent (31.5%) was silver medals and thirty-seven was bronze medals. This means that there were more athletes that won bronze medals than the other medals.</p>

### 2.4.5 First and Last Place Medals

<p align="justify">Next there is a description and an analysis about the first (USA) and last (Zambia) place performances. Through the dataset it’s possible to see that the USA performance was considerably better than the other countries. It won forty (40) gold medals, forty-four (44) silver medals, forty-two (42) bronze medals and the total medals is one hundred and twenty-six (126) medals.</p>

<div align="center">
  <img src="assets/first-place-pie.png" alt="First place pie chart"/>
</div>
<br>
<p align="justify">Zambia had a not so good performance as the USA. It won just one (1) bronze medal.</p>

<div align="center">
  <img src="assets/last-place-pie.png" alt="Last place pie chart"/>
</div>
<br>
<p align="justify">There is an extreme difference between the performance of these two countries in the Olympics 2024. Why? Probably the USA spent more resources (money in general) on their athletes. Possibly they received more incentive from the USA government, companies and people than Zambia athletes, which must have helped them to get better results. Of course, there might be other variables for this huge difference, but in this case a deeper research should be applied.</p>
