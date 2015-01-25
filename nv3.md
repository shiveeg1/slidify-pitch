---

title : Rankers
subtitle : A result analysis App
author : Shivee Pradeep Gupta
job :
framework : io2012 # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js # {highlight.js, prettify, highlight}
hitheme : tomorrow #
ext_widgets : {rCharts: ["libraries/highcharts", "libraries/nvd3", "libraries/morris","libraries/mathjax"]} # {mathjax, quiz, bootstrap}
mode : selfcontained # {standalone, draft}
---

## What it does ?
Gives you the following analysis for your entered score:-
<ul><li>Percentile</li>
<li>Student above your score</li>
<li>Students below your score</li>
<li>Number of backlog Students</li></ul>
---
You can choose from following three departments:-
<ul><li>Entc</li>
<li>IT</li>
<li>Comp</li></ul>

---

## Percentile Graph
 

 

<div id = 'chart3' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart3()
    });
    function drawchart3(){  
      var opts = {
 "dom": "chart3",
"width":    800,
"height":    400,
"x": "pass",
"y": "n",
"type": "lineChart",
"id": "chart3" 
},
        data = [
 {
 "pass": "354",
"n": 1 
},
{
 "pass": "361",
"n": 2 
},
{
 "pass": "377",
"n": 3 
},
{
 "pass": "382",
"n": 5 
},
{
 "pass": "382",
"n": 5 
},
{
 "pass": "389",
"n": 6 
},
{
 "pass": "399",
"n": 7 
},
{
 "pass": "400",
"n": 8 
},
{
 "pass": "402",
"n": 9 
},
{
 "pass": "403",
"n": 10 
},
{
 "pass": "405",
"n": 11 
},
{
 "pass": "411",
"n": 12 
},
{
 "pass": "414",
"n": 13 
},
{
 "pass": "416",
"n": 14 
},
{
 "pass": "417",
"n": 15 
},
{
 "pass": "421",
"n": 17 
},
{
 "pass": "421",
"n": 17 
},
{
 "pass": "422",
"n": 18 
},
{
 "pass": "423",
"n": 20 
},
{
 "pass": "423",
"n": 20 
},
{
 "pass": "426",
"n": 21 
},
{
 "pass": "427",
"n": 23 
},
{
 "pass": "427",
"n": 23 
},
{
 "pass": "431",
"n": 25 
},
{
 "pass": "431",
"n": 25 
},
{
 "pass": "435",
"n": 26 
},
{
 "pass": "437",
"n": 27 
},
{
 "pass": "438",
"n": 29 
},
{
 "pass": "438",
"n": 29 
},
{
 "pass": "440",
"n": 30 
},
{
 "pass": "441",
"n": 31 
},
{
 "pass": "442",
"n": 32 
},
{
 "pass": "444",
"n": 34 
},
{
 "pass": "444",
"n": 34 
},
{
 "pass": "445",
"n": 36 
},
{
 "pass": "445",
"n": 36 
},
{
 "pass": "446",
"n": 37 
},
{
 "pass": "448",
"n": 39 
},
{
 "pass": "448",
"n": 39 
},
{
 "pass": "450",
"n": 40 
},
{
 "pass": "451",
"n": 41 
},
{
 "pass": "453",
"n": 42 
},
{
 "pass": "456",
"n": 43 
},
{
 "pass": "457",
"n": 44 
},
{
 "pass": "458",
"n": 45 
},
{
 "pass": "459",
"n": 46 
},
{
 "pass": "460",
"n": 48 
},
{
 "pass": "460",
"n": 48 
},
{
 "pass": "461",
"n": 50 
},
{
 "pass": "461",
"n": 50 
},
{
 "pass": "462",
"n": 52 
},
{
 "pass": "462",
"n": 52 
},
{
 "pass": "463",
"n": 53 
},
{
 "pass": "464",
"n": 54 
},
{
 "pass": "465",
"n": 55 
},
{
 "pass": "466",
"n": 56 
},
{
 "pass": "467",
"n": 58 
},
{
 "pass": "467",
"n": 58 
},
{
 "pass": "468",
"n": 60 
},
{
 "pass": "468",
"n": 60 
},
{
 "pass": "475",
"n": 63 
},
{
 "pass": "475",
"n": 63 
},
{
 "pass": "475",
"n": 63 
},
{
 "pass": "476",
"n": 64 
},
{
 "pass": "477",
"n": 67 
},
{
 "pass": "477",
"n": 67 
},
{
 "pass": "477",
"n": 67 
},
{
 "pass": "478",
"n": 68 
},
{
 "pass": "479",
"n": 69 
},
{
 "pass": "480",
"n": 70 
},
{
 "pass": "481",
"n": 71 
},
{
 "pass": "482",
"n": 72 
},
{
 "pass": "483",
"n": 73 
},
{
 "pass": "484",
"n": 75 
},
{
 "pass": "484",
"n": 75 
},
{
 "pass": "485",
"n": 76 
},
{
 "pass": "487",
"n": 77 
},
{
 "pass": "488",
"n": 80 
},
{
 "pass": "488",
"n": 80 
},
{
 "pass": "488",
"n": 80 
},
{
 "pass": "490",
"n": 81 
},
{
 "pass": "491",
"n": 82 
},
{
 "pass": "492",
"n": 84 
},
{
 "pass": "492",
"n": 84 
},
{
 "pass": "493",
"n": 85 
},
{
 "pass": "495",
"n": 87 
},
{
 "pass": "495",
"n": 87 
},
{
 "pass": "497",
"n": 89 
},
{
 "pass": "497",
"n": 89 
},
{
 "pass": "502",
"n": 91 
},
{
 "pass": "502",
"n": 91 
},
{
 "pass": "503",
"n": 92 
},
{
 "pass": "506",
"n": 94 
},
{
 "pass": "506",
"n": 94 
},
{
 "pass": "509",
"n": 95 
},
{
 "pass": "510",
"n": 96 
},
{
 "pass": "513",
"n": 97 
},
{
 "pass": "514",
"n": 98 
},
{
 "pass": "515",
"n": 99 
},
{
 "pass": "516",
"n": 100 
},
{
 "pass": "518",
"n": 101 
},
{
 "pass": "520",
"n": 102 
},
{
 "pass": "521",
"n": 103 
},
{
 "pass": "522",
"n": 104 
},
{
 "pass": "523",
"n": 106 
},
{
 "pass": "523",
"n": 106 
},
{
 "pass": "525",
"n": 107 
},
{
 "pass": "527",
"n": 108 
},
{
 "pass": "528",
"n": 109 
},
{
 "pass": "529",
"n": 110 
},
{
 "pass": "531",
"n": 111 
},
{
 "pass": "534",
"n": 112 
},
{
 "pass": "535",
"n": 113 
},
{
 "pass": "538",
"n": 114 
},
{
 "pass": "539",
"n": 115 
},
{
 "pass": "546",
"n": 118 
},
{
 "pass": "546",
"n": 118 
},
{
 "pass": "546",
"n": 118 
},
{
 "pass": "551",
"n": 119 
},
{
 "pass": "552",
"n": 120 
},
{
 "pass": "556",
"n": 121 
},
{
 "pass": "557",
"n": 122 
},
{
 "pass": "568",
"n": 123 
},
{
 "pass": "576",
"n": 124 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>
<p><center> Graphical representation of the student's percentile</center></p>
<ul><li>X-axis : Total score acquired</li>
<li> Y-axis : Number of students below that score</li>

---

## The Mathematics involved

<br></br><p>The percentile formula is as follows:</p>
$$latex
percentile = \frac{Number\ of\ students\ below\ the\ score}{Total\ number\ of\ students}
$$

<br><p>The code implementation is as follows:</p>
<p><center> 
percentile[i]= sum(sorted_list_of_scores <= sorted_list_of_scores[i])
<center></p> 

---

## Salient Features

To the geeks (like me ) who give a damn...
<br>This is a :<br>
<ul><li> A self explanatory interactive application with dynamic responses</li>
<li> Modular code </li>
<li> All data is read from files thus making the application extensible</li>
<li> The file names are a list and thus easily refactorable </li>
</ul> 
---

And finally...<br>
<a href = "https://github.com/shiveeg1/Result-Analysis">link to application code on github </a>

<a href = " http://shiveegupta.shinyapps.io/rankers">link to the application on shinyapps.io</a>
<center>Thank You.</center>
















