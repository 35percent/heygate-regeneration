---
title: Overall loss
date: 2019-12-15 00:00:00 -0700
---
Government statistics show that Southwark has lost over 13,000 council homes since the commencement of its estate regeneration initiatives.


<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script src="http://code.highcharts.com/highcharts.js">
</script>
<script src="http://code.highcharts.com/modules/exporting.js">
</script>

<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">
</div>

<script type="text/javascript">

        $('#container').highcharts({
            title: {
                text: "Southwark's Council Homes",
                x: -20 //center
            },
            subtitle: {
                text: 'Source: <a href="https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx">https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx</a>',
		x: -20
            },
            xAxis: {
                categories: ['1999', '2000', '2001', '2002', '2003', '2004', '2005', '2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015', '2016', '2017', '2018']
            },
            yAxis: {
                title: {
                    text: 'Council-owned stock'
                },
                plotLines: [{
                    value: 0,
                    width: 1,
                    color: '#808080'
                }]
            },
            tooltip: {
                valueSuffix: ' Council homes'
            },
            legend: {
                layout: 'vertical',
                align: 'right',
                verticalAlign: 'middle',
                borderWidth: 0
            },
            series: [{
                name: 'Southwark',
                data: [51706, 50903, 49875, 48052, 46887, 45346, 43885, 42275, 41873, 41287, 40618, 40120, 39845, 39781, 38578, 39029, 38687, 38522, 38553, 38489]
            }]
        });

</script>

Approximately half of these are down to estate demolitions and half due to Right to Buy [source].

[Source: http://www.gov.uk](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/674346/LT_116.xlsx)
