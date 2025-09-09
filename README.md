# PhD Thesis Videos
Links to the videos accompanying my PhD Thesis: "3D Magnetic Vector Fields as an Unconventional Robotic Perception Modality".

## Chapter 4: Magnetic Vector Field Mapping and Localisation with Physics-Informed Sparse Gaussian Processes

### Section 4.3.3.3: Global Localisation in GP Magnetic Maps
- Simulation video: https://youtu.be/wxNFypJu_DU
- UTS Tech Lab video: https://youtu.be/x_XUpedlUIE

These animations demonstrate Section 4.3.3.3: Global Localisation in GP Magnetic Maps, for the Ansys simulation and UTS Tech Lab environments. A Gaussian Process is used as the measurement model for a particle filter. Shown is model (i): the divergence-free 3D vector-field map with 3D-vector measurements. The black marker is the ground truth robot trajectory, while the green marker is the particle filter pose hypothesis. The red markers represent the particles. The white lines indicate the orientations of each marker. The norm of the magnetic vector field is plotted with brighter areas corresponding to areas of greater field strength. In the Ansys simulation environment, the white rectangles are solid obstacles where the field cannot be sampled, so magnetic values are not included in the visualisation or the GP training data. In both examples, the particle filter quickly converges to the ground truth and maintains this hypothesis.

## Chapter 5: Mag-Match: Magnetic Vector Field Feature Detection and Description for Map Matching and Registration
Full demonstration video: https://youtu.be/xbHDUNFxOrA

This video demonstrates Mag-Match: Magnetic Vector Field Features for Map Matching and Registration, and accompanies the paper submission to IROS 2025. It shows the different stages of the system with animations and images. It better conveys the processes involved than the images in the paper alone, particularly the recursive Gaussian Process as it integrates additional data and improves the accuracy of its inference.

## Chapter 6: Mag-Follow: Active Perception and Planning in Magnetic Vector Fields with Recursive Gaussian Processes

### Section 6.3.2.2: Active perception in 3D - Mag-Follow trajectories
These videos demonstrate the exploration of Mag-Follow as it navigates a 3D magnetic vector field. The left figure shows the ground truth of this field. The right figure shows the field being continuously updated as more samples are acquired and the recursive Gaussian Process in Mag-Follow becomes more informed. A selection of sampling budgets show how the inferred field becomes more accurate as more samples are obtained.

- 250 points: https://youtu.be/NqkmViNFX5c
- 500 points: https://youtu.be/qT-awST4PEA
- 750 points: https://youtu.be/lxttKkMIBGU
- 1000 points: https://youtu.be/oq85O3FXS8o
