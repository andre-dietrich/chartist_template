# chartist_template
Template for using ChartistJS in LiaScript for visualization
<!--

author:   André Dietrich
email:    andre.dietrich@ovgu.de
version:  1.0.0
language: de_DE
narrator: Deutsch Female

script: https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

@Chartist
<div class="ct-chart ct-golden-section" id="chart@0" width="@1"></div>
<script>
// Initialize a Line chart in the container with the ID chart1
new Chartist.Line('#chart@0', @2);
</script>
@end

-->

# chartist_template
<link rel="stylesheet" href="//cdn.jsdelivr.net/chartist.js/latest/chartist.min.css">

```JSON
@Chartist(1,300px)
{
  labels: [1, 2, 3, 4, 5, 6],
  series: [[100, 120, 180, 200, 333, 3333, 444, 555]]
}
```
