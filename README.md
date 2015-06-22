<html>
<head>
<title>Crime records of GUJRAT</title>
<script type="text/javascript" src="fusioncharts/fusioncharts.js"></script>
<script type="text/javascript" src="fusioncharts/themes/fusioncharts.theme.zune.js"></script>
<script type="text/javascript">
FusionCharts.ready(function(){
  var murderChart = new FusionCharts({
      "type": "mscolumnline3d",
      "renderAt": "murderContainer",
      "width": "60%",
      "height": "50%",
      "dataFormat": "json",
      "dataSource": {
        "chart": {
          "showvalues": "1",
          "caption": "Victims of Murder",
          "xaxisname": "Age Group",
          "yaxisname": "No.of Victims",
          "showBorder": "0",
          "paletteColors": "#0075c2,#1aaf5d,#f2c500",
          "bgColor": "#ffffff",
          "canvasBgColor": "#ffffff",
          "captionFontSize": "14",
          "subcaptionFontSize": "14",
          "subcaptionFontBold": "0",
          "divlineColor": "#999999",
          "divLineIsDashed": "1",
          "divLineDashLen": "1",
          "divLineGapLen": "1",
          "toolTipColor": "#ffffff",
          "toolTipBorderThickness": "0",
          "toolTipBgColor": "#000000",
          "toolTipBgAlpha": "80",
          "toolTipBorderRadius": "2",
          "toolTipPadding": "5",
          "legendBgColor": "#ffffff",
          "legendBorderAlpha": "0",
          "legendShadow": "0",
          "legendItemFontSize": "10",
          "legendItemFontColor": "#666666"
        },
        "categories": [
          {
              "category": [
                {
                    "label": "<10"
                },
                {
                    "label": "10-15"
                },
                {
                    "label": "15-18"
                },
                {
                    "label": "18-30"
                },
                {
                    "label": "30-50"
                },
                {
                    "label": ">50"
                }
              ]
          }
        ],
        "dataset": [
          {
            "seriesname": "Male",
            "data": [
                 {
                            "value": "34"
                        },
                        {
                            "value": "2"
                        },
                        {
                            "value": "6"
                        },
                        {
                            "value": "292"
                        },
                        {
                            "value": "326"
                        },
                        {
                            "value": "126"
                        }
                        
                    ]
                },
                {
                    "seriesname": "female",
                    "data": [
                        {
                            "value": "43"
                        },
                        {
                            "value": "8"
                        },
                        {
                            "value": "4"
                        },
                        {
                            "value": "148"
                        },
                        {
                            "value": "126"
                        },
                        {
                            "value": "47"
                        }
            ]
          },
          {
            "seriesname": "Total",
            "renderAs": "Line",
            "data": [
                {
                    "value": "77"
                },
                {
                    "value": "10"
                },
                {
                    "value": "10"
                },
                {
                    "value": "440"
                },
                {
                    "value": "452"
                },
                {
                    "value": "173"
                }
            ]
          }
        ]
      }
  });
  var gaugesChart = new FusionCharts({
        "type": "angulargauge",
        "renderAt": "gauge1",
        "width": "30%",
        "height": "50%",
        "dataFormat": "json",
        "dataSource":  {
          "chart": {
            "caption": "Murder",
            "manageresize": "1",
            "origw": "300",
            "origh": "300",
            "palette": "3",
            "bgcolor": "333333, 453243",
            "bgalpha": "10",
            "lowerlimit": "0",
            "upperlimit": "1500",
            "gaugestartangle": "240",
            "gaugeendangle": "-60",
            "gaugeouterradius": "120",
            "gaugeinnerradius": "60%",
            "gaugefillmix": "{light-10},{light-30},{light-20},{dark-5},{color},{light-30},{light-20},{dark-10}",
            "gaugefillratio": "",
            "basefontcolor": "222222",
            "tooltipbgcolor": "eeeeee",
            "tooltipbordercolor": "333333",
            "decimals": "1",
            "gaugeoriginx": "150",
            "gaugeoriginy": "150",
            "showborder": "0"
          },
          "colorrange": {
            "color": [
                {
                    "minvalue": "0",
                    "maxvalue": "500"
                },
                {
                    "minvalue": "500",
                    "maxvalue": "1000"
                },
                {
                    "minvalue": "1000",
                    "maxvalue": "1500"
                }
            ]
          },
          "dials": {
            "dial": [
                {
                    "id": "Male",
                    "value": "786",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "150",
                    "valueY": "90",
                    "tooltext": "Male Murder : $value",
                    "bgColor": "108567",
                    "valueFont": "Arial",
                    "valueFontSize": "20",
                    "valueFontColor": "FFFFFF",
                    "valueFontBold": "1"
                },
                {
                    "id": "Female",
                    "value": "376",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "rearextension": "10",
                    "showvalue": "1",
                    "valueX": "110",
                    "valueY": "140",
                    "tooltext": "Female Murder : $value",
                    "bgColor": "ff3398"
                },
                {
                    "id": "Total",
                    "value": "1162",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "190",
                    "valueY": "110",
                    "tooltext": "Total Murder : $value",
                    "bgColor": "000000"
                }
            ]
          }
        }
  });
  var gaugesChart1 = new FusionCharts({
        "type": "angulargauge",
        "renderAt": "gauge3",
        "width": "30%",
        "height": "50%",
        "dataFormat": "json",
        "dataSource":  {
          "chart": {
            "caption": "Kidnap",
            "manageresize": "1",
            "origw": "300",
            "origh": "300",
            "palette": "3",
            "bgcolor": "333333, 453243",
            "bgalpha": "10",
            "lowerlimit": "0",
            "upperlimit": "3000",
            "gaugestartangle": "240",
            "gaugeendangle": "-60",
            "gaugeouterradius": "120",
            "gaugeinnerradius": "60%",
            "gaugefillmix": "{light-10},{light-30},{light-20},{dark-5},{color},{light-30},{light-20},{dark-10}",
            "gaugefillratio": "",
            "basefontcolor": "222222",
            "tooltipbgcolor": "eeeeee",
            "tooltipbordercolor": "333333",
            "decimals": "1",
            "gaugeoriginx": "150",
            "gaugeoriginy": "150",
            "showborder": "0"
          },
          "colorrange": {
            "color": [
                {
                    "minvalue": "0",
                    "maxvalue": "1000"
                },
                {
                    "minvalue": "1000",
                    "maxvalue": "2000"
                },
                {
                    "minvalue": "2000",
                    "maxvalue": "3000"
                }
            ]
          },
          "dials": {
            "dial": [
                {
                    "id": "Male",
                    "value": "765",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "115",
                    "valueY": "125",
                    "tooltext": "Male Kidnap : $value",
                    "bgColor": "108567",
                    "valueFont": "Arial",
                    "valueFontSize": "20",
                    "valueFontColor": "FFFFFF",
                    "valueFontBold": "1"
                },
                {
                    "id": "Female",
                    "value": "1910",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "rearextension": "10",
                    "showvalue": "1",
                    "valueX": "170",
                    "valueY": "110",
                    "tooltext": "Female Kidnap : $value",
                    "bgColor": "ff3398"
                },
                {
                    "id": "Total",
                    "value": "2675",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "170",
                    "valueY": "160",
                    "tooltext": "Total Kidnap : $value",
                    "bgColor": "000000"
                }
            ]
          }
        }
  });
  var gaugesChart2 = new FusionCharts({
        "type": "angulargauge",
        "renderAt": "gauge2",
        "width": "30%",
        "height": "50%",
        "dataFormat": "json",
        "dataSource":  {
          "chart": {
            "caption": "Rape",
            "manageresize": "1",
            "origw": "300",
            "origh": "300",
            "palette": "2",
            "bgcolor": "333333, 453243",
            "bgalpha": "10",
            "lowerlimit": "0",
            "upperlimit": "1000",
            "gaugestartangle": "240",
            "gaugeendangle": "-60",
            "gaugeouterradius": "120",
            "gaugeinnerradius": "60%",
            "gaugefillmix": "{light-10},{light-30},{light-20},{dark-5},{color},{light-30},{light-20},{dark-10}",
            "gaugefillratio": "",
            "basefontcolor": "222222",
            "tooltipbgcolor": "eeeeee",
            "tooltipbordercolor": "333333",
            "decimals": "1",
            "gaugeoriginx": "150",
            "gaugeoriginy": "150",
            "showborder": "0"
          },
          "colorrange": {
            "color": [
                {
                    "minvalue": "0",
                    "maxvalue": "500"
                },
                {
                    "minvalue": "500",
                    "maxvalue": "1000"
                }
            ]
          },
          "dials": {
            "dial": [
                {
                    "id": "Incest",
                    "value": "17",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "120",
                    "valueY": "175",
                    "tooltext": "Incest Rape : $value",
                    "bgColor": "12fca9",
                    "valueFont": "Arial",
                    "valueFontSize": "60",
                    "valueFontColor": "FFFFFF",
                    "valueFontBold": "1"
                },
                {
                    "id": "Other",
                    "value": "716",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "rearextension": "10",
                    "showvalue": "1",
                    "valueX": "170",
                    "valueY": "100",
                    "tooltext": "Other Rape : $value",
                    "bgColor": "ad6798"
                },
                {
                    "id": "Total",
                    "value": "833",
                    "basewidth": "6",
                    "topwidth": "1",
                    "editmode": "1",
                    "showvalue": "1",
                    "rearextension": "10",
                    "valueX": "180",
                    "valueY": "125",
                    "tooltext": "Total Rape : $value",
                    "bgColor": "000000"
                }
            ]
          }
        }
  });
  var rapeChart = new FusionCharts({
        "type": "column3d",
        "renderAt": "rapeContainer",
        "width": "60%",
        "height": "50%",
        "dataFormat": "json",
        "dataSource":  {
          "chart": {
            "caption": "Victims of Rape Cases",
            "subCaption": "By Age Group",
            "xAxisName": "Age Group",
            "yAxisName": "No. of Victims",
            "yAxisMaxValue":"450",
            "paletteColors": "#0075c2",
           // "valueFontColor": "#ffffff",
            "baseFont": "Helvetica Neue,Arial",
            "captionFontSize": "14",
            "subcaptionFontSize": "14",
            "subcaptionFontBold": "0",
            "placeValuesInside": "0",
            "rotateValues": "0",
            "showShadow": "0",
            "divlineColor": "#999999",
            "divLineDashed": "1",
            "divlineThickness": "1",
            "divLineDashLen": "1",
            "divLineGapLen": "1",
            "canvasBgColor": "#ffffff"
          },
          "data": [
                {
                    "label": "10",
                    "value": "35"
                }, 
                {
                    "label": "10-14",
                    "value": "66"
                }, 
                {
                    "label": "14-18",
                    "value": "164"
                }, 
                {
                    "label": "18-30",
                    "value": "385"
                }, 
                {
                    "label": "30-50",
                    "value": "78"
                }, 
                {
                    "label": ">50",
                    "value": "5"
                } 
                
          ]
        }
  });
  var kidnapChart = new FusionCharts({
      "type": "mscolumn3d",
      "renderAt": "kidnapContainer",
      "width": "60%",
      "height": "50%",
      "dataFormat": "json",
      "dataSource": {
        "chart": {
          "caption": "Victims of Kidnapping & Abduction",
          "subCaption": "By Age Group",
          "xAxisName": "Age Group",
          "yAxisName": "No. of Victims",
          "yAxisMaxValue":"1000",
          "paletteColors": "#0075c2,#1aaf5d,#f2c500",
          "bgColor": "#ffffff",
          "showBorder": "0",
          "showCanvasBorder": "0",
          "usePlotGradientColor": "0",
          "plotBorderAlpha": "10",
          "legendBorderAlpha": "0",
          "legendBgAlpha": "0",
          "legendShadow": "0",
          "showHoverEffect": "1",
         // "valueFontColor": "#ffffff",
          "rotateValues": "0",
          "placeValuesInside": "0",
          "divlineColor": "#999999",
          "divLineDashed": "1",
          "divLineDashLen": "1",
          "divLineGapLen": "1",
          "canvasBgColor": "#ffffff",
          "captionFontSize": "14",
          "subcaptionFontSize": "14",
          "subcaptionFontBold": "0"
        },
        "categories": [
          {
              "category": [
                {
                    "label": "<10"
                },
                {
                    "label": "10-15"
                },
                {
                    "label": "15-18"
                },
                {
                    "label": "18-30"
                },
                {
                    "label": "30-50"
                },
                {
                    "label": ">50"
                }
              ]
          }
        ],
        "dataset": [
          {
            "seriesname": "Male",
            "data": [
                {
                            "value": "24"
                        },
                        {
                            "value": "79"
                        },
                        {
                            "value": "146"
                        },
                        {
                            "value": "385"
                        },
                        {
                            "value": "123"
                        },
                        {
                            "value": "8"
                        }
                        
                    ]
                },
                {
                    "seriesname": "female",
                    "data": [
                        {
                            "value": "21"
                        },
                        {
                            "value": "267"
                        },
                        {
                            "value": "895"
                        },
                        {
                            "value": "698"
                        },
                        {
                            "value": "29"
                        },
                        {
                            "value": "0"
                        }
            ]
          }
        ]
      }
  });
  murderChart.render();
  gaugesChart.render();
  gaugesChart1.render();
  gaugesChart2.render();
  rapeChart.render();
  kidnapChart.render();
})
</script>
</head>
<body>
  <h1 align="center">Crime records of GUJRAT
<!--<div id="murderContainer">Murder will load here!</div>
<div id="gaugesContainer">
  <span id="gauge1">gauge1</span>
  <span id="gauge2">gauge2</span>
  <span id="gauge3">gauge3</span>
</div>
<div id="rapeContainer">Rape will load here!</div>
<div id="kidnapContainer">Kidnap will load here!</div>-->
<!--<div>
  <span id="murderContainer" style="float:left;">Murder will load here!</span>
  <span style="float:right;">
    <span id="gauge1" style="float:left;">gauge1</span>
    <span id="gauge2">gauge2</span>
    <span id="gauge3" style="float:right;">gauge3</span>
  </span>
</div>
<div>
  <span id="rapeContainer" style="float:left;">Rape will load here!</span>
  <span id="kidnapContainer" style="float:right;">Kidnap will load here!</span>
</div>-->
<div>
  <span id="murderContainer" style="float:left;"></span>
  <span id="gauge1" style="float:right;"></span>
</div>
<div>
  <span id="rapeContainer" style="float:left;"></span>
  <span id="gauge2" style="float:right;"></span>
</div>
<div>
  <span id="kidnapContainer" style="float:left;"></span>
  <span id="gauge3" style="float:right;"></span>
</div>
</body>
</html>
