### Bar and Column Chart Demo

This demo showcases various configurations of Bar and Column charts using VisuallyJS in an Angular application.

#### How it works

The application imports `VisuallyJsModule` and uses the `vjs-bar-chart` and `vjs-column-chart` components. It renders multiple chart examples by iterating over a list of configurations, demonstrating different data sets and visual settings.

#### Components Used

- `vjs-bar-chart`: Used to display horizontal bar charts.
- `vjs-column-chart`: Used to display vertical column charts.

#### Component Options

Both components accept an `options` property of type `BarChartOptions` or `ColumnChartOptions`. These options control:
- Category and value axes.
- Series data and styling.
- Layout and spacing of bars/columns.

#### Stylesheets

For the VisuallyJS components to render correctly, the following stylesheets must be included in the project (usually in `styles.css`):

```css
@import "@visuallyjs/browser-ui/css/visuallyjs.css";
@import "@visuallyjs/browser-ui-angular/css/visuallyjs-angular.css";
```
