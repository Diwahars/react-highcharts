# React HighCharts

Render HighCharts with React.js using JSON data.  This is a basic, working template of a bar chart with React that anyone can pull and start working on.

![alt text](https://github.com/jasonganub/react-highcharts/blob/master/screenshots/HighChartsScreenshot.PNG "Screenshot of a HighCharts example")

## Examples

```javascript
var chartInstance = new Highcharts.Chart(chartOptions);
this.setState({
  chartInstance: chartInstance
});
```

```javascript
var chart = React.render(
  React.createElement(Chart, {
    seriesModel: seriesObject,
    chartModel: chartObject}),
  document.getElementById('example')
);
```

```javascript
var seriesObject = [{
      name: 'Year 1800',
      data: [107, 31, 635, 203, 2]
  }, {
      name: 'Year 1900',
      data: [133, 156, 947, 408, 6]
  }, {
      name: 'Year 2008',
      data: [973, 914, 4054, 732, 34]
}];
```

## Installation

Download the full directory as a zip to use it as a template.

## Usage

The JSON data is modifiable within src/chart.js folder under the seriesObject array.

If you want to use the JSX file, src/chart.js
If you want to use the JavaScript file, build/chart.js

Note: build/chart.js is the JavaScript file that was transformed from the JSX file, src/chart.js.  If you are going to work with the JSX file, be sure to use "jsx --watch src/ build/" from the main directory.  This will convert any JSX files in the src directory to JavaScript files in the build directory.

## History

1.0.0 Initial release

## Credits

With the help of Justin Woo's Mori implementation https://github.com/justinwoo/highcharts-mori-test

## License

React is BSD licensed.
Highcharts is free for a personal or non-profit project under the Creative Commons Attribution-NonCommercial 3.0 License.
