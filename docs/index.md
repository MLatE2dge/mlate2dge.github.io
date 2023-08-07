

# Machine Learning @ the Extreme Edge.

<div style="text-align: center">
  <p><img width="400px" class="center-block" src="../img/Image - Project.png"></p>
</div>
<div style="text-align: center">
  <i><p style="font-size: 12px"> "This image was created with the assistance of DALL·E 2."</p></i>
</div>

<div style="text-align: justify"><p>Today's challenge is real-time and energy-efficient information extraction and processing at the edge using Artificial Intelligence. However, a recent trend exists to implement machine learning on devices located on the extreme edge, i.e. the border between the analog (physical) and digital world. These devices consist of one or more sensors and a resource-constrained embedded device, i.e. a device with limited memory, computing power, and power consumption. Today's challenge is the development of accurate, energy-efficient machine learning models for deployment on these resource-constrained devices. Starting from a case study, the project Machine Learning at the Extreme Edge (ML@E2dge) examines applying embedded machine learning to develop accurate, energy-efficient models for intelligent devices.</p></div>
## Case Study - Gait Stride Length Estimation Using Embedded Machine Learning

<div style="text-align: center">
  <p><img width="400px" class="center-block" src="../img/Image - Use case.png"></p>
</div>

<div style="text-align: center">
  <i><p style="font-size: 12px"> "This image was created with the assistance of DALL·E 2."</p></i>
</div>
<div style="text-align: justify"><p>Spatiotemporal gait parameters, e.g., gait stride length, are measurements that are classically derived from instrumented gait analysis. Today, different solutions are available for gait assessment outside the laboratory, specifically for spatiotemporal gait parameters. Such solutions are wearable devices that comprise an inertial measurement unit (IMU) sensor and a microcontroller (MCU). However, these existing wearable devices are resource constrained. They contain a processing unit with limited processing and memory capabilities, which limit the use of machine learning to estimate spatiotemporal gait parameters directly on the device. The solution for this limitation is embedded machine learning or tiny machine learning (tinyML). The use case aims to create a machine-learning model for gait stride length estimation deployable on a microcontroller.</p></div>

<div style="text-align: justify"><p>Starting from the <a href="https://www.mdpi.com/2306-5729/6/9/95"> TRIPOD dataset</a> consisting of gait strides from 15 healthy people, measured by IMU sensor, and using state-of-the-art machine learning frameworks - <a href="https://www.tensorflow.org">TensorFlow</a> and <a href="https://keras.io">Keras</a> -  and machine learning operations (MLOps) tools - <a href="https://www.edgeimpulse.com/">Edge Impulse Studio</a> and <a href="https://wandb.ai/">Weights and Biases</a> - a multilayer 1D convolutional float32 and int8 model for gait stride length estimation is developed.</p></div> 

<div style="text-align: justify"><p>The results, published in an Open-Source publication (proofreading ongoing), shows that estimating gait stride length directly on a microcontroller is feasible and demonstrates the potential of embedded machine learning or tinyML in designing wearable sensor devices for gait analysis.</p></div>
