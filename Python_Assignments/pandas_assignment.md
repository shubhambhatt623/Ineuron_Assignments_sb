# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?

    By using pd.read_csv("location_of_the_file.csv")

Q2. How do you check the data type of a column in a Pandas DataFrame?

    df.dtypes()

Q3. How do you select rows from a Pandas DataFrame based on a condition?

    df[df['col_name'] == "condition"]

Q4. How do you rename columns in a Pandas DataFrame?

    df.rename(columns = {'test_rename':'new_column'}, inplace = True)

Q5. How do you drop columns in a Pandas DataFrame?

    df.drop(['Col_name'],axis=1)

Q6. How do you find the unique values in a column of a Pandas DataFrame?

    df.unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?

    df.isna()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?

    df.fillna()

Q9. How do you concatenate two Pandas DataFrames?

    pd.concat([df_1,df_2])

Q10. How do you merge two Pandas DataFrames on a specific column?

    pd.merge(df_1,df_2,on=column_name)

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?

    df.groupby(['list of columns'])['col to display].sum()

Q12. How do you pivot a Pandas DataFrame?

    df_pivot = pd.pivot_table(df, values = 'D', index = ['A', 'B'],
                    columns = ['C'], aggfunc = np.sum)

Q13. How do you change the data type of a column in a Pandas DataFrame?

    df.astype(np.int)

Q14. How do you sort a Pandas DataFrame by a specific column?

    df.sort_values(by=['Country'])

Q15. How do you create a copy of a Pandas DataFrame?

    df_copy =  df.copy()

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

    df[(df.col > 100) & (df.col < 10000)]

Q17. How do you calculate the mean of a column in a Pandas DataFrame?

    df.co_name.mean()

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?

    df_col.std()

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?

    df.corr()

Q20. How do you select specific columns in a DataFrame using their labels?

    df[['col_1','col_2']]

Q21. How do you select specific rows in a DataFrame using their indexes?

    using loc method .

Q22. How do you sort a DataFrame by a specific column?

    df.sort_values(by=['Country'])

Q23. How do you create a new column in a DataFrame based on the values of another column?

    df.new_col = df.curr_col + 100

Q24. How do you remove duplicates from a DataFrame?

    df.drop_duplicated()

Q25. What is the difference between .loc and .iloc in Pandas?

    The main distinction between the two methods is: loc gets rows (and/or columns) with particular labels. iloc gets rows (and/or columns) at integer locations.
