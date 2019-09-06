# Face-Blur-with-AWS-Deeplens
Detect and blur faces in live video for whatever reasons, e.g. little bit for skin smoothing or a lot for suspect identity protection, using AWS Deeplens, a deeplearning enabled, programable "smart" camera meant to introduce developers to AWS cloud ecosystem, rather than delivering a powerful edge device. 

# Demo video
[Link to Youtube](https://www.youtube.com/watch?v=Ak436N1o-AU)

As seen from the project stream (inference lambda output) in the video above, face is being tracked and blured while everything else such as mario on the shirt remains sharp. Frame rate is terrible, running optimized model on integrated gpu of Atom processor. 

# Model used
Pretrained face detection model for deeplens

# Lambda used
greengrassHelloWorld.py in this repo

