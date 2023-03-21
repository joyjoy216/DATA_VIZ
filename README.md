# PROJECT BY JOY AKINYI(NYC TAXI DATASET 2022 JANUARY)
## Introduction
A Project that uses Bokeh for visualisations and draws insights from them.This is a prerequisite to join the Outreachy internship program
> This dataset was downloaded from the following link https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page.   
I performed two types of analysis,one that is geographical under the [BOKEH_VIZ](./BOKEH_VIZ.ipynb) file and another one that is statistical.The latter can be found under the file named [BOKEH_TAXIS](./BOKEH_TAXIS.ipynb).The plots for the statistical analysis are located at [plots_Viz](./plots_Viz) while those of the geographical analysis is located at [plots_Taxi](./plots_Taxi)
## SUMMARY OF FINDINGS
From the [BOKEH_TAXIS](./BOKEH_TAXIS.ipynb) file i concluded the following:

1. Most people have favorite pickup and drop off locations hence there are some ID's that are ever busy
2. Vendor ID 1 is way more active than ID 2,they have quite a large gap in terms of the number of trips
3. From the payment name column i created,there seems to be a specific payment method most people prefer.It is associated with the payment type of 2



From the [BOKEH_VIZ](./BOKEH_VIZ.ipynb) file i had the following findings:
 1. Effects of oversampling

Visual clutter: Overplotting can make a plot appear visually cluttered, making it difficult to read and interpret. This can also lead to user fatigue and make it harder to discern patterns and trends in the data.

Bias in analysis: Overplotting can also lead to biased analysis, particularly if certain regions of the plot are more densely populated than others. This can result in overemphasis on certain areas of the data and underemphasis on others, leading to skewed conclusions.

2. Effects of Undersampling

Overgeneralization: Undersampling can also result in overgeneralization, particularly if the subset is not representative of the population as a whole. This can result in inaccurate models that do not capture the true complexity of the data


 **Using Alpha**
 
 - Alpha refers to the level of transparency or opacity of graphical elements, such as points or lines, used to represent data. Alpha is typically represented by a       numerical value between 0 and 1, where 0 is completely transparent (invisible) and 1 is completely opaque.

> The above effects can be solved by using alpha as it improves data visibility by reducing overplotting and allowing users to see the individual data points more clearly. This can help users identify patterns and trends in the data that may have been obscured by overplotting.

> Using alpha also enhances effective communication since it helps in the communication of data by making it easier for users to understand the data being presented. This can help users better communicate their findings to others and improve the overall effectiveness of data-driven decision-making.

