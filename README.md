

# Posetivity 


## Overview
This uses TensorFlow Lite PoseNet and detects the person posture using Pose Estimation model.
It maintains the same aspact ratio.


### Model used
[Pose Estimation model][posenet-model] is a vision model that can be used to
estimate the pose of a person in an image or video by estimating where key body
joints are.

## Requirements

* Xcode
* Valid Apple Developer ID
* Real iOS device with camera
* iOS version 12.0 or above
* Xcode command line tools (to install, run `xcode-select --install`)
* CocoaPods (to install, run `sudo gem install cocoapods`)

## Build and run
1. Clone the TensorFlow examples GitHub repository to your computer to get the
demo application.

    ```
    git clone https://github.com/harish-rajan/Posetivity.git
    ```

1. Install the pod to generate the workspace file:

    ```
    cd Posetivity && pod install
    ```
    Note: If you have installed this pod before and that command doesn't work,
    try `pod update`.
    At the end of this step you should have a directory called
    `PoseNet.xcworkspace`.

1. Open the project in Xcode with the following command:

    ```
    open PoseNet.xcworkspace
    ```
    This launches Xcode and opens the `PoseNet` project.


[posenet-model]: https://www.tensorflow.org/lite/models/pose_estimation/overview


## Citation

https://www.tensorflow.org/lite/models/pose_estimation/overview

https://github.com/tensorflow/examples/tree/master/lite/examples/posenet/ios

https://towardsdatascience.com/pose-estimation-and-matching-with-tensorflow-lite-posenet-model-ea2e9249abbd

Model used:

https://www.tensorflow.org/lite/models/pose_estimation/overview


