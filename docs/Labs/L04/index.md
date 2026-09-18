# A4 – [Topic]

## Parameter

For this project, I decided to make a tolerance gauge test. This kind of benchmark focuses on extruding a hole and a gauge intended to fit through that hole. Most tests like this take the form of cylinders that are printed or machined to have a slightly smaller diameter than the holes cut in the main part. My tolerance test was designed to be extremely tight and I do not expect all of the "studs" to pass the test. I will be making my tolerances a change in 0.002 in. This tolerance is extreme even for some CNC applications let alone a normal #D printer. The recommended minimum tolerance for a Prusa Core one is 0.3 mm or 0.0012 in.


## Document Design

The design process was simple as this is product only requires a few parts. I began by extruding a rectangle that is 1.5 in x 0.95 in x 0.25 in. The 0.25 in height was to allow for the studs to be significantly larger than the body without using too much material. After the body was made, I cut the tolerance holes in the body. Originally, I wanted to have three circular, three square, and three triangular holes, but managing the triangles proved to be more complex than I intended. I cut three circular holes with equivalent diameters of 0.2 in and sketched 4 squares with side lengths of 0.25 in. I made three of each shape to allow for three steps in tolerance.

<p align="center"> 
  <img width=200" src="sketch.png"/>
  <img width="495" src="extrude.png"/>
  <img width="625" src="cutSketch.png"/>
</p>

Now I designed the different gauges. The first gauge was sketched with a diameter of 0.198 in and was extruded to 0.4 in. The second and third cylinders were sketched with a progressive 0.004 in difference: the second had a diameter of 0.194, the third a diameter of 0.19. As shown in the fourth image below, there is a noticeable gap between the gauge and the body beginning with the second cylinder. 

<p align="center"> 
  <img width=325" src="cyl1Sketch.png"/>
  <img width=350" src="cyl2Sketch.png"/>
  <img width=325" src="cyl3Sketch.png"/>
</p>

<p align="center">
  <img width="500" src="firstCylinder.png"/>
  <img width="500"  src="cylindersTop.png"/>
</p>

To make the square gauges, I sketched lines from the corners of each cut to make a center point for each square. This center point is imperative for making my rectangle cuts. I used the center rectangle function and then set the dimensions of each square after they were sketched. The first rectangle was built with a side length 0.002 in smaller than the cut. In order the square side lengths are: 0.248 in, 0.244 in, 0.24 in. There is a similar pattern in tolerances with the squares. The first being difference of 0.002 in and the subsequent, a difference of 0.004 in.

<p align="center"> 
  <img width="625" src="squarePoint.png"/>
  <br>
  <img width=325" src="square1Sketch.png"/>
  <img width=350" src="square2Sketch2.png"/>
  <img width=325" src="square3Sketch.png"/>
</p>

<p align="center">
  <img width="625" src="squaresDone.png"/>
  <img width="625" src="finalTop.png"/>
</p>

At this point, the CAD modeling was finished. The image right above shows what the final product looked like from an angled view and from a direct top view.


## Preprocessor
In the Prusa Slicer software, Ethan and I chose to use a 10% honeycomb infill. We had previous experience with this infill so we knew it was a reliable choice. For this specific project, the infill was not a necessary part as we were not testing for strength or rigidity. Similarly, we did not use any supports because those would have no visible effect on the tolerance gauge test. There was no need to scale as the CAD model was built to the intended sizes in the parametric software. 

<p align="center">
  <img width="400" src="prusaSlice.png"/>
</p>



## Print Artifact
The print of my model was ultimately a failure. I believe that the tolerances were so low that the Prusa Slicer program overwrote the small gaps. It only attempted to print the largest of the tolerance gauges, but it still failed to print a noticeable separation. Below are the pictures of my print. As seen in the bottom image, the square and cylinder on the bottom have a visible pattern difference while the rest are printed as if there was no gap at all. In this [hyperlink](https://drive.google.com/drive/folders/1_ynZBPD60af9CihB2jIJqgjBs7ZQEdCG?usp=sharing) will be a video of the print while in progress.

<p align="center">
  <img width="400" src="top.png"/>
  <img width="400" src="bottom.png"/>
</p>

## Lessons Learned

I learned a few valuable lessons in this project. The most important was to pay attention to the specific limitations of the tools you use. Those limitations and tolerances are set for a reason, it is not viable to ignore those for important projects. I severely undercut the tolerance limit for the Prusa Core One resulting in a complete failure for my tolerance gauge.

## Resources
[Prusa FAQ including tolerances and limits for Core One printer](https://help.prusa3d.com/article/faq-frequently-asked-questions_1932)
<p align="center">
  <img width="400" src="benchmarks.png"/>
</p>
