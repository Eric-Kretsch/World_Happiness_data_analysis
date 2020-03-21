First completed exercize from the Data Analytics discord: https://discord.gg/CWXdT3

Context
This dataset is obtained from Kaggle. I have modified the data to contain only data from 2015 to 2017. This report ranks 155 countries by their happiness level through 6 indicators:

economic production
social support
life expectancy
freedom
absence of corruption
generosity
The last indicator is dystopia residual. Dystopia residual is "the Dystopia Happiness Score(1.85) + the Residual value or the unexplained value for each country". Dystopia is a made up country that has the world's least happiest people. This made up country is high in corruption, low in average income, employment, etc. Dystopia residual is used as a benchmark and should be used side-by-side with the happiness score.

Low dystopia residual = low level of happiness
high dystopia residual = high level of happiness.
Understanding the column data
Country
Happiness rank
Happiness score
This is obtained from a sample of population. The survey-taker asked the respondent to rate their happiness from 1 to 10.
Economic (GDP per cap)
Extend of GDP that contributes to the happiness score
Family
To what extend does family contribute to the happiness score
Health
Extend of health (life expectancy) contribute to the happiness score
Freedom
Extend of freedom that contribute to happiness. The freedom here represents the freedom of speech, freedom to pursue what we want, etc
Trust (Government corruption)
Extend of trust with regards to government corruption that contribute to happiness score
Generosity
Extend of generosity that contribute to happiness score
dystopia residual
Year
Do note:
HappinessScore=Economic(GDPpercap)+Family+Health+Freedom+Trust+Generosity+DystopiaResidual
