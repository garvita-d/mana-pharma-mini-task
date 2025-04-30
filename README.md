# mana-pharma-mini-task
In the code I have completed an assignment for applying as an AI/ML Intern at Mana Pharma, Hyderabad. 
So my first step was to load the datset through pandas from the link for dataset given by the company and kept time constraint to get the data within a period of time. Furhter I wanted to see what dataset contains, hence i did so.
Next, I wanted to know if its loaded successfully or not hence by importing requestI did so as the code depicts further if there an error with the network then an error message should be displayed so that i could improve network environment, hence i did so at the end of the 1st cell. 
Then in the next cell i inspected the data by using dataframes simply which gave me column names and datatypes. The comes the data preprocessing steps like checking for any missing values in any of the columns , for which i got no missing values in the dataset. 
Then I also checked for any duplicate values and i got none.

The last step was to visualize minimum 2 property trends like molecular weight vs xlogp and xlogp vs compound name. Using matplot library of python for graph plotting i visually represented both of it and named properly. 

The first graph shows for 5 chemical compounds if there is a correlation between molecular weight and xlogp. For instance, the compound ID 2244 with the most xlogp value suggesting more fat-soluble (lipophilicity) with moderate molecular weight out of the 5 compounds where as compound id with 5957 has the lowest xlogp values indicating more water soluble(hydrophilicity) and highest molecular weight.

Similarly, other graph portrays relation between checmical compounds which are in SMILES representation and xlogp. For example, The corner compound at rightside has lowest xlogp values meaning most negative value and compound prefers polar environment and the first three compounds have xlogp values >0 meaning they are positive values they prepfer nonpolar environment.
