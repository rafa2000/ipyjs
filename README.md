# ipyjs
## Reproducible data driven documents with IPython and JavaScript
IPython can inject HTML content and Javascript code directly onto a notebook. This, plus the easy production and interchange of JSON data between all components and languates inside the same notebook, allows the use of third party JavaScript libraries &mdash;or any other scripting language&mdash; to enhance the **Reproducible** capabilities of your notebook.

## Used Libraries
* [Dynatable.js](http://www.dynatable.com/) - Dynamic Tables with sorted columns, search and pagination.
* [Highcharts](http://www.highcharts.com/) - Publish quality charts (bar, pie, line, scatter plots, etc.)
* [D3.js](http://d3js.org/) - Free format high quality charts
* [three.js](http://threejs.org/) - Three-dimensional graphs

## Examples
Here are some simple examples to help you mix and match these Javascript libraries with your IPython notebooks:

* **`dynatable_in_ipython`** Dynatable.js and Faker.js inside IPython example.

* **`higcharts_in_ipython`** Highchards.js inside IPython example.

* **`d3_in_ipython`** D3.js inside IPython example.

* **`three_in_ipython`** three.js inside IPython example.

**Note**: You may want to download each notebook, inspect the code, and run it on your computer to actually see the generated charts or dynamic tables. I haven't put an autorun on the JavaScript code yet. If you have some suggestions please clone and make a pull request. I had just the reqular autostart but it worked only for the first graph using it. I need a way to execute in a synchronous way several charts inside the notebooks.
