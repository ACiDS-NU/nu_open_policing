This demo was inspired by J. Bednar's post "[Python Data Visualization 2018: Moving Toward Convergence](https://www.anaconda.com/blog/developer-blog/python-data-visualization-moving-toward-convergence/)" (accessed 5 Dec 2018) <br>
In it, he states:
## De-facto .plot() API standard
"The pandas plotting API has emerged as a de-facto standard for 2D charts, with a similar set of calls on [Pandas](https://pandas.pydata.org/pandas-docs/stable/visualization.html) dataframes now able to generate plots using Matplotlib (natively in Pandas), Vega-lite (via [pdvega](https://jakevdp.github.io/pdvega/)), Plotly (via [cufflinks](https://plot.ly/ipython-notebooks/cufflinks)), or Bokeh (via [hvPlot](http://hvplot.pyviz.org/)). hvPlot also provides the same plotting API for many other data libraries (xarray, GeoPandas, Dask, Intake, Streamz), making it possible for users in many cases to learn one set of plotting commands using Pandas and then apply them to a wide range of libraries to get either static or interactive plots." <br>
The python environment `dotplot.yml` (and `dotplot_windows.yml` for a windows environment) is meant to enable anyone to test out these libraries on Pandas dataframes (for tabulated data)<br>

To install the environment, execute
```
conda create -f dotplot.yml
```
