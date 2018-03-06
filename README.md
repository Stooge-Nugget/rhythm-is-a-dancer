# Webpack Base Project

My webpack boilder plate for new projects.


### Output

dist  
|- bundle.js  
|- index.html


### Devtool

inline-source-map:  
Map compiled code back to original source, for easier debugging.


## Webpack Plugins

### HtmlWebpackPlugin

HTML file generation to serve webpack bundles  
*Can be generated using template.*

[Reference](https://webpack.js.org/guides/output-management/#setting-up-htmlwebpackplugin)  
[Github](https://github.com/jantimon/html-webpack-plugin)


### CleanWebpackPlugin

Removes/Cleans build folder ready for the next build

[Reference](https://webpack.js.org/guides/output-management/#cleaning-up-the-dist-folder)  
[Github](https://github.com/johnagan/clean-webpack-plugin)