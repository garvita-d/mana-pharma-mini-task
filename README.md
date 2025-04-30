# mana-pharma-mini-task
In the code I have completed an assignment for applying as an AI/ML Intern at Mana Pharma, Hyderabad. 
So my first step was to load the datset through pandas from the link for dataset given by the company and kept time constraint to get the data within a period of time. Furhter I wanted to see what dataset contains, hence i did so.
Next, I wanted to know if its loaded successfully or not hence by importing requestI did so as the code depicts further if there an error with the network then an error message should be displayed so that i could improve network environment, hence i did so at the end of the 1st cell. 
Then in the next cell i inspected the data by using dataframes simply which gave me column names and datatypes. The comes the data preprocessing steps like checking for any missing values in any of the columns , for which i got no missing values in the dataset. 
Then I also checked for any duplicate values and i got none.

The last step was to visualize at least 2 property trends, like molecular weight vs xlogp and xlogp vs compound name. Using the matplotlib library of Python for graph plotting I visually represented both of them and named them properly. 

The first graph shows if there is a correlation between molecular weight and xlogp for five chemical compounds. For instance, compound ID 2244 has the most xlogp value, suggesting more fat-soluble (lipophilicity) with moderate molecular weight, whereas compound ID 5957 has the lowest xlogp value, indicating more water-soluble (hydrophilicity) and the highest molecular weight.

Similarly, another graph portrays the relationship between chemical compounds, which are in SMILES representation, and xlogp. For example, the corner compound at right side has lowest xlogp values, meaning the most negative value and compound prefers a polar environment and the first three compounds have xlogp values >0, meaning they are positive values they prefer a nonpolar environment.

How can trends in molecular properties help in solvent selection in drug development?
Since we have seen that xlogp is the most important property for finding solubility, its higher or lower value helps us know if a drug is water or polar, or which kind of solvent.
