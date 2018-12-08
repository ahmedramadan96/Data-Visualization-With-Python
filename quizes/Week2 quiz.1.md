# Basic Visualization Tools quiz(1) :
 
1. Area plots are stacked by default..

    - Ans: True.

2. The following code uses the artist layer to create a stacked area plot of the data in the        pandas dataframe, area_df. ```
        import matplotlib.pyplot as plt
        series_df.plot(kind='area', figsize=(20, 10))
        plt.title('Plot Title')
        plt.ylabel('Vertical Axis Label')
        plt.xlabel('Horizontal Axis Label') 
        plt.show()```

    - Ans: False.


3. Which of the following codes will create an unstacked area plot of the data in the pandas dataframe, area_df, with a transparency value of 0.35?.

    - Ans: The last snip shot of code
        *               
                         transparency = 0.35
                         ax = area_df.plot(kind='area', alpha=transparency, stacked=False,  figsize=(20, 10))
                         ax.title('Plot Title')
                         ax.ylabel('Vertical Axis Label')
                         ax.xlabel('Horizontal Axis Label')


4. Given a pandas series, series_data, which of the following will create a histogram of            series_data and align the bin edges with the horizontal tick marks?.

    - Ans: The second snipshot of code.
        *                            count, bin_edges = np.histogram(series_data)
                                       series_data.plot(kind='hist', xticks = bin_edges) 

5. Given a pandas dataframe, question, which of the following will create a horizontal bar chart    of the data in question?.

    - Ans: the third snipshot of code
        *                             question.plot(kind='barh') .