### Looking Outwards 1: Driving High-Resolution Facial Scans with Video Performance Capture


[![video of research](http://img.youtube.com/vi/mGH0nNkTOJI/0.jpg)](http://www.youtube.com/watch?v=mGH0nNkTOJI)

![](http://gl.ict.usc.edu/Research/DrivingScansWithVideo/images/Teaser.jpg)

In [“Driving High-Resolution Facial Scans with Video Performance Capture”](http://gl.ict.usc.edu/Research/DrivingScansWithVideo/Fyffe_DrivingScansWithVideo_ACMTOG2014_Preprint.pdf), presented at SIGGRAPH 2015, the authors describe a method for driving a static scanned model of a face using video from multiple angles. The algorithm used finds correspondences between dynamic frames and a static scanned model. Unlike traditional facial motion capture techniques, this method doesn’t need markers or face paint to track points. It also doesn’t require facial feature detection or rigging. The benefit of animated a scanned mesh is that it can be relit and positioned to match arbitrary environmental conditions. I’m interested in this technique because it lets you capture performance using off-the-shelf video cameras, assuming you already have static scans of the face you wish to animate. It is more cost-effective than high-end volumetric video capture – [see this recent “holographic video“ research from Microsoft](https://www.youtube.com/watch?v=kZ-XZIV-o8s) – which requires a rig with many sensors. One drawback of this technique is that it requires a static scanned mesh from the actor (as opposed to an arbitrary face mesh) in order to find correspondences between the video and the model. This paper was presented at the ["Face Reality"](http://s2015.siggraph.org/attendees/technical-papers/sessions/face-reality) session at SIGGRAPH, along with other papers describing similar techniques, such as "Facial-Performance-Sensing Head-Mounted Display" and "Real-Time High-Fidelity Facial Performance Capture". With the coming commercial availability of VR headsets, there seems to be increasing demand for capture techniques that integrate well with 3D environments.