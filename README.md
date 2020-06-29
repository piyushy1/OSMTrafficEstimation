# Traffic Estimation for OpenStreetMap using Open Traffic Cameras

Displaying near-real time traffic state information is a useful feature of digital navigation maps. However, most commercial providers rely on privacy compromising measures such as deriving location information from cellphones to estimate traffic. The lack of an open-source traffic estimation method using open data platforms is a bottleneck for building sophisticated navigation services on top of OpenStreetMap (OSM). We propose a deep learning-based Complex Event Processing (CEP) method that relies on publicly available video camera streams for traffic state estimation. The proposed framework performs near-real time object detection and object property extraction across camera clusters in parallel to derive multiple measures related to traffic with the results visualized on OpenStreetMap. The estimation of object properties (e.g. speed, count, direction) provides multi-dimensional data that can be leveraged to create metrics and visualization for congestion beyond commonly used density based measures. For example, we couple both flow and count measures during interpolation by considering each vehicle as a sample point and their speed as weight. We demonstrate  multidimensional traffic metrics (e.g. flow rate, congestion estimation) over OSM by processing 22 traffic cameras from London. The system achieves a near realtime performance of 1.42 seconds median latency and an average F-score of 0.80.

![Image of OSM](https://github.com/piyushy1/OSMTrafficEstimation/blob/master/Maps.svg)

## Dataset
Camera Link {Please Connect to author for dataset}


## References
Yadav, Piyush, Dipto Sarkar, Dhaval Salwala, and Edward Curry. “Complex Event Processing based Near Real-Time Traffic Prediction Framework for OpenStreetMap using Open Traffic Cameras”. In 11th International Conference on Geographic Information Systems (GIScience 2020), 2020.

## Contact
Email <piyushy1@gmail.com>
