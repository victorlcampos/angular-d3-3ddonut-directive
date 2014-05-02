# Directive for D3 3D Donuts Sample (http://bl.ocks.org/NPashaP/9994181)

## How to use:
```js
<!-- Controller -->
$scope.data = [
    {label:"Basic", color:"#3366CC", value:1000*Math.random()},
    {label:"Plus" , color:"#DC3912", value:1000*Math.random()},
    {label:"Lite" , color:"#FF9900", value:1000*Math.random()},
    {label:"Elite", color:"#109618", value:1000*Math.random()},
    {label:"Delux", color:"#990099", value:1000*Math.random()}
  ];

<!-- View -->
<div dttt-ddd-donut ng-model="data"></div>
```

## TODO
Think in the better way to use Donut3D.transition