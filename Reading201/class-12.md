# setting up

setting up you'll need to make sure you reference the chart in your script code for example <!-- <script src='Chart.min.js'></script> --> then you would create the canvas id giving it a width then height. Create the script to retrieve the context of the canvas. Create the script to create an object holding the labels for the base and datasets to describe the values. ex = 

var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

Path methods
Methods to set different paths for objects.

closePath()
Adds a straight line to the path, going to the start of the current sub-path.

stroke()
Draws the shape by stroking its outline.

fill()
Draws a solid shape by filling the path's content area

this can be used to draw a path on the canvas. When drawing paths, inside the function you can curve lines. Text can be styled and colored as well.