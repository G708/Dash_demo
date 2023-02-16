# Dash_demo
Test of hosting Dash in github pages.


`html.Div` is components of the Dashboard `layout`. `layout` are organized as hierarchical tree of components.

`dash.dcc` is module of interactive components, like input box, download button, etc. Dropdown or Multi-Select Dropdown seems work for selecting genes from Datasets.

Reference components: https://dash.plotly.com/dash-core-components


`@app.callback` is a callback function which reacts user action to the components.
This function is how interactively works. 

Dash run in localhost. 

```
python app.py
```
