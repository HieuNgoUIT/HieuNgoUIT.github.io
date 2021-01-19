## join 2 tables
1. joined = df1.set_index('column_name').join(df2.set_index('column_name'))
2. joined = pd.merge(df1, df2, how = 'left', on ='item_id')

## groupby
df.groupby(['column_name']).max()   (mean, average,...)
=> Groupby then select on another column : df.groupby('column_name')['another_name'].max().reset_index(name = 'total_revenue')

=> return column 1 based on max column 2: result = df['column1'].iloc[df['column2'].idxmax()]