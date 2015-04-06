# React HighCharts

Render HighCharts with React.js using JSON data.  This is a basic, working template of a bar chart with React that anyone can pull and start working on.

## Examples

'''
var chartInstance = new Highcharts.Chart(chartOptions);
this.setState({
  chartInstance: chartInstance
});
'''

'''
var chart = React.render(
  React.createElement(Chart, {
    seriesModel: seriesObject,
    chartModel: chartObject}),
  document.getElementById('example')
);
'''

## Installation

Download the full directory as a zip to use it as a template.

## Usage

TODO: Write usage instructions

## History

1.0.0 Initial release

## Credits

With the help of Justin Woo's Mori implementation https://github.com/justinwoo/highcharts-mori-test

## License

React is BSD licensed.
Highcharts is free for a personal or non-profit project under the Creative Commons Attribution-NonCommercial 3.0 License.
