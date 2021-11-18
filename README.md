# GroningenNet

Deep learning for low-magnitude earthquake detection on a multi-level sensor network

Automatic detection of low-magnitude earthquakes has become an increasingly important research topic in recent years due to a sharp increase in induced seismicity around the globe. The detection of low-magnitude seismic events finds growing industrial applications in hydraulic fracturing, carbon capture and storage (CCS), and geothermal monitoring to mitigate hazards and ensure safe operations. Moreover, detection of these earthquakes is crucial to understand the underlying mechanisms of larger earthquakes. Various algorithms, including deep learning methods, have been proposed over the years to detect such low-magnitude events. However, there is still a need for improving the robustness of these methods in discriminating between local sources of noise and weak seismic events. In this study, we propose a convolutional neural network (CNN) to detect seismic events from shallow borehole stations in Groningen, the Netherlands. We train a CNN model to detect low-magnitude earthquakes harnessing the multi-level sensor configuration of the G-network in Groningen. Each G-network station contains four geophones at depths of 50, 100, 150, and 200 meters. Unlike prior deep learning approaches that use 3-component seismic records at a single sensor level, we use records from the entire borehole as one training example. This allows us to train the CNN model using moveout patterns of the energy traveling across the borehole sensors at a single station to discriminate between events originating in the subsurface and local noise coming from the surface. We compare the prediction accuracy of our trained CNN model to that of the STA/LTA and template matching algorithms on a two-month continuous record. We demonstrate that the CNN model shows significantly better performance than STA/LTA and template matching in detecting new events missing from the catalog and minimizing false detections. Moreover, we find that using the moveout feature allows us to effectively train our CNN model using only a fraction of the data that would be needed otherwise, saving plenty of manual labor in preparing training labels. The proposed approach can be easily applied to other microseismic monitoring networks with multi-level sensors.

# Citation

If you find our work useful in your research, please cite:

@article{shaheen2021deep,
  title={Deep learning for low-magnitude earthquake detection on a multi-level sensor network},
  author={Shaheen, Ahmed and Waheed, Umair bin and Fehler, Michael and Sokol, Lubos and Hanafy, Sherif},
  journal={arXiv preprint arXiv:2103.07897},
  year={2021}
}

# Contact

If you have any questions, please feel free to email the author.

