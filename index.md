
<link href="assets/css/style.scss" rel="stylesheet">

## Welcome to the Compound Eye Tracing Project Website.

Reconstructing the structure of compound eyes of flies is fundamental to understanding their vision system and flight behavior. Recent development of  2-photon imaging techniques has allowed us to capture high resolution 3D images of the fovea regions of robber flies (Holcocephala Fusca) and learn about  ([Wardill '2017](https://www.cell.com/current-biology/pdf/S0960-9822(17)30085-4.pdf)). However, the reconstruction of the individual lenses of the eye is performed through manual annotation which is highly time consuming and challenging due to the low visibility under certain angles. The goal of the Compound Eye Tracing Project is to build automatic pipelines for image processing of the 3D stacks which output the boundaries of the individual lenses and allow to perform further statistics on the patterns in the eye structure. Peek into the robber fly's eye with the interactive visualizations below.




### Slice Visualization

<div id="contentframe" style="position:relative; top: 160px; left:50px;"> </div>
<iframe src="https://valentina-s.github.io/volumeJS/index.html" height="600" width="800" allowfullscreen="allowfullscreen"> </iframe>



### Volume Visualization

<div id="contentframe" style="position:relative; top: 500px; left:50px; bottom:100px"> </div>
<iframe src="https://valentina-s.github.io/WebGLVolumeRendering/Index_eye.html" height="600" width="800" allowfullscreen="allowfullscreen"> </iframe>
<br/>

We extract a mesh representing the boundaries of the lenses using a sequence of image and graph processing steps. 

### Lens Structure Visualization

<div id="contentframe" style="position:relative; top: 500px; left:50px; bottom:100px"> </div>
<iframe src="https://plot.ly/~vms/195.embed" height="600" width="800" allowfullscreen="allowfullscreen"> </iframe>
<br/>



