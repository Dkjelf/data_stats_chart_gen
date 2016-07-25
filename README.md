# data_stats_chart_gen


Chart Generation Documentation

Charts are generated using the Google Charts toolkit. The data for the chart is obtained from the build-stats repository by AidData-WM. The specific file referenced is build_stats.json .   
To generate a new graph, copy the chart_gen generic file into a new file. Then, all that needs to be changed is the datasetName variable at the very top of the file. Change that variable to the name in the JSON file and it should display the new data. 

To add an iframe to the window:  
< iframe src="http://rawgit.com/Dkjelf/data_stats_chart_gen/master/ [CHARTNAME HERE].html" seamless width ="980" height = "275" scrolling= "no"> </iframe></p>    


Add this to each of the block segments or anywhere you want the graph.  
The chartname is the filename in this repo.
