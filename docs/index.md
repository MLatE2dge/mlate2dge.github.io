

# Machine Learning @ the Extreme Edge

<div style="text-align: center"><p style="font-size: 18px"><a href="https://jrverbiest.github.io/">Joeri Verbiest</a></p></div>

<div style="text-align: center">
  <p><img width="400px" class="center-block" src="../img/Image - Project.png"></p>
</div>
<div style="text-align: center">
  <i><p style="font-size: 12px"> "This image was created with the assistance of DALL·E 2."</p></i>
</div>
<div style="text-align: justify"><p>Today's challenge is real-time and energy-efficient information extraction and processing at the edge using Artificial Intelligence. However, a recent trend exists to implement machine learning on devices located on the extreme edge, i.e. the border between the analog (physical) and digital world. These devices consist of one or more sensors and a resource-constrained embedded device, i.e. a device with limited memory, computing power, and power consumption. Today's challenge is the development of accurate, energy-efficient machine learning models for deployment on these resource-constrained devices. Given a (healthcare) use case, the project examines how to apply embedded machine learning to develop accurate, energy-efficient models for intelligent devices.</p></div><br>

## Case Study - Gait Stride Length Estimation Using Embedded Machine Learning

<div style="text-align: center">
  <p><img width="400px" class="center-block" src="../img/Image - Use case.png"></p>
</div>
<div style="text-align: center">
  <i><p style="font-size: 12px"> "This image was created with the assistance of DALL·E 2."</p></i>
</div>
<div style="text-align: justify"><p>Spatiotemporal gait parameters, e.g., gait stride length, are classically derived from instrumented gait analysis measurements. Today, different solutions are available for gait assessment outside the laboratory, specifically for spatiotemporal gait parameters. Such solutions are wearable devices that comprise an inertial measurement unit (IMU) sensor and a microcontroller (MCU). However, these existing wearable devices are resource constrained. They contain a processing unit with limited processing and memory capabilities, which limit the use of machine learning to estimate spatiotemporal gait parameters directly on the device. The solution for this limitation is embedded machine learning or tiny machine learning (tinyML).</p></div>

<div style="text-align: justify"><p>The use case aims to create a machine-learning model for gait stride length estimation deployable on a microcontroller. Starting from the <a href="https://www.mdpi.com/2306-5729/6/9/95"> TRIPOD dataset</a> consisting of gait strides from 15 healthy people, measured by IMU sensor, and using state-of-the-art machine learning frameworks - <a href="https://www.tensorflow.org">TensorFlow</a> and <a href="https://keras.io">Keras</a> -  and machine learning operations (MLOps) tools - <a href="https://www.edgeimpulse.com/">Edge Impulse Studio</a> and <a href="https://wandb.ai/">Weights and Biases</a> - a multilayer 1D convolutional float32 and int8 model for gait stride length estimation is developed.</p></div> 

<div style="text-align: justify"><p>The use case outcome shows that estimating gait stride length directly on a microcontroller is feasible and demonstrates the potential of embedded machine learning or tinyML in designing wearable sensor devices for gait analysis. The results are published in <a href="https://www.mdpi.com/1424-8220/23/16/7166">Gait Stride Length Estimation Using Embedded Machine Learning</a> (Open-Access). This article belongs to the MDPI Sensors Special Issue <a href="https://www.mdpi.com/journal/sensors/special_issues/9DML2DP267">Wearable Sensors for Gait, Human Motion Analysis and Health Monitoring</a>.</p></div>

---

<div style="text-align: justify" > <p style="font-size: 10px">Project supported by the Karel de Grote University of Applied Sciences and Arts through funding by the Flemish government specifically allocated to practice-based research at universities of applied sciences. Project duration: 1 December 2021 - 31 August 2023 (14 person-month).</div>
