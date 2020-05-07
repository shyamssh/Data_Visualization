# Layered Grammar for plots

[https://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf](https://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf)

# Anatomy of matplotlib

- plots
- subplots
- axis
- labels

# Introduction of Seaborn

# Univariate Analysis

Analyzing one data attribute or variable and its distribution 

- Visualizing continuous data attribute
    - Histograms
- Visualizing a discrete, categorical data attribute
    - bar plots (stacked bars or multiple bars for more dimensions)

    ```sql
    [0.1, 0.2 ,0.4 , ..., 0.9 ] => histogram/density => on y, count 

    [1,2,3,4,5,10] => barchart => on y , count 

    {"key1": ["A","B","C"] } => barchart => on y, count 

    {
    "key1": ["A","B","C"],
    "key2": ["A","A","B"]
    }

    ```

 

# Multivariate Analysis

We analyze multiple data dimensions or attributes. data attribute can be continuous or categorical

### Visualizing data in Three Dimensions (3-D)

- Potential relationships or correlations amongst the different data attributes
    - Pair-wise correlation matrix and depict it as a heatmap.
    - pair-wise scatter plots
- Visualize two continuous, numeric attributes
    - Scatter plots
    - Joint plots / KDE Plot using Seaborn
- Visualizing two discrete, categorical attributes
    - Create separate plots (subplots) or facets for one of the categorical dimensions
    - stacked bars or multiple bars for the different attributes
- Visualizing mixed attributes in two-dimensions
    - One way is to use faceting\subplots along with generic histograms or density plots.
    - Overlapped histogram
    Leveraging multiple histograms for mixed attributes in two-dimensions in one plot
    - box plots
    - violin plots

- **Other plots**
    - Stack Plot and Stem Plot [https://towardsdatascience.com/data-visualization-using-matplotlib-16f1aae5ce70](https://towardsdatascience.com/data-visualization-using-matplotlib-16f1aae5ce70)
    [https://github.com/BadreeshShetty/Data-Visualization-using-Matplotlib](https://github.com/BadreeshShetty/Data-Visualization-using-Matplotlib)
