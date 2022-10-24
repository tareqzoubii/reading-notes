## Read 11

## what is matplotlib ?

#### Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. Matplotlib makes easy things easy and hard things possible

# --------------

## How do I run matplotlib in Python?

#### To use matplotlib, we need to install it.
#### Step 1 − Make sure Python and pip is preinstalled on your system. Type the following commands in the command prompt to check is python and pip is installed on your system. ...
#### Step 2 − Install Matplotlib. ...
#### Step 3 − Check if it is installed successfully.

# ---------------

## What are types of matplotlib in Python?

#### Matplotlib Plot Types
#### Line Plot.
#### Bar Plot.
#### Scatter Plot.
#### Pie Plot.
#### Area Plot.
#### Histogram Plot.

# ----------------

## What is Bokeh?

#### Bokeh is an interactive visualization library that targets modern web browsers for presentation.

# ----------------

## What can I do with Bokeh?

#### Plot a complex chart with interactive hover in a few lines of code
> from bokeh.models import ColumnDataSource, HoverTool
>from bokeh.plotting import figure
> from bokeh.sampledata.autompg import autompg_clean as df
> from bokeh.transform import factor_cmap

> df.cyl = df.cyl.astype(str)
> df.yr = df.yr.astype(str)

> group = df.groupby(by=['cyl', 'mfr'])
> source = ColumnDataSource(group)

>p = figure(plot_width=800, plot_height=300, title="Mean MPG by # Cylinders and Manufacturer",
>          x_range=group, toolbar_location=None, tools="")

> p.xgrid.grid_line_color = None
> p.xaxis.axis_label = "Manufacturer grouped by # Cylinders"
> p.xaxis.major_label_orientation = 1.2

> index_cmap = factor_cmap('cyl_mfr', palette=['#2b83ba', '#abdda4', '#ffffbf', '#fdae61', > '#d7191c'], 
>                         factors=sorted(df.cyl.unique()), end=1)

> p.vbar(x='cyl_mfr', top='mpg_mean', width=1, source=source,
>       line_color="white", fill_color=index_cmap, 
>       hover_line_color="darkgrey", hover_fill_color=index_cmap)

> p.add_tools(HoverTool(tooltips=[("MPG", "@mpg_mean"), ("Cyl, Mfr", "@cyl_mfr")]))

> show(p)

#### Create and deploy interactive data applications

> from IPython.display import IFrame
> IFrame('https://demo.bokeh.org/sliders', width=900, height=500)