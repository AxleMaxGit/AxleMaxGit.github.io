# Pandas Cheat Sheet

## Get Max of two columns

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
