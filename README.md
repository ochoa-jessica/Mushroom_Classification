# Mushroom Classification EDA using Plotly 
<p>mainly using .go charts</p>

## Motivation
<p>To get hands-on experience using Plotly to visualize multi-diemnsional categorical data.</p>

## Data Source
<p>The dataset was published as a [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom)</p>

## Data Content
<p>The dataset includes hypothetical samples corresponding to 23 species of gilled mushrooms in he Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one.</p>

## Data Preprocessing 
<p>For readability purpose I renamed one of column names from <i>class</i> to <i>is-edible</i> and replaced default observations with human-readable equivalents.</p>

## One-Dimensional Plot
<p>The pie chart is constructed using <i>population</i> feature.</p>
![Mushroom Population Pie Chart](Images/newplot.png)
<p>Mushrooms are classified by the kind of populations they habituate in. The above pie chart represents the proportion of mushrooms in each population. Most of the mushrooms live in groups of several, while less than 15% of the mushrooms live in groups that can be described as numerous, abundant, or clustered. Approximately one-third of the mushrooms contained in this dataset occur either solitarily or scattered.</p>
