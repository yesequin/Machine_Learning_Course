# MACHINE LEARNING

https://www.youtube.com/watch?v=JcI5Vnw0b2c&list=PLQVvvaa0QuDfKTOs3Keq_kaG2P55YRn5v&index=2

ML = Machine Learning

Data science is the field of exploring, manipulating, and analyzing data, and using data to answer questions or make recommendations.

Data science can help organizations:

- Understand their enviroments
- Analyze existing issues
- Reveal previously hidden opportunities

Many organizations will use data science to focus on an specific problem, and so it’s essential to 

## REGRESSION

```bash
pip install sklearn
pip install quandl
pip install pandas
```

The idea with regression is to take continuous data and figure out a best fit line to that data. We are trying to “model” our data.

For Simple linear regression is just a straight line, so basically the whole point of regression is to find out what “m” and “b” is

$$
Y = mX+b
$$

With machine learning, specially with supervised ML, everything boils down to features and labels.

- Features: Attributes, or in this case, the continuous data. You want to have meaningful features, so you should simplify your data as much as possible.  The features are kinda of the attributes that make up the label.
- Label: some sort of prediction into the future.

### Steps

1. Create the DataFrame
2. Grab some features. Here is where we simplify the data as much as possible (choose only the columns we want for the model). There might be some worthless columns, but they do have some relationships, and this is very valuable.
3. Define (if necessary) some special relationships between columns.
4. Define the Forecast column
5. Forecast out. This is a regression algorithm. Generally you use regressions to forecast out. You don’t have to, but generally that’s what you are doing.
6. Create the label.

I am mariflower