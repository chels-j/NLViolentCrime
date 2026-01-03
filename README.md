# 🚓 🕵️ Dutch Crime Data: Increasing or decreasing? Diverging trends

This project uses crime data from 2012-2024 collected by [Politie Nederland](https://data.politie.nl/portal.html?_la=nl&_catalog=Politie&tableId=47013NED&_theme=115) and population data from the same period collected by the [Centraal Bureau voor Statistiek (CBS)](https://opendata.cbs.nl/#/CBS/nl/dataset/37230ned/table?ts=1766338546563) to calculate the total and violent crime rates per 1000 people at different geographic levels across the Netherlands.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ihlM24SVloG1rZwnPUF3LygHgoN0qcPQ?usp=sharing)


<i><b>❓This project seeks to answer the following questions:</i></b>
1) Has crime in the Netherlands actually been increasing, as many people seem to believe?
2) Is there a difference in how violent crime rates have changed compared to total crime rates?
3) Which regions have the highest overall and violent crime rates?
4) Which of the major cities have historically had and currently have the highest crime rates?
5) Are there substantial differences in crime rates between two Dutch regions most often in the news for crime: the Randstad and Brabant?

<i><b> 📈 Key Performance Indicators (KPIs), each disaggregated on the national, regional and city level, include:</i></b>
- Total crime rate per 1000 people: total crime includes all crime categories listed in the crime data from Politie Nederland including violent crime, thievery, environmental crime, traffic crime, etc.
- Violent crime rate per 1000 people: violent crime is calculated based on crimes including physical violence (i.e. mugging, robbery, sex crimes, assault, threats, etc.)

<i><b> ✅ The project is organized in the following sections:</i></b>
- Data prep (including importing, inspecting, cleaning, transforming and merging the crime and population data)
- Analysis per question
- Correlation analysis of population vs. crime rates

<i><b> 🔎 Main findings:</i></b>
- The data shows a clear, diverging pattern of a steady and signficiant national decrease in both total and violent crime rates, but many local increases in total crime rate and in some cases also violent crime rate.
- While total and violent crime nationally continue its decreasing trend after the pandemic, for many reigons and cities, the pandemic was an inflection point that sharply changed the decreasing trend to one of increasing total and violent crime rates since 2020.
- On the regional level, Noord Holland, Zuid Holland and Limburg lead the regions in terms of both the total crime rate and violent crime rate per 1000 people. However, Zeeland, Overijssel and Groningen have experienced the largest percentage increases in total crime rate relative to pre-pandemic levels (2019).
- While Utrecht province places 5th overall in terms of total crime rate, it bucks the trend of total crime tracking violent crime by having the lowest violent crime rate of all the provinces.
- Many cities show a similar pattern of following the steady decline in total crime levels seen at the national level up until the pandemic, yet with total crime rates increasing thereafter. Amsterdam, Rotterdam and Eindhoven show both the highest average total crime rates historically and the highest currrent total crime rates as of 2024. However, only Groningen, Rotterdam and Den Haag show total crime rates that surpass their pre-pandemic levels (2019).
- In contrast to the trends for total crime, the trends for violent crime rates in cities show much more variation among them. Although Amsterdam and Rotterdam are also in the top 3 cities for 2024 violent crime rates, Heerlen ties with Rotterdam for first place.
- When comparing major cities in the Randstad v. Brabant, cities in the Randstad show total crime rates significantly higher than Brabant cities, with the exception of Eindhoven, which shows a total crime rate comparable to those seen in the Randstad. In contrast violent crime rates are relatively comparable among Randstad and Brabant cities, with the exception of Utrecht city, which has an exceptionally low violent crime rate both historically and in 2024 compared to other cities.

<b><i> Conclusions: </b></i>
The divergence in national vs. reigonal or local experiences perhaps contributes to the often contradictory picture of the status of Dutch crime portrayed in the media and by politics. While on a macro level it is true that we are overall better off in terms of crime rates than we were before, on the local level, some cities and regions are experiencing very real and worrying increases in crime. This likely contributes to opinions of whether enough is being done about crime diverging strongly based on one's local experience. Clearly, despite the national decreasing trend in crime, certain areas of the country are experiencing a much heavier burden of crime than they did pre-pandemic, and this can have large consequences for the how the perception of crime influences people's consumption of media, their political opinions and their attitudes towards the society in which they live.
