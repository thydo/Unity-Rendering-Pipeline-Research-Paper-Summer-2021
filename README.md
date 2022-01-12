# Characterizing Unity Render Pipelines and Visualization Techniques of Point Clouds Data on HoloLens 2
This research paper written under the National Science Foundation sponsored program, [Visual Media Research Experiences for Undergraduate](https://web.asu.edu/imaging-lyceum/visual-media-reu) during Summer 2021.  

## Abstract
The Microsoft HoloLens 2 provides users an interactive
medium to 3D models. In this paper, point clouds data rendering is examined. A small model already contain thousands
of data points. However, with a device of limited computing
capability, HoloLens targeted applications must be efficient
with the limited processing capabilities of the device. Furthermore, the applications must be able to render the data
smoothly. Using Unity Game Engine, applications are deployed to observe and characterize the supported render
pipelines: Built-in and Universal. Five rendering methods
are implemented on each of the pipeline: Game Objects,
Mesh Topology, Particles System, Compute Shader, and VFX
Graph.
Collected results showed the Built-in pipeline is most suitable, while the Mesh Topology is compatible with both pipelines,
has the highest GPU and CPU FPS and the lowest batches
count. VFX is also a good contender, albeit only the Universal Render Pipeline supports it. This paper provides a
basic ground work for further optimization research for the
HoloLens 2 and other MR devices using Unity.

### [Full paper](Assets/ThyDo_FinalReport.pdf)
### [Presentation](Assets/ThyDo_Final%20Presentation.pdf)
### [Rendered Rabbits](Assets/RabbitPhotos/)
### [Pitch Banner](Assets/ThyDo_PresentationPitch.pdf)
### [Pitch Text](Assets/Pitch.txt)
