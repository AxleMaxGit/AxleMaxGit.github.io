# Pandas Cheat Sheet

## Get Max of two columns  
[link](https://stackoverflow.com/questions/12169170/how-should-i-take-the-max-of-2-columns-in-a-dataframe-and-make-it-another-column)


df[["A", "B"]].max(axis=1)

'>>> df  
'  **A  B**  
0  1  -2  
1  2  8  
2  3  1  

'>>> df[["A", "B"]].max(axis=1)  
0    1  
1    8  
2    3  
