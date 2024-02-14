# Trade-Pro-Manager
![image](https://github.com/irakli182/Trade-Pro-Manager/assets/112957853/04cd466f-1696-4b30-8209-48af72c938dc)

### 💻 Installation Steps 
- Download from [Releases](https://github.com/irakli182/Trade-Pro-Manager/releases)
- Extract the zip file (using WinRAR) 
- Configure the settings in the config.ini file with reference to the configFormat.ini file 
- Open File
- Select the start menu
- Run
- Finish

# 1. What time frame is best to use?
Time frames determine the frequency with which prices are plotted on the chart and can range from 1 second to 1 month. We can notice that price charts tend to be similar to each other from one time frame to another, having the same irregular aspects and the same patterns, which explains the fractal nature of market prices, where shorter term fluctuations make up the longer term fluctuations found on the higher time frame.
![image](https://github.com/irakli182/Trade-Pro-Manager/assets/112957853/18fe6801-5ff2-4772-8a8b-aa1d26dde500)
# 2. Best settings for technical indicators
![image](https://github.com/irakli182/Trade-Pro-Manager/assets/112957853/98cf3be3-7736-491c-9641-5155e8d032f4)
When using technical indicators that reduce scourge transactions, decision-making time often deteriorates, therefore, finding settings that minimize scourge transactions while maintaining an acceptable amount of delay is not an easy task.

Most technical indicators have user-defined settings, they can be numeric, alphabetic or Boolean and allow traders to change the output of the indicator. In general, the basic setting of the technical indicator allows you to make decisions about long-term price fluctuations, so traders should use the indicator settings to catch the fluctuations they are interested in, as is done when choosing a timeframe, however, the settings of technical indicators often allow a greater degree of manipulation and may have a wider range of values, so the choice of settings is often carried out differently.

# 2.2 Indicator settings from optimization

When using technical indicators to create entry rules, the settings that bring the most profit are usually selected. There are various methods to achieve optimization, some programs use brute force, testing the strategy for each indicator setting. More advanced procedures such as genetic algorithms (GA) can also be used.

GA is beyond the scope of this article, but, simply put, GA is a search algorithm that simulates natural selection and is especially suitable for solving multiparametric optimization problems. When using GA, the tuning is carried out as genes in a chromosome.

This selection method has some limitations, the most obvious of which is that the optimal settings may change over time, which makes the optimization process useless. Optimization can also take a long time when working with a large data set or when using a large combination of indicator settings, so it would be more interesting to analyze the optimized settings of the technical indicator over time and try to find a connection with market prices.

# 2.3 The period of the dominant cycle for selecting settings

Some technical analysts have hypothesized that the dominant cycle period should be used as a setting for technical indicators instead of a fixed value, this method can often be seen in technical indicators by J. Most technical indicators that use the dominant period as a setting are bandpass filters that preserve frequencies close to the dominant period.

This method of choice has several limitations, firstly, it strongly depends on the accuracy and speed of the algorithm used to determine the dominant period of the cycle, the noisy nature of the price makes it extremely difficult to accurately and timely measure the dominant period, in general, more accurate methods will have a greater delay as a result. Another disadvantage is that this is not a universal solution, technical indicators can handle the market price in different ways.

# 3. Conclusion
Of the two questions highlighted at the beginning of this note, the question of technical indicators remains the most difficult to answer, which often happens with questions like "what is better ...". Undoubtedly, there is no universal setting for each indicator, some settings may be more adapted to specific market conditions (for example, range or trend), and the presence of a setting in itself always means that interaction will occur at some point, so the recommendation of setting an indicator or timeframe should be carefully justified.
