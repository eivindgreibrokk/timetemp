# timetemp
Temperature graph like this: https://zoomcharts.com/developers/en/time-chart/examples/series/line.html
or this: http://www.humblesoftware.com/finance/index

Raspberry PI polls temperature sensors every 10 minutes, and saves them to a file on Dolly, which is NFS mounted.
Temperature files are made available for the graph API using Apache.
