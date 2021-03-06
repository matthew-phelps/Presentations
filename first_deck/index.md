---
title       : Inferring Drivers of Cholera Transmission from Historical Data
subtitle    : 
author      : Matthew Phelps
job         : PhD Fellow
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: libraries/nvd3}
mode        : selfcontained # {standalone, draft}
---

## Background

### Rational
- Uncertainty of cholera transmission pathways still exists and is difficult to infer with contemporary data
- High quality data from 1853 Copenhagen outbreak can potentially provide information on transmission pathways

### Objectives
- Evaluate the degree to which water-borne transmission routes drove the Copenhagen cholera outbreak of 1853, relative to non-water-borne transmission routes


--- .class #id 

## Reference Map

![alt text](https://raw.githubusercontent.com/matthew-phelps/Presentations/master/CPH%20reference%20map.jpg)


--- .class #id
## 

<div id = 'chart63052c5210f' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart63052c5210f()
    });
    function drawchart63052c5210f(){  
      var opts = {
 "dom": "chart63052c5210f",
"width":    800,
"height":    400,
"x": "day.index",
"y": "cholera.cases",
"type": "lineChart",
"title": "Citywide daily incidence",
"id": "chart63052c5210f" 
},
        data = [
 {
 "month": 6,
"day": 12,
"day.index": 1,
"cholera.cases": 2,
"cholera.deaths": 1 
},
{
 "month": 6,
"day": 13,
"day.index": 2,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 6,
"day": 14,
"day.index": 3,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 6,
"day": 15,
"day.index": 4,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 6,
"day": 16,
"day.index": 5,
"cholera.cases": 1,
"cholera.deaths": 0 
},
{
 "month": 6,
"day": 17,
"day.index": 6,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 6,
"day": 18,
"day.index": 7,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 6,
"day": 19,
"day.index": 8,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 6,
"day": 20,
"day.index": 9,
"cholera.cases": 7,
"cholera.deaths": 4 
},
{
 "month": 6,
"day": 21,
"day.index": 10,
"cholera.cases": 3,
"cholera.deaths": 2 
},
{
 "month": 6,
"day": 22,
"day.index": 11,
"cholera.cases": 2,
"cholera.deaths": 2 
},
{
 "month": 6,
"day": 23,
"day.index": 12,
"cholera.cases": 3,
"cholera.deaths": 2 
},
{
 "month": 6,
"day": 24,
"day.index": 13,
"cholera.cases": 3,
"cholera.deaths": 1 
},
{
 "month": 6,
"day": 25,
"day.index": 14,
"cholera.cases": 17,
"cholera.deaths": 14 
},
{
 "month": 6,
"day": 26,
"day.index": 15,
"cholera.cases": 4,
"cholera.deaths": 4 
},
{
 "month": 6,
"day": 27,
"day.index": 16,
"cholera.cases": 7,
"cholera.deaths": 4 
},
{
 "month": 6,
"day": 28,
"day.index": 17,
"cholera.cases": 11,
"cholera.deaths": 7 
},
{
 "month": 6,
"day": 29,
"day.index": 18,
"cholera.cases": 19,
"cholera.deaths": 13 
},
{
 "month": 6,
"day": 30,
"day.index": 19,
"cholera.cases": 9,
"cholera.deaths": 4 
},
{
 "month": 7,
"day": 1,
"day.index": 20,
"cholera.cases": 13,
"cholera.deaths": 9 
},
{
 "month": 7,
"day": 2,
"day.index": 21,
"cholera.cases": 31,
"cholera.deaths": 19 
},
{
 "month": 7,
"day": 3,
"day.index": 22,
"cholera.cases": 34,
"cholera.deaths": 30 
},
{
 "month": 7,
"day": 4,
"day.index": 23,
"cholera.cases": 42,
"cholera.deaths": 31 
},
{
 "month": 7,
"day": 5,
"day.index": 24,
"cholera.cases": 27,
"cholera.deaths": 13 
},
{
 "month": 7,
"day": 6,
"day.index": 25,
"cholera.cases": 44,
"cholera.deaths": 34 
},
{
 "month": 7,
"day": 7,
"day.index": 26,
"cholera.cases": 49,
"cholera.deaths": 39 
},
{
 "month": 7,
"day": 8,
"day.index": 27,
"cholera.cases": 49,
"cholera.deaths": 38 
},
{
 "month": 7,
"day": 9,
"day.index": 28,
"cholera.cases": 60,
"cholera.deaths": 42 
},
{
 "month": 7,
"day": 10,
"day.index": 29,
"cholera.cases": 49,
"cholera.deaths": 33 
},
{
 "month": 7,
"day": 11,
"day.index": 30,
"cholera.cases": 84,
"cholera.deaths": 59 
},
{
 "month": 7,
"day": 12,
"day.index": 31,
"cholera.cases": 73,
"cholera.deaths": 48 
},
{
 "month": 7,
"day": 13,
"day.index": 32,
"cholera.cases": 101,
"cholera.deaths": 73 
},
{
 "month": 7,
"day": 14,
"day.index": 33,
"cholera.cases": 153,
"cholera.deaths": 120 
},
{
 "month": 7,
"day": 15,
"day.index": 34,
"cholera.cases": 305,
"cholera.deaths": 229 
},
{
 "month": 7,
"day": 16,
"day.index": 35,
"cholera.cases": 309,
"cholera.deaths": 227 
},
{
 "month": 7,
"day": 17,
"day.index": 36,
"cholera.cases": 284,
"cholera.deaths": 198 
},
{
 "month": 7,
"day": 18,
"day.index": 37,
"cholera.cases": 255,
"cholera.deaths": 180 
},
{
 "month": 7,
"day": 19,
"day.index": 38,
"cholera.cases": 310,
"cholera.deaths": 202 
},
{
 "month": 7,
"day": 20,
"day.index": 39,
"cholera.cases": 333,
"cholera.deaths": 227 
},
{
 "month": 7,
"day": 21,
"day.index": 40,
"cholera.cases": 246,
"cholera.deaths": 175 
},
{
 "month": 7,
"day": 22,
"day.index": 41,
"cholera.cases": 258,
"cholera.deaths": 172 
},
{
 "month": 7,
"day": 23,
"day.index": 42,
"cholera.cases": 221,
"cholera.deaths": 152 
},
{
 "month": 7,
"day": 24,
"day.index": 43,
"cholera.cases": 209,
"cholera.deaths": 140 
},
{
 "month": 7,
"day": 25,
"day.index": 44,
"cholera.cases": 261,
"cholera.deaths": 172 
},
{
 "month": 7,
"day": 26,
"day.index": 45,
"cholera.cases": 270,
"cholera.deaths": 206 
},
{
 "month": 7,
"day": 27,
"day.index": 46,
"cholera.cases": 340,
"cholera.deaths": 217 
},
{
 "month": 7,
"day": 28,
"day.index": 47,
"cholera.cases": 277,
"cholera.deaths": 174 
},
{
 "month": 7,
"day": 29,
"day.index": 48,
"cholera.cases": 226,
"cholera.deaths": 160 
},
{
 "month": 7,
"day": 30,
"day.index": 49,
"cholera.cases": 213,
"cholera.deaths": 141 
},
{
 "month": 7,
"day": 31,
"day.index": 50,
"cholera.cases": 205,
"cholera.deaths": 136 
},
{
 "month": 8,
"day": 1,
"day.index": 51,
"cholera.cases": 147,
"cholera.deaths": 84 
},
{
 "month": 8,
"day": 2,
"day.index": 52,
"cholera.cases": 149,
"cholera.deaths": 92 
},
{
 "month": 8,
"day": 3,
"day.index": 53,
"cholera.cases": 133,
"cholera.deaths": 81 
},
{
 "month": 8,
"day": 4,
"day.index": 54,
"cholera.cases": 121,
"cholera.deaths": 61 
},
{
 "month": 8,
"day": 5,
"day.index": 55,
"cholera.cases": 120,
"cholera.deaths": 67 
},
{
 "month": 8,
"day": 6,
"day.index": 56,
"cholera.cases": 84,
"cholera.deaths": 45 
},
{
 "month": 8,
"day": 7,
"day.index": 57,
"cholera.cases": 59,
"cholera.deaths": 35 
},
{
 "month": 8,
"day": 8,
"day.index": 58,
"cholera.cases": 100,
"cholera.deaths": 52 
},
{
 "month": 8,
"day": 9,
"day.index": 59,
"cholera.cases": 78,
"cholera.deaths": 38 
},
{
 "month": 8,
"day": 10,
"day.index": 60,
"cholera.cases": 61,
"cholera.deaths": 32 
},
{
 "month": 8,
"day": 11,
"day.index": 61,
"cholera.cases": 63,
"cholera.deaths": 37 
},
{
 "month": 8,
"day": 12,
"day.index": 62,
"cholera.cases": 58,
"cholera.deaths": 41 
},
{
 "month": 8,
"day": 13,
"day.index": 63,
"cholera.cases": 47,
"cholera.deaths": 22 
},
{
 "month": 8,
"day": 14,
"day.index": 64,
"cholera.cases": 46,
"cholera.deaths": 23 
},
{
 "month": 8,
"day": 15,
"day.index": 65,
"cholera.cases": 46,
"cholera.deaths": 27 
},
{
 "month": 8,
"day": 16,
"day.index": 66,
"cholera.cases": 45,
"cholera.deaths": 24 
},
{
 "month": 8,
"day": 17,
"day.index": 67,
"cholera.cases": 34,
"cholera.deaths": 17 
},
{
 "month": 8,
"day": 18,
"day.index": 68,
"cholera.cases": 35,
"cholera.deaths": 18 
},
{
 "month": 8,
"day": 19,
"day.index": 69,
"cholera.cases": 33,
"cholera.deaths": 17 
},
{
 "month": 8,
"day": 20,
"day.index": 70,
"cholera.cases": 25,
"cholera.deaths": 9 
},
{
 "month": 8,
"day": 21,
"day.index": 71,
"cholera.cases": 20,
"cholera.deaths": 8 
},
{
 "month": 8,
"day": 22,
"day.index": 72,
"cholera.cases": 21,
"cholera.deaths": 11 
},
{
 "month": 8,
"day": 23,
"day.index": 73,
"cholera.cases": 32,
"cholera.deaths": 18 
},
{
 "month": 8,
"day": 24,
"day.index": 74,
"cholera.cases": 22,
"cholera.deaths": 10 
},
{
 "month": 8,
"day": 25,
"day.index": 75,
"cholera.cases": 29,
"cholera.deaths": 13 
},
{
 "month": 8,
"day": 26,
"day.index": 76,
"cholera.cases": 20,
"cholera.deaths": 13 
},
{
 "month": 8,
"day": 27,
"day.index": 77,
"cholera.cases": 13,
"cholera.deaths": 6 
},
{
 "month": 8,
"day": 28,
"day.index": 78,
"cholera.cases": 11,
"cholera.deaths": 6 
},
{
 "month": 8,
"day": 29,
"day.index": 79,
"cholera.cases": 21,
"cholera.deaths": 8 
},
{
 "month": 8,
"day": 30,
"day.index": 80,
"cholera.cases": 9,
"cholera.deaths": 4 
},
{
 "month": 8,
"day": 31,
"day.index": 81,
"cholera.cases": 10,
"cholera.deaths": 6 
},
{
 "month": 9,
"day": 1,
"day.index": 82,
"cholera.cases": 9,
"cholera.deaths": 4 
},
{
 "month": 9,
"day": 2,
"day.index": 83,
"cholera.cases": 8,
"cholera.deaths": 5 
},
{
 "month": 9,
"day": 3,
"day.index": 84,
"cholera.cases": 8,
"cholera.deaths": 4 
},
{
 "month": 9,
"day": 4,
"day.index": 85,
"cholera.cases": 11,
"cholera.deaths": 8 
},
{
 "month": 9,
"day": 5,
"day.index": 86,
"cholera.cases": 6,
"cholera.deaths": 3 
},
{
 "month": 9,
"day": 6,
"day.index": 87,
"cholera.cases": 5,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 7,
"day.index": 88,
"cholera.cases": 3,
"cholera.deaths": 2 
},
{
 "month": 9,
"day": 8,
"day.index": 89,
"cholera.cases": 3,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 9,
"day.index": 90,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 10,
"day.index": 91,
"cholera.cases": 2,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 11,
"day.index": 92,
"cholera.cases": 3,
"cholera.deaths": 3 
},
{
 "month": 9,
"day": 12,
"day.index": 93,
"cholera.cases": 4,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 13,
"day.index": 94,
"cholera.cases": 4,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 14,
"day.index": 95,
"cholera.cases": 8,
"cholera.deaths": 6 
},
{
 "month": 9,
"day": 15,
"day.index": 96,
"cholera.cases": 8,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 16,
"day.index": 97,
"cholera.cases": 1,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 17,
"day.index": 98,
"cholera.cases": 5,
"cholera.deaths": 3 
},
{
 "month": 9,
"day": 18,
"day.index": 99,
"cholera.cases": 6,
"cholera.deaths": 5 
},
{
 "month": 9,
"day": 19,
"day.index": 100,
"cholera.cases": 2,
"cholera.deaths": 2 
},
{
 "month": 9,
"day": 20,
"day.index": 101,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 21,
"day.index": 102,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 22,
"day.index": 103,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 23,
"day.index": 104,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 24,
"day.index": 105,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 9,
"day": 25,
"day.index": 106,
"cholera.cases": 3,
"cholera.deaths": 3 
},
{
 "month": 9,
"day": 26,
"day.index": 107,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 27,
"day.index": 108,
"cholera.cases": 0,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 28,
"day.index": 109,
"cholera.cases": 1,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 29,
"day.index": 110,
"cholera.cases": 1,
"cholera.deaths": 0 
},
{
 "month": 9,
"day": 30,
"day.index": 111,
"cholera.cases": 1,
"cholera.deaths": 1 
},
{
 "month": 10,
"day": 1,
"day.index": 112,
"cholera.cases": 1,
"cholera.deaths": 1 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        chart.xAxis
  .axisLabel("Day Index")
  .width(    90)

        
        
        chart.yAxis
  .axisLabel("Number infected")
  .width(    40)
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
      
      //add our title with html
      //might be better with svg
      d3.select("#" + opts.id).insert("h3","svg")
        .text(opts.title);
        //if desired, could change styling with css or with d3
        //some examples here http://tympanus.net/codrops/2012/11/02/heading-set-styling-with-css/
        //will use example
        //.style("float","right");
        //.style("text-shadow", "0 -1px 1px rgba(0,0,0,0.4)")
        //.style("font-size","22px")
        //.style("line-height", "40px")
        //.style("color", "#355681")
        //.style("ext-transform", "uppercase")
        //.style("border-bottom", "1px solid rgba(53,86,129, 0.3)");
    };
</script>

--- .class #id
## 

<div id = 'chart1e1c610682' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart1e1c610682()
    });
    function drawchart1e1c610682(){  
      var opts = {
 "dom": "chart1e1c610682",
"width":    800,
"height":    400,
"x": "startday.index",
"y": "sick.total.week",
"group": "quarter",
"type": "lineChart",
"title": "Un-normalized weekly incidence",
"id": "chart1e1c610682" 
},
        data = [
 {
 "quarter": "Christianshavn",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Christianshavn",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Christianshavn",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 4,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1 
},
{
 "quarter": "Christianshavn",
"startday.index":             21,
"mensick.week": 4,
"mendead.week": 3,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 13,
"dead.total.week": 9 
},
{
 "quarter": "Christianshavn",
"startday.index":             28,
"mensick.week": 40,
"mendead.week": 26,
"womensick.week": 45,
"womendead.week": 37,
"sick.total.week": 85,
"dead.total.week": 63 
},
{
 "quarter": "Christianshavn",
"startday.index":             35,
"mensick.week": 137,
"mendead.week": 97,
"womensick.week": 135,
"womendead.week": 102,
"sick.total.week": 272,
"dead.total.week": 199 
},
{
 "quarter": "Christianshavn",
"startday.index":             42,
"mensick.week": 211,
"mendead.week": 146,
"womensick.week": 216,
"womendead.week": 150,
"sick.total.week": 427,
"dead.total.week": 296 
},
{
 "quarter": "Christianshavn",
"startday.index":             49,
"mensick.week": 113,
"mendead.week": 65,
"womensick.week": 114,
"womendead.week": 64,
"sick.total.week": 227,
"dead.total.week": 129 
},
{
 "quarter": "Christianshavn",
"startday.index":             56,
"mensick.week": 36,
"mendead.week": 12,
"womensick.week": 45,
"womendead.week": 20,
"sick.total.week": 81,
"dead.total.week": 32 
},
{
 "quarter": "Christianshavn",
"startday.index":             63,
"mensick.week": 11,
"mendead.week": 6,
"womensick.week": 10,
"womendead.week": 7,
"sick.total.week": 21,
"dead.total.week": 13 
},
{
 "quarter": "Christianshavn",
"startday.index":             70,
"mensick.week": 8,
"mendead.week": 3,
"womensick.week": 6,
"womendead.week": 4,
"sick.total.week": 14,
"dead.total.week": 7 
},
{
 "quarter": "Christianshavn",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 8,
"dead.total.week": 6 
},
{
 "quarter": "Christianshavn",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 2 
},
{
 "quarter": "Christianshavn",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Christianshavn",
"startday.index":             98,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Christianshavn",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Frimands",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":             21,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Frimands",
"startday.index":             28,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Frimands",
"startday.index":             35,
"mensick.week": 7,
"mendead.week": 5,
"womensick.week": 6,
"womendead.week": 3,
"sick.total.week": 13,
"dead.total.week": 8 
},
{
 "quarter": "Frimands",
"startday.index":             42,
"mensick.week": 5,
"mendead.week": 4,
"womensick.week": 6,
"womendead.week": 5,
"sick.total.week": 11,
"dead.total.week": 9 
},
{
 "quarter": "Frimands",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 8,
"womendead.week": 4,
"sick.total.week": 14,
"dead.total.week": 8 
},
{
 "quarter": "Frimands",
"startday.index":             56,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 4 
},
{
 "quarter": "Frimands",
"startday.index":             63,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Frimands",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 2 
},
{
 "quarter": "Frimands",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Frimands",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Kjoebmager",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Kjoebmager",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Kjoebmager",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Kjoebmager",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 5,
"womendead.week": 3,
"sick.total.week": 5,
"dead.total.week": 3 
},
{
 "quarter": "Kjoebmager",
"startday.index":             28,
"mensick.week": 17,
"mendead.week": 11,
"womensick.week": 8,
"womendead.week": 4,
"sick.total.week": 25,
"dead.total.week": 15 
},
{
 "quarter": "Kjoebmager",
"startday.index":             35,
"mensick.week": 21,
"mendead.week": 12,
"womensick.week": 27,
"womendead.week": 11,
"sick.total.week": 48,
"dead.total.week": 23 
},
{
 "quarter": "Kjoebmager",
"startday.index":             42,
"mensick.week": 47,
"mendead.week": 30,
"womensick.week": 38,
"womendead.week": 25,
"sick.total.week": 85,
"dead.total.week": 55 
},
{
 "quarter": "Kjoebmager",
"startday.index":             49,
"mensick.week": 42,
"mendead.week": 22,
"womensick.week": 48,
"womendead.week": 24,
"sick.total.week": 90,
"dead.total.week": 46 
},
{
 "quarter": "Kjoebmager",
"startday.index":             56,
"mensick.week": 17,
"mendead.week": 12,
"womensick.week": 21,
"womendead.week": 13,
"sick.total.week": 38,
"dead.total.week": 25 
},
{
 "quarter": "Kjoebmager",
"startday.index":             63,
"mensick.week": 6,
"mendead.week": 2,
"womensick.week": 12,
"womendead.week": 5,
"sick.total.week": 18,
"dead.total.week": 7 
},
{
 "quarter": "Kjoebmager",
"startday.index":             70,
"mensick.week": 4,
"mendead.week": 1,
"womensick.week": 9,
"womendead.week": 5,
"sick.total.week": 13,
"dead.total.week": 6 
},
{
 "quarter": "Kjoebmager",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 0,
"womensick.week": 5,
"womendead.week": 2,
"sick.total.week": 11,
"dead.total.week": 2 
},
{
 "quarter": "Kjoebmager",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0 
},
{
 "quarter": "Kjoebmager",
"startday.index":             91,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "Kjoebmager",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Kjoebmager",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":             28,
"mensick.week": 5,
"mendead.week": 5,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 7,
"dead.total.week": 6 
},
{
 "quarter": "Klaedebo",
"startday.index":             35,
"mensick.week": 9,
"mendead.week": 4,
"womensick.week": 18,
"womendead.week": 16,
"sick.total.week": 27,
"dead.total.week": 20 
},
{
 "quarter": "Klaedebo",
"startday.index":             42,
"mensick.week": 17,
"mendead.week": 8,
"womensick.week": 17,
"womendead.week": 12,
"sick.total.week": 34,
"dead.total.week": 20 
},
{
 "quarter": "Klaedebo",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 6,
"womensick.week": 6,
"womendead.week": 4,
"sick.total.week": 12,
"dead.total.week": 10 
},
{
 "quarter": "Klaedebo",
"startday.index":             56,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 4,
"womendead.week": 4,
"sick.total.week": 6,
"dead.total.week": 6 
},
{
 "quarter": "Klaedebo",
"startday.index":             63,
"mensick.week": 3,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1 
},
{
 "quarter": "Klaedebo",
"startday.index":             70,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1 
},
{
 "quarter": "Klaedebo",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Klaedebo",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Klaedebo",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Klaedebo",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Klaedebo",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Noerre",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Noerre",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Noerre",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Noerre",
"startday.index":             21,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1 
},
{
 "quarter": "Noerre",
"startday.index":             28,
"mensick.week": 11,
"mendead.week": 9,
"womensick.week": 4,
"womendead.week": 3,
"sick.total.week": 15,
"dead.total.week": 12 
},
{
 "quarter": "Noerre",
"startday.index":             35,
"mensick.week": 14,
"mendead.week": 10,
"womensick.week": 11,
"womendead.week": 6,
"sick.total.week": 25,
"dead.total.week": 16 
},
{
 "quarter": "Noerre",
"startday.index":             42,
"mensick.week": 17,
"mendead.week": 14,
"womensick.week": 26,
"womendead.week": 17,
"sick.total.week": 43,
"dead.total.week": 31 
},
{
 "quarter": "Noerre",
"startday.index":             49,
"mensick.week": 22,
"mendead.week": 14,
"womensick.week": 29,
"womendead.week": 18,
"sick.total.week": 51,
"dead.total.week": 32 
},
{
 "quarter": "Noerre",
"startday.index":             56,
"mensick.week": 13,
"mendead.week": 6,
"womensick.week": 17,
"womendead.week": 11,
"sick.total.week": 30,
"dead.total.week": 17 
},
{
 "quarter": "Noerre",
"startday.index":             63,
"mensick.week": 15,
"mendead.week": 10,
"womensick.week": 15,
"womendead.week": 10,
"sick.total.week": 30,
"dead.total.week": 20 
},
{
 "quarter": "Noerre",
"startday.index":             70,
"mensick.week": 12,
"mendead.week": 8,
"womensick.week": 7,
"womendead.week": 2,
"sick.total.week": 19,
"dead.total.week": 10 
},
{
 "quarter": "Noerre",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 4 
},
{
 "quarter": "Noerre",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Noerre",
"startday.index":             91,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 0 
},
{
 "quarter": "Noerre",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Noerre",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Nyboder",
"startday.index":              0,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Nyboder",
"startday.index":              7,
"mensick.week": 3,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 3 
},
{
 "quarter": "Nyboder",
"startday.index":             14,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 2 
},
{
 "quarter": "Nyboder",
"startday.index":             21,
"mensick.week": 5,
"mendead.week": 5,
"womensick.week": 8,
"womendead.week": 7,
"sick.total.week": 13,
"dead.total.week": 12 
},
{
 "quarter": "Nyboder",
"startday.index":             28,
"mensick.week": 45,
"mendead.week": 33,
"womensick.week": 62,
"womendead.week": 47,
"sick.total.week": 107,
"dead.total.week": 80 
},
{
 "quarter": "Nyboder",
"startday.index":             35,
"mensick.week": 65,
"mendead.week": 50,
"womensick.week": 102,
"womendead.week": 76,
"sick.total.week": 167,
"dead.total.week": 126 
},
{
 "quarter": "Nyboder",
"startday.index":             42,
"mensick.week": 51,
"mendead.week": 37,
"womensick.week": 63,
"womendead.week": 50,
"sick.total.week": 114,
"dead.total.week": 87 
},
{
 "quarter": "Nyboder",
"startday.index":             49,
"mensick.week": 42,
"mendead.week": 21,
"womensick.week": 49,
"womendead.week": 31,
"sick.total.week": 91,
"dead.total.week": 52 
},
{
 "quarter": "Nyboder",
"startday.index":             56,
"mensick.week": 14,
"mendead.week": 10,
"womensick.week": 14,
"womendead.week": 7,
"sick.total.week": 28,
"dead.total.week": 17 
},
{
 "quarter": "Nyboder",
"startday.index":             63,
"mensick.week": 7,
"mendead.week": 2,
"womensick.week": 6,
"womendead.week": 1,
"sick.total.week": 13,
"dead.total.week": 3 
},
{
 "quarter": "Nyboder",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 5,
"womendead.week": 3,
"sick.total.week": 8,
"dead.total.week": 5 
},
{
 "quarter": "Nyboder",
"startday.index":             77,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 2 
},
{
 "quarter": "Nyboder",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Nyboder",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Nyboder",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Nyboder",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Oester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Oester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Oester",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 3,
"dead.total.week": 2 
},
{
 "quarter": "Oester",
"startday.index":             21,
"mensick.week": 5,
"mendead.week": 2,
"womensick.week": 6,
"womendead.week": 5,
"sick.total.week": 11,
"dead.total.week": 7 
},
{
 "quarter": "Oester",
"startday.index":             28,
"mensick.week": 12,
"mendead.week": 9,
"womensick.week": 19,
"womendead.week": 11,
"sick.total.week": 31,
"dead.total.week": 20 
},
{
 "quarter": "Oester",
"startday.index":             35,
"mensick.week": 24,
"mendead.week": 18,
"womensick.week": 61,
"womendead.week": 35,
"sick.total.week": 85,
"dead.total.week": 53 
},
{
 "quarter": "Oester",
"startday.index":             42,
"mensick.week": 25,
"mendead.week": 13,
"womensick.week": 41,
"womendead.week": 25,
"sick.total.week": 66,
"dead.total.week": 38 
},
{
 "quarter": "Oester",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 15,
"dead.total.week": 9 
},
{
 "quarter": "Oester",
"startday.index":             56,
"mensick.week": 10,
"mendead.week": 6,
"womensick.week": 16,
"womendead.week": 10,
"sick.total.week": 26,
"dead.total.week": 16 
},
{
 "quarter": "Oester",
"startday.index":             63,
"mensick.week": 7,
"mendead.week": 5,
"womensick.week": 4,
"womendead.week": 2,
"sick.total.week": 11,
"dead.total.week": 7 
},
{
 "quarter": "Oester",
"startday.index":             70,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 7,
"womendead.week": 2,
"sick.total.week": 9,
"dead.total.week": 3 
},
{
 "quarter": "Oester",
"startday.index":             77,
"mensick.week": 4,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 6,
"dead.total.week": 4 
},
{
 "quarter": "Oester",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Oester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "Oester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Oester",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "Rosenborg",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Rosenborg",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 3,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1 
},
{
 "quarter": "Rosenborg",
"startday.index":             14,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 12,
"womendead.week": 5,
"sick.total.week": 18,
"dead.total.week": 8 
},
{
 "quarter": "Rosenborg",
"startday.index":             21,
"mensick.week": 4,
"mendead.week": 3,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 11,
"dead.total.week": 6 
},
{
 "quarter": "Rosenborg",
"startday.index":             28,
"mensick.week": 25,
"mendead.week": 16,
"womensick.week": 7,
"womendead.week": 5,
"sick.total.week": 32,
"dead.total.week": 21 
},
{
 "quarter": "Rosenborg",
"startday.index":             35,
"mensick.week": 23,
"mendead.week": 14,
"womensick.week": 28,
"womendead.week": 17,
"sick.total.week": 51,
"dead.total.week": 31 
},
{
 "quarter": "Rosenborg",
"startday.index":             42,
"mensick.week": 40,
"mendead.week": 23,
"womensick.week": 37,
"womendead.week": 20,
"sick.total.week": 77,
"dead.total.week": 43 
},
{
 "quarter": "Rosenborg",
"startday.index":             49,
"mensick.week": 31,
"mendead.week": 21,
"womensick.week": 41,
"womendead.week": 29,
"sick.total.week": 72,
"dead.total.week": 50 
},
{
 "quarter": "Rosenborg",
"startday.index":             56,
"mensick.week": 20,
"mendead.week": 10,
"womensick.week": 19,
"womendead.week": 9,
"sick.total.week": 39,
"dead.total.week": 19 
},
{
 "quarter": "Rosenborg",
"startday.index":             63,
"mensick.week": 11,
"mendead.week": 2,
"womensick.week": 20,
"womendead.week": 12,
"sick.total.week": 31,
"dead.total.week": 14 
},
{
 "quarter": "Rosenborg",
"startday.index":             70,
"mensick.week": 11,
"mendead.week": 8,
"womensick.week": 10,
"womendead.week": 10,
"sick.total.week": 21,
"dead.total.week": 18 
},
{
 "quarter": "Rosenborg",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 4 
},
{
 "quarter": "Rosenborg",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Rosenborg",
"startday.index":             91,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 2 
},
{
 "quarter": "Rosenborg",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Rosenborg",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":             14,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 2 
},
{
 "quarter": "Snarens",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":             28,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "Snarens",
"startday.index":             35,
"mensick.week": 5,
"mendead.week": 1,
"womensick.week": 10,
"womendead.week": 4,
"sick.total.week": 15,
"dead.total.week": 5 
},
{
 "quarter": "Snarens",
"startday.index":             42,
"mensick.week": 35,
"mendead.week": 28,
"womensick.week": 25,
"womendead.week": 18,
"sick.total.week": 60,
"dead.total.week": 46 
},
{
 "quarter": "Snarens",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 9,
"womendead.week": 4,
"sick.total.week": 15,
"dead.total.week": 8 
},
{
 "quarter": "Snarens",
"startday.index":             56,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 10,
"dead.total.week": 6 
},
{
 "quarter": "Snarens",
"startday.index":             63,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 3,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 3 
},
{
 "quarter": "Snarens",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 1 
},
{
 "quarter": "Snarens",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Snarens",
"startday.index":             91,
"mensick.week": 6,
"mendead.week": 2,
"womensick.week": 3,
"womendead.week": 0,
"sick.total.week": 9,
"dead.total.week": 2 
},
{
 "quarter": "Snarens",
"startday.index":             98,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "Snarens",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":              0,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             21,
"mensick.week": 10,
"mendead.week": 7,
"womensick.week": 10,
"womendead.week": 7,
"sick.total.week": 20,
"dead.total.week": 14 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             28,
"mensick.week": 74,
"mendead.week": 53,
"womensick.week": 74,
"womendead.week": 57,
"sick.total.week": 148,
"dead.total.week": 110 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             35,
"mensick.week": 83,
"mendead.week": 54,
"womensick.week": 98,
"womendead.week": 54,
"sick.total.week": 181,
"dead.total.week": 108 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             42,
"mensick.week": 32,
"mendead.week": 24,
"womensick.week": 44,
"womendead.week": 27,
"sick.total.week": 76,
"dead.total.week": 51 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             49,
"mensick.week": 9,
"mendead.week": 6,
"womensick.week": 13,
"womendead.week": 9,
"sick.total.week": 22,
"dead.total.week": 15 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             56,
"mensick.week": 6,
"mendead.week": 5,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 15,
"dead.total.week": 11 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             63,
"mensick.week": 6,
"mendead.week": 5,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 13,
"dead.total.week": 8 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             77,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":            105,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Vester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Vester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             14,
"mensick.week": 17,
"mendead.week": 12,
"womensick.week": 19,
"womendead.week": 1,
"sick.total.week": 36,
"dead.total.week": 13 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             21,
"mensick.week": 61,
"mendead.week": 47,
"womensick.week": 65,
"womendead.week": 47,
"sick.total.week": 126,
"dead.total.week": 94 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             28,
"mensick.week": 132,
"mendead.week": 96,
"womensick.week": 162,
"womendead.week": 109,
"sick.total.week": 294,
"dead.total.week": 205 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             35,
"mensick.week": 171,
"mendead.week": 108,
"womensick.week": 252,
"womendead.week": 151,
"sick.total.week": 423,
"dead.total.week": 259 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             42,
"mensick.week": 151,
"mendead.week": 93,
"womensick.week": 201,
"womendead.week": 127,
"sick.total.week": 352,
"dead.total.week": 220 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             49,
"mensick.week": 72,
"mendead.week": 44,
"womensick.week": 86,
"womendead.week": 46,
"sick.total.week": 158,
"dead.total.week": 90 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             56,
"mensick.week": 30,
"mendead.week": 18,
"womensick.week": 42,
"womendead.week": 21,
"sick.total.week": 72,
"dead.total.week": 39 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             63,
"mensick.week": 13,
"mendead.week": 8,
"womensick.week": 26,
"womendead.week": 8,
"sick.total.week": 39,
"dead.total.week": 16 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             70,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 5,
"womendead.week": 0,
"sick.total.week": 11,
"dead.total.week": 3 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 4,
"womendead.week": 0,
"sick.total.week": 10,
"dead.total.week": 4 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             98,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 3 
},
{
 "quarter": "St. Annae Vester",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 1 
},
{
 "quarter": "Strand",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             28,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 1 
},
{
 "quarter": "Strand",
"startday.index":             35,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1 
},
{
 "quarter": "Strand",
"startday.index":             42,
"mensick.week": 4,
"mendead.week": 4,
"womensick.week": 4,
"womendead.week": 1,
"sick.total.week": 8,
"dead.total.week": 5 
},
{
 "quarter": "Strand",
"startday.index":             49,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Strand",
"startday.index":             56,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             63,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1 
},
{
 "quarter": "Strand",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Strand",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":             21,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 3,
"womendead.week": 3,
"sick.total.week": 4,
"dead.total.week": 4 
},
{
 "quarter": "Vester",
"startday.index":             28,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 2 
},
{
 "quarter": "Vester",
"startday.index":             35,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":             42,
"mensick.week": 20,
"mendead.week": 10,
"womensick.week": 23,
"womendead.week": 18,
"sick.total.week": 43,
"dead.total.week": 28 
},
{
 "quarter": "Vester",
"startday.index":             49,
"mensick.week": 9,
"mendead.week": 4,
"womensick.week": 15,
"womendead.week": 13,
"sick.total.week": 24,
"dead.total.week": 17 
},
{
 "quarter": "Vester",
"startday.index":             56,
"mensick.week": 9,
"mendead.week": 6,
"womensick.week": 9,
"womendead.week": 4,
"sick.total.week": 18,
"dead.total.week": 10 
},
{
 "quarter": "Vester",
"startday.index":             63,
"mensick.week": 5,
"mendead.week": 3,
"womensick.week": 6,
"womendead.week": 3,
"sick.total.week": 11,
"dead.total.week": 6 
},
{
 "quarter": "Vester",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 3,
"womendead.week": 2,
"sick.total.week": 6,
"dead.total.week": 4 
},
{
 "quarter": "Vester",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 3 
},
{
 "quarter": "Vester",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 2 
},
{
 "quarter": "Vester",
"startday.index":             91,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1 
},
{
 "quarter": "Vester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0 
},
{
 "quarter": "Vester",
"startday.index":            105,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        chart.xAxis
  .axisLabel("Day Index")
  .width(    90)

        
        
        chart.yAxis
  .axisLabel("Number infected")
  .width(    40)
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
      
      //add our title with html
      //might be better with svg
      d3.select("#" + opts.id).insert("h3","svg")
        .text(opts.title);
        //if desired, could change styling with css or with d3
        //some examples here http://tympanus.net/codrops/2012/11/02/heading-set-styling-with-css/
        //will use example
        //.style("float","right");
        //.style("text-shadow", "0 -1px 1px rgba(0,0,0,0.4)")
        //.style("font-size","22px")
        //.style("line-height", "40px")
        //.style("color", "#355681")
        //.style("ext-transform", "uppercase")
        //.style("border-bottom", "1px solid rgba(53,86,129, 0.3)");
    };
</script>

--- .class #id


<div id = 'chart1e1c405433e4' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart1e1c405433e4()
    });
    function drawchart1e1c405433e4(){  
      var opts = {
 "dom": "chart1e1c405433e4",
"width":    800,
"height":    400,
"x": "startday.index",
"y": "normal.incidence",
"group": "quarter",
"type": "lineChart",
"title": "Normalized weekly incidence",
"id": "chart1e1c405433e4" 
},
        data = [
 {
 "quarter": "Christianshavn",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Christianshavn",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.1,
"normal.mortality": 0.06066856761512 
},
{
 "quarter": "Christianshavn",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 4,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.2,
"normal.mortality": 0.06066856761512 
},
{
 "quarter": "Christianshavn",
"startday.index":             21,
"mensick.week": 4,
"mendead.week": 3,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 13,
"dead.total.week": 9,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.8,
"normal.mortality": 0.5460171085361 
},
{
 "quarter": "Christianshavn",
"startday.index":             28,
"mensick.week": 40,
"mendead.week": 26,
"womensick.week": 45,
"womendead.week": 37,
"sick.total.week": 85,
"dead.total.week": 63,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            5.2,
"normal.mortality": 3.822119759752 
},
{
 "quarter": "Christianshavn",
"startday.index":             35,
"mensick.week": 137,
"mendead.week": 97,
"womensick.week": 135,
"womendead.week": 102,
"sick.total.week": 272,
"dead.total.week": 199,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":           16.5,
"normal.mortality": 12.07304495541 
},
{
 "quarter": "Christianshavn",
"startday.index":             42,
"mensick.week": 211,
"mendead.week": 146,
"womensick.week": 216,
"womendead.week": 150,
"sick.total.week": 427,
"dead.total.week": 296,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":           25.9,
"normal.mortality": 17.95789601408 
},
{
 "quarter": "Christianshavn",
"startday.index":             49,
"mensick.week": 113,
"mendead.week": 65,
"womensick.week": 114,
"womendead.week": 64,
"sick.total.week": 227,
"dead.total.week": 129,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":           13.8,
"normal.mortality":  7.82624522235 
},
{
 "quarter": "Christianshavn",
"startday.index":             56,
"mensick.week": 36,
"mendead.week": 12,
"womensick.week": 45,
"womendead.week": 20,
"sick.total.week": 81,
"dead.total.week": 32,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            4.9,
"normal.mortality": 1.941394163684 
},
{
 "quarter": "Christianshavn",
"startday.index":             63,
"mensick.week": 11,
"mendead.week": 6,
"womensick.week": 10,
"womendead.week": 7,
"sick.total.week": 21,
"dead.total.week": 13,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            1.3,
"normal.mortality": 0.7886913789965 
},
{
 "quarter": "Christianshavn",
"startday.index":             70,
"mensick.week": 8,
"mendead.week": 3,
"womensick.week": 6,
"womendead.week": 4,
"sick.total.week": 14,
"dead.total.week": 7,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.8,
"normal.mortality": 0.4246799733058 
},
{
 "quarter": "Christianshavn",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 8,
"dead.total.week": 6,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.5,
"normal.mortality": 0.3640114056907 
},
{
 "quarter": "Christianshavn",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 2,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.2,
"normal.mortality": 0.1213371352302 
},
{
 "quarter": "Christianshavn",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Christianshavn",
"startday.index":             98,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.1,
"normal.mortality": 0.1213371352302 
},
{
 "quarter": "Christianshavn",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 16483,
"pop1850": 14865,
"normal.incidence":            0.1,
"normal.mortality": 0.06066856761512 
},
{
 "quarter": "Frimands",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":             21,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            0.4,
"normal.mortality": 0.1982946658735 
},
{
 "quarter": "Frimands",
"startday.index":             28,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            0.4,
"normal.mortality": 0.1982946658735 
},
{
 "quarter": "Frimands",
"startday.index":             35,
"mensick.week": 7,
"mendead.week": 5,
"womensick.week": 6,
"womendead.week": 3,
"sick.total.week": 13,
"dead.total.week": 8,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            2.6,
"normal.mortality": 1.586357326988 
},
{
 "quarter": "Frimands",
"startday.index":             42,
"mensick.week": 5,
"mendead.week": 4,
"womensick.week": 6,
"womendead.week": 5,
"sick.total.week": 11,
"dead.total.week": 9,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            2.2,
"normal.mortality": 1.784651992861 
},
{
 "quarter": "Frimands",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 8,
"womendead.week": 4,
"sick.total.week": 14,
"dead.total.week": 8,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            2.8,
"normal.mortality": 1.586357326988 
},
{
 "quarter": "Frimands",
"startday.index":             56,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 4,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              1,
"normal.mortality": 0.793178663494 
},
{
 "quarter": "Frimands",
"startday.index":             63,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            0.4,
"normal.mortality": 0.396589331747 
},
{
 "quarter": "Frimands",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 2,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":            0.8,
"normal.mortality": 0.396589331747 
},
{
 "quarter": "Frimands",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Frimands",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 5043,
"pop1850": 4813,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Kjoebmager",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Kjoebmager",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.1,
"normal.mortality": 0.08564576909901 
},
{
 "quarter": "Kjoebmager",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.2,
"normal.mortality": 0.08564576909901 
},
{
 "quarter": "Kjoebmager",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 5,
"womendead.week": 3,
"sick.total.week": 5,
"dead.total.week": 3,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.4,
"normal.mortality": 0.256937307297 
},
{
 "quarter": "Kjoebmager",
"startday.index":             28,
"mensick.week": 17,
"mendead.week": 11,
"womensick.week": 8,
"womendead.week": 4,
"sick.total.week": 25,
"dead.total.week": 15,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            2.1,
"normal.mortality": 1.284686536485 
},
{
 "quarter": "Kjoebmager",
"startday.index":             35,
"mensick.week": 21,
"mendead.week": 12,
"womensick.week": 27,
"womendead.week": 11,
"sick.total.week": 48,
"dead.total.week": 23,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            4.1,
"normal.mortality": 1.969852689277 
},
{
 "quarter": "Kjoebmager",
"startday.index":             42,
"mensick.week": 47,
"mendead.week": 30,
"womensick.week": 38,
"womendead.week": 25,
"sick.total.week": 85,
"dead.total.week": 55,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            7.3,
"normal.mortality": 4.710517300445 
},
{
 "quarter": "Kjoebmager",
"startday.index":             49,
"mensick.week": 42,
"mendead.week": 22,
"womensick.week": 48,
"womendead.week": 24,
"sick.total.week": 90,
"dead.total.week": 46,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            7.7,
"normal.mortality": 3.939705378554 
},
{
 "quarter": "Kjoebmager",
"startday.index":             56,
"mensick.week": 17,
"mendead.week": 12,
"womensick.week": 21,
"womendead.week": 13,
"sick.total.week": 38,
"dead.total.week": 25,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            3.3,
"normal.mortality": 2.141144227475 
},
{
 "quarter": "Kjoebmager",
"startday.index":             63,
"mensick.week": 6,
"mendead.week": 2,
"womensick.week": 12,
"womendead.week": 5,
"sick.total.week": 18,
"dead.total.week": 7,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            1.5,
"normal.mortality": 0.599520383693 
},
{
 "quarter": "Kjoebmager",
"startday.index":             70,
"mensick.week": 4,
"mendead.week": 1,
"womensick.week": 9,
"womendead.week": 5,
"sick.total.week": 13,
"dead.total.week": 6,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            1.1,
"normal.mortality": 0.513874614594 
},
{
 "quarter": "Kjoebmager",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 0,
"womensick.week": 5,
"womendead.week": 2,
"sick.total.week": 11,
"dead.total.week": 2,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.9,
"normal.mortality": 0.171291538198 
},
{
 "quarter": "Kjoebmager",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.3,
"normal.mortality":              0 
},
{
 "quarter": "Kjoebmager",
"startday.index":             91,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "Kjoebmager",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":            0.1,
"normal.mortality": 0.08564576909901 
},
{
 "quarter": "Kjoebmager",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 11676,
"pop1850": 11345,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":             28,
"mensick.week": 5,
"mendead.week": 5,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 7,
"dead.total.week": 6,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              1,
"normal.mortality": 0.8527572484366 
},
{
 "quarter": "Klaedebo",
"startday.index":             35,
"mensick.week": 9,
"mendead.week": 4,
"womensick.week": 18,
"womendead.week": 16,
"sick.total.week": 27,
"dead.total.week": 20,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            3.8,
"normal.mortality": 2.842524161455 
},
{
 "quarter": "Klaedebo",
"startday.index":             42,
"mensick.week": 17,
"mendead.week": 8,
"womensick.week": 17,
"womendead.week": 12,
"sick.total.week": 34,
"dead.total.week": 20,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            4.8,
"normal.mortality": 2.842524161455 
},
{
 "quarter": "Klaedebo",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 6,
"womensick.week": 6,
"womendead.week": 4,
"sick.total.week": 12,
"dead.total.week": 10,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            1.7,
"normal.mortality": 1.421262080728 
},
{
 "quarter": "Klaedebo",
"startday.index":             56,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 4,
"womendead.week": 4,
"sick.total.week": 6,
"dead.total.week": 6,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.9,
"normal.mortality": 0.8527572484366 
},
{
 "quarter": "Klaedebo",
"startday.index":             63,
"mensick.week": 3,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.6,
"normal.mortality": 0.1421262080728 
},
{
 "quarter": "Klaedebo",
"startday.index":             70,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 1,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.6,
"normal.mortality": 0.1421262080728 
},
{
 "quarter": "Klaedebo",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.3,
"normal.mortality": 0.1421262080728 
},
{
 "quarter": "Klaedebo",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.3,
"normal.mortality": 0.2842524161455 
},
{
 "quarter": "Klaedebo",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":            0.3,
"normal.mortality": 0.2842524161455 
},
{
 "quarter": "Klaedebo",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Klaedebo",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 7036,
"pop1850": 6663,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Noerre",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Noerre",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.1,
"normal.mortality": 0.1088376142795 
},
{
 "quarter": "Noerre",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Noerre",
"startday.index":             21,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.3,
"normal.mortality": 0.1088376142795 
},
{
 "quarter": "Noerre",
"startday.index":             28,
"mensick.week": 11,
"mendead.week": 9,
"womensick.week": 4,
"womendead.week": 3,
"sick.total.week": 15,
"dead.total.week": 12,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            1.6,
"normal.mortality": 1.306051371354 
},
{
 "quarter": "Noerre",
"startday.index":             35,
"mensick.week": 14,
"mendead.week": 10,
"womensick.week": 11,
"womendead.week": 6,
"sick.total.week": 25,
"dead.total.week": 16,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            2.7,
"normal.mortality": 1.741401828472 
},
{
 "quarter": "Noerre",
"startday.index":             42,
"mensick.week": 17,
"mendead.week": 14,
"womensick.week": 26,
"womendead.week": 17,
"sick.total.week": 43,
"dead.total.week": 31,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            4.7,
"normal.mortality": 3.373966042664 
},
{
 "quarter": "Noerre",
"startday.index":             49,
"mensick.week": 22,
"mendead.week": 14,
"womensick.week": 29,
"womendead.week": 18,
"sick.total.week": 51,
"dead.total.week": 32,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            5.6,
"normal.mortality": 3.482803656944 
},
{
 "quarter": "Noerre",
"startday.index":             56,
"mensick.week": 13,
"mendead.week": 6,
"womensick.week": 17,
"womendead.week": 11,
"sick.total.week": 30,
"dead.total.week": 17,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            3.3,
"normal.mortality": 1.850239442751 
},
{
 "quarter": "Noerre",
"startday.index":             63,
"mensick.week": 15,
"mendead.week": 10,
"womensick.week": 15,
"womendead.week": 10,
"sick.total.week": 30,
"dead.total.week": 20,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            3.3,
"normal.mortality":  2.17675228559 
},
{
 "quarter": "Noerre",
"startday.index":             70,
"mensick.week": 12,
"mendead.week": 8,
"womensick.week": 7,
"womendead.week": 2,
"sick.total.week": 19,
"dead.total.week": 10,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            2.1,
"normal.mortality": 1.088376142795 
},
{
 "quarter": "Noerre",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 4,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.5,
"normal.mortality": 0.435350457118 
},
{
 "quarter": "Noerre",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.2,
"normal.mortality": 0.217675228559 
},
{
 "quarter": "Noerre",
"startday.index":             91,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 0,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.2,
"normal.mortality":              0 
},
{
 "quarter": "Noerre",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Noerre",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 9188,
"pop1850": 8979,
"normal.incidence":            0.1,
"normal.mortality": 0.1088376142795 
},
{
 "quarter": "Nyboder",
"startday.index":              0,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.3,
"normal.mortality": 0.1485222040695 
},
{
 "quarter": "Nyboder",
"startday.index":              7,
"mensick.week": 3,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 3,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.7,
"normal.mortality": 0.4455666122085 
},
{
 "quarter": "Nyboder",
"startday.index":             14,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 2,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.4,
"normal.mortality": 0.297044408139 
},
{
 "quarter": "Nyboder",
"startday.index":             21,
"mensick.week": 5,
"mendead.week": 5,
"womensick.week": 8,
"womendead.week": 7,
"sick.total.week": 13,
"dead.total.week": 12,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            1.9,
"normal.mortality": 1.782266448834 
},
{
 "quarter": "Nyboder",
"startday.index":             28,
"mensick.week": 45,
"mendead.week": 33,
"womensick.week": 62,
"womendead.week": 47,
"sick.total.week": 107,
"dead.total.week": 80,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":           15.9,
"normal.mortality": 11.88177632556 
},
{
 "quarter": "Nyboder",
"startday.index":             35,
"mensick.week": 65,
"mendead.week": 50,
"womensick.week": 102,
"womendead.week": 76,
"sick.total.week": 167,
"dead.total.week": 126,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":           24.8,
"normal.mortality": 18.71379771276 
},
{
 "quarter": "Nyboder",
"startday.index":             42,
"mensick.week": 51,
"mendead.week": 37,
"womensick.week": 63,
"womendead.week": 50,
"sick.total.week": 114,
"dead.total.week": 87,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":           16.9,
"normal.mortality": 12.92143175405 
},
{
 "quarter": "Nyboder",
"startday.index":             49,
"mensick.week": 42,
"mendead.week": 21,
"womensick.week": 49,
"womendead.week": 31,
"sick.total.week": 91,
"dead.total.week": 52,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":           13.5,
"normal.mortality": 7.723154611614 
},
{
 "quarter": "Nyboder",
"startday.index":             56,
"mensick.week": 14,
"mendead.week": 10,
"womensick.week": 14,
"womendead.week": 7,
"sick.total.week": 28,
"dead.total.week": 17,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            4.2,
"normal.mortality": 2.524877469182 
},
{
 "quarter": "Nyboder",
"startday.index":             63,
"mensick.week": 7,
"mendead.week": 2,
"womensick.week": 6,
"womendead.week": 1,
"sick.total.week": 13,
"dead.total.week": 3,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            1.9,
"normal.mortality": 0.4455666122085 
},
{
 "quarter": "Nyboder",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 5,
"womendead.week": 3,
"sick.total.week": 8,
"dead.total.week": 5,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            1.2,
"normal.mortality": 0.7426110203475 
},
{
 "quarter": "Nyboder",
"startday.index":             77,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 2,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.4,
"normal.mortality": 0.297044408139 
},
{
 "quarter": "Nyboder",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.1,
"normal.mortality": 0.1485222040695 
},
{
 "quarter": "Nyboder",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":            0.1,
"normal.mortality": 0.1485222040695 
},
{
 "quarter": "Nyboder",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Nyboder",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 6733,
"pop1850": 7888,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Oester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Oester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Oester",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 3,
"dead.total.week": 2,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            0.3,
"normal.mortality": 0.2322610614331 
},
{
 "quarter": "Oester",
"startday.index":             21,
"mensick.week": 5,
"mendead.week": 2,
"womensick.week": 6,
"womendead.week": 5,
"sick.total.week": 11,
"dead.total.week": 7,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            1.3,
"normal.mortality": 0.8129137150157 
},
{
 "quarter": "Oester",
"startday.index":             28,
"mensick.week": 12,
"mendead.week": 9,
"womensick.week": 19,
"womendead.week": 11,
"sick.total.week": 31,
"dead.total.week": 20,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            3.6,
"normal.mortality": 2.322610614331 
},
{
 "quarter": "Oester",
"startday.index":             35,
"mensick.week": 24,
"mendead.week": 18,
"womensick.week": 61,
"womendead.week": 35,
"sick.total.week": 85,
"dead.total.week": 53,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            9.9,
"normal.mortality": 6.154918127976 
},
{
 "quarter": "Oester",
"startday.index":             42,
"mensick.week": 25,
"mendead.week": 13,
"womensick.week": 41,
"womendead.week": 25,
"sick.total.week": 66,
"dead.total.week": 38,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            7.7,
"normal.mortality": 4.412960167228 
},
{
 "quarter": "Oester",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 15,
"dead.total.week": 9,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            1.7,
"normal.mortality": 1.045174776449 
},
{
 "quarter": "Oester",
"startday.index":             56,
"mensick.week": 10,
"mendead.week": 6,
"womensick.week": 16,
"womendead.week": 10,
"sick.total.week": 26,
"dead.total.week": 16,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":              3,
"normal.mortality": 1.858088491464 
},
{
 "quarter": "Oester",
"startday.index":             63,
"mensick.week": 7,
"mendead.week": 5,
"womensick.week": 4,
"womendead.week": 2,
"sick.total.week": 11,
"dead.total.week": 7,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            1.3,
"normal.mortality": 0.8129137150157 
},
{
 "quarter": "Oester",
"startday.index":             70,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 7,
"womendead.week": 2,
"sick.total.week": 9,
"dead.total.week": 3,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":              1,
"normal.mortality": 0.3483915921496 
},
{
 "quarter": "Oester",
"startday.index":             77,
"mensick.week": 4,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 2,
"sick.total.week": 6,
"dead.total.week": 4,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            0.7,
"normal.mortality": 0.4645221228661 
},
{
 "quarter": "Oester",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            0.2,
"normal.mortality": 0.1161305307165 
},
{
 "quarter": "Oester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "Oester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Oester",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 8611,
"pop1850": 8465,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "Rosenborg",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Rosenborg",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 3,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            0.3,
"normal.mortality": 0.09824147755182 
},
{
 "quarter": "Rosenborg",
"startday.index":             14,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 12,
"womendead.week": 5,
"sick.total.week": 18,
"dead.total.week": 8,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            1.8,
"normal.mortality": 0.7859318204146 
},
{
 "quarter": "Rosenborg",
"startday.index":             21,
"mensick.week": 4,
"mendead.week": 3,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 11,
"dead.total.week": 6,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            1.1,
"normal.mortality": 0.5894488653109 
},
{
 "quarter": "Rosenborg",
"startday.index":             28,
"mensick.week": 25,
"mendead.week": 16,
"womensick.week": 7,
"womendead.week": 5,
"sick.total.week": 32,
"dead.total.week": 21,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            3.1,
"normal.mortality": 2.063071028588 
},
{
 "quarter": "Rosenborg",
"startday.index":             35,
"mensick.week": 23,
"mendead.week": 14,
"womensick.week": 28,
"womendead.week": 17,
"sick.total.week": 51,
"dead.total.week": 31,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":              5,
"normal.mortality": 3.045485804106 
},
{
 "quarter": "Rosenborg",
"startday.index":             42,
"mensick.week": 40,
"mendead.week": 23,
"womensick.week": 37,
"womendead.week": 20,
"sick.total.week": 77,
"dead.total.week": 43,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            7.6,
"normal.mortality": 4.224383534728 
},
{
 "quarter": "Rosenborg",
"startday.index":             49,
"mensick.week": 31,
"mendead.week": 21,
"womensick.week": 41,
"womendead.week": 29,
"sick.total.week": 72,
"dead.total.week": 50,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            7.1,
"normal.mortality": 4.912073877591 
},
{
 "quarter": "Rosenborg",
"startday.index":             56,
"mensick.week": 20,
"mendead.week": 10,
"womensick.week": 19,
"womendead.week": 9,
"sick.total.week": 39,
"dead.total.week": 19,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            3.8,
"normal.mortality": 1.866588073485 
},
{
 "quarter": "Rosenborg",
"startday.index":             63,
"mensick.week": 11,
"mendead.week": 2,
"womensick.week": 20,
"womendead.week": 12,
"sick.total.week": 31,
"dead.total.week": 14,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":              3,
"normal.mortality": 1.375380685726 
},
{
 "quarter": "Rosenborg",
"startday.index":             70,
"mensick.week": 11,
"mendead.week": 8,
"womensick.week": 10,
"womendead.week": 10,
"sick.total.week": 21,
"dead.total.week": 18,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            2.1,
"normal.mortality": 1.768346595933 
},
{
 "quarter": "Rosenborg",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 4,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            0.5,
"normal.mortality": 0.3929659102073 
},
{
 "quarter": "Rosenborg",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            0.2,
"normal.mortality": 0.1964829551036 
},
{
 "quarter": "Rosenborg",
"startday.index":             91,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 2,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":            0.4,
"normal.mortality": 0.1964829551036 
},
{
 "quarter": "Rosenborg",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Rosenborg",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 10179,
"pop1850": 10266,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":             14,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 2,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            0.6,
"normal.mortality": 0.4196391103651 
},
{
 "quarter": "Snarens",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":             28,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            0.2,
"normal.mortality": 0.2098195551825 
},
{
 "quarter": "Snarens",
"startday.index":             35,
"mensick.week": 5,
"mendead.week": 1,
"womensick.week": 10,
"womendead.week": 4,
"sick.total.week": 15,
"dead.total.week": 5,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            3.1,
"normal.mortality": 1.049097775913 
},
{
 "quarter": "Snarens",
"startday.index":             42,
"mensick.week": 35,
"mendead.week": 28,
"womensick.week": 25,
"womendead.week": 18,
"sick.total.week": 60,
"dead.total.week": 46,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":           12.6,
"normal.mortality": 9.651699538397 
},
{
 "quarter": "Snarens",
"startday.index":             49,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 9,
"womendead.week": 4,
"sick.total.week": 15,
"dead.total.week": 8,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            3.1,
"normal.mortality":  1.67855644146 
},
{
 "quarter": "Snarens",
"startday.index":             56,
"mensick.week": 3,
"mendead.week": 3,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 10,
"dead.total.week": 6,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            2.1,
"normal.mortality": 1.258917331095 
},
{
 "quarter": "Snarens",
"startday.index":             63,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 3,
"womendead.week": 2,
"sick.total.week": 5,
"dead.total.week": 3,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              1,
"normal.mortality": 0.6294586655476 
},
{
 "quarter": "Snarens",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            0.6,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 1,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            0.8,
"normal.mortality": 0.2098195551825 
},
{
 "quarter": "Snarens",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Snarens",
"startday.index":             91,
"mensick.week": 6,
"mendead.week": 2,
"womensick.week": 3,
"womendead.week": 0,
"sick.total.week": 9,
"dead.total.week": 2,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            1.9,
"normal.mortality": 0.4196391103651 
},
{
 "quarter": "Snarens",
"startday.index":             98,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":            0.4,
"normal.mortality": 0.4196391103651 
},
{
 "quarter": "Snarens",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 4766,
"pop1850": 4536,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":              0,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":              7,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.2,
"normal.mortality": 0.07932730445819 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             14,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 2,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.2,
"normal.mortality": 0.1586546089164 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             21,
"mensick.week": 10,
"mendead.week": 7,
"womensick.week": 10,
"womendead.week": 7,
"sick.total.week": 20,
"dead.total.week": 14,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            1.6,
"normal.mortality": 1.110582262415 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             28,
"mensick.week": 74,
"mendead.week": 53,
"womensick.week": 74,
"womendead.week": 57,
"sick.total.week": 148,
"dead.total.week": 110,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":           11.7,
"normal.mortality": 8.726003490401 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             35,
"mensick.week": 83,
"mendead.week": 54,
"womensick.week": 98,
"womendead.week": 54,
"sick.total.week": 181,
"dead.total.week": 108,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":           14.4,
"normal.mortality": 8.567348881485 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             42,
"mensick.week": 32,
"mendead.week": 24,
"womensick.week": 44,
"womendead.week": 27,
"sick.total.week": 76,
"dead.total.week": 51,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":              6,
"normal.mortality": 4.045692527368 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             49,
"mensick.week": 9,
"mendead.week": 6,
"womensick.week": 13,
"womendead.week": 9,
"sick.total.week": 22,
"dead.total.week": 15,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            1.7,
"normal.mortality": 1.189909566873 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             56,
"mensick.week": 6,
"mendead.week": 5,
"womensick.week": 9,
"womendead.week": 6,
"sick.total.week": 15,
"dead.total.week": 11,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            1.2,
"normal.mortality": 0.8726003490401 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             63,
"mensick.week": 6,
"mendead.week": 5,
"womensick.week": 7,
"womendead.week": 3,
"sick.total.week": 13,
"dead.total.week": 8,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":              1,
"normal.mortality": 0.6346184356656 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.2,
"normal.mortality": 0.07932730445819 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             77,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.2,
"normal.mortality": 0.07932730445819 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             84,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 0,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Oester",
"startday.index":            105,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 12606,
"pop1850": 10884,
"normal.incidence":            0.1,
"normal.mortality": 0.07932730445819 
},
{
 "quarter": "St. Annae Vester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":              0,
"normal.mortality": 0.03830977282305 
},
{
 "quarter": "St. Annae Vester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.1,
"normal.mortality": 0.03830977282305 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             14,
"mensick.week": 17,
"mendead.week": 12,
"womensick.week": 19,
"womendead.week": 1,
"sick.total.week": 36,
"dead.total.week": 13,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            1.4,
"normal.mortality": 0.4980270466996 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             21,
"mensick.week": 61,
"mendead.week": 47,
"womensick.week": 65,
"womendead.week": 47,
"sick.total.week": 126,
"dead.total.week": 94,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            4.8,
"normal.mortality": 3.601118645366 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             28,
"mensick.week": 132,
"mendead.week": 96,
"womensick.week": 162,
"womendead.week": 109,
"sick.total.week": 294,
"dead.total.week": 205,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":           11.3,
"normal.mortality": 7.853503428725 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             35,
"mensick.week": 171,
"mendead.week": 108,
"womensick.week": 252,
"womendead.week": 151,
"sick.total.week": 423,
"dead.total.week": 259,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":           16.2,
"normal.mortality": 9.922231161169 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             42,
"mensick.week": 151,
"mendead.week": 93,
"womensick.week": 201,
"womendead.week": 127,
"sick.total.week": 352,
"dead.total.week": 220,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":           13.5,
"normal.mortality":  8.42815002107 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             49,
"mensick.week": 72,
"mendead.week": 44,
"womensick.week": 86,
"womendead.week": 46,
"sick.total.week": 158,
"dead.total.week": 90,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            6.1,
"normal.mortality": 3.447879554074 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             56,
"mensick.week": 30,
"mendead.week": 18,
"womensick.week": 42,
"womendead.week": 21,
"sick.total.week": 72,
"dead.total.week": 39,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            2.8,
"normal.mortality": 1.494081140099 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             63,
"mensick.week": 13,
"mendead.week": 8,
"womensick.week": 26,
"womendead.week": 8,
"sick.total.week": 39,
"dead.total.week": 16,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            1.5,
"normal.mortality": 0.6129563651688 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             70,
"mensick.week": 6,
"mendead.week": 3,
"womensick.week": 5,
"womendead.week": 0,
"sick.total.week": 11,
"dead.total.week": 3,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.4,
"normal.mortality": 0.1149293184691 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             77,
"mensick.week": 6,
"mendead.week": 4,
"womensick.week": 4,
"womendead.week": 0,
"sick.total.week": 10,
"dead.total.week": 4,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.4,
"normal.mortality": 0.1532390912922 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 0,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.1,
"normal.mortality":              0 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.1,
"normal.mortality": 0.03830977282305 
},
{
 "quarter": "St. Annae Vester",
"startday.index":             98,
"mensick.week": 2,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 3,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":            0.2,
"normal.mortality": 0.1149293184691 
},
{
 "quarter": "St. Annae Vester",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 1,
"pop1855": 26103,
"pop1850": 22483,
"normal.incidence":              0,
"normal.mortality": 0.03830977282305 
},
{
 "quarter": "Strand",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             21,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             28,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 3,
"dead.total.week": 1,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            1.2,
"normal.mortality": 0.395256916996 
},
{
 "quarter": "Strand",
"startday.index":             35,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            1.2,
"normal.mortality": 0.395256916996 
},
{
 "quarter": "Strand",
"startday.index":             42,
"mensick.week": 4,
"mendead.week": 4,
"womensick.week": 4,
"womendead.week": 1,
"sick.total.week": 8,
"dead.total.week": 5,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            3.2,
"normal.mortality":  1.97628458498 
},
{
 "quarter": "Strand",
"startday.index":             49,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            0.8,
"normal.mortality": 0.395256916996 
},
{
 "quarter": "Strand",
"startday.index":             56,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 2,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            0.8,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             63,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             70,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 1,
"womendead.week": 1,
"sick.total.week": 2,
"dead.total.week": 1,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":            0.8,
"normal.mortality": 0.395256916996 
},
{
 "quarter": "Strand",
"startday.index":             77,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             84,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             91,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Strand",
"startday.index":            105,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 2530,
"pop1850": 2587,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":              0,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":              7,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":             14,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":             21,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 3,
"womendead.week": 3,
"sick.total.week": 4,
"dead.total.week": 4,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.5,
"normal.mortality": 0.4714201532115 
},
{
 "quarter": "Vester",
"startday.index":             28,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 1,
"womendead.week": 0,
"sick.total.week": 4,
"dead.total.week": 2,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.5,
"normal.mortality": 0.2357100766058 
},
{
 "quarter": "Vester",
"startday.index":             35,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":             42,
"mensick.week": 20,
"mendead.week": 10,
"womensick.week": 23,
"womendead.week": 18,
"sick.total.week": 43,
"dead.total.week": 28,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            5.1,
"normal.mortality": 3.299941072481 
},
{
 "quarter": "Vester",
"startday.index":             49,
"mensick.week": 9,
"mendead.week": 4,
"womensick.week": 15,
"womendead.week": 13,
"sick.total.week": 24,
"dead.total.week": 17,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            2.8,
"normal.mortality": 2.003535651149 
},
{
 "quarter": "Vester",
"startday.index":             56,
"mensick.week": 9,
"mendead.week": 6,
"womensick.week": 9,
"womendead.week": 4,
"sick.total.week": 18,
"dead.total.week": 10,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            2.1,
"normal.mortality": 1.178550383029 
},
{
 "quarter": "Vester",
"startday.index":             63,
"mensick.week": 5,
"mendead.week": 3,
"womensick.week": 6,
"womendead.week": 3,
"sick.total.week": 11,
"dead.total.week": 6,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            1.3,
"normal.mortality": 0.7071302298173 
},
{
 "quarter": "Vester",
"startday.index":             70,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 3,
"womendead.week": 2,
"sick.total.week": 6,
"dead.total.week": 4,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.7,
"normal.mortality": 0.4714201532115 
},
{
 "quarter": "Vester",
"startday.index":             77,
"mensick.week": 3,
"mendead.week": 2,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 5,
"dead.total.week": 3,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.6,
"normal.mortality": 0.3535651149087 
},
{
 "quarter": "Vester",
"startday.index":             84,
"mensick.week": 2,
"mendead.week": 1,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 4,
"dead.total.week": 2,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.5,
"normal.mortality": 0.2357100766058 
},
{
 "quarter": "Vester",
"startday.index":             91,
"mensick.week": 1,
"mendead.week": 0,
"womensick.week": 2,
"womendead.week": 1,
"sick.total.week": 3,
"dead.total.week": 1,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.4,
"normal.mortality": 0.1178550383029 
},
{
 "quarter": "Vester",
"startday.index":             98,
"mensick.week": 0,
"mendead.week": 0,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 0,
"dead.total.week": 0,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":              0,
"normal.mortality":              0 
},
{
 "quarter": "Vester",
"startday.index":            105,
"mensick.week": 1,
"mendead.week": 1,
"womensick.week": 0,
"womendead.week": 0,
"sick.total.week": 1,
"dead.total.week": 1,
"pop1855": 8485,
"pop1850": 8485,
"normal.incidence":            0.1,
"normal.mortality": 0.1178550383029 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        chart.xAxis
  .axisLabel("Day Index")
  .width(    90)

        
        
        chart.yAxis
  .axisLabel("Number infected per 100 people")
  .width(    40)
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
      
      //add our title with html
      //might be better with svg
      d3.select("#" + opts.id).insert("h3","svg")
        .text(opts.title);
        //if desired, could change styling with css or with d3
        //some examples here http://tympanus.net/codrops/2012/11/02/heading-set-styling-with-css/
        //will use example
        //.style("float","right");
        //.style("text-shadow", "0 -1px 1px rgba(0,0,0,0.4)")
        //.style("font-size","22px")
        //.style("line-height", "40px")
        //.style("color", "#355681")
        //.style("ext-transform", "uppercase")
        //.style("border-bottom", "1px solid rgba(53,86,129, 0.3)");
    };
</script>


--- .class1 #id




![alt text](https://raw.githubusercontent.com/matthew-phelps/Presentations/master/cph_map_contour.png)


