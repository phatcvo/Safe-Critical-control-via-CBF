### Environments
Create your environment via `conda env create -f environment.yml`. The default conda environment name is `cbf`, and you could also choose that name with your own preferences by editing the .yml file.

Run `python models/kinematic_car_test.py`. This simulates maze navigation (two maze setups) with duality-based obstacle avoidance (four robot shapes including rectangle, pentagon, triangle and l-shape) in the discrete-time domain. The animations and snapshots can be found in folder `animations` and `figures`. An example animation video can be generated as follows,

https://user-images.githubusercontent.com/27001847/147999361-faf3557a-3c87-48ab-aa3a-8830b3d565d5.mp4

### References
[Safety-Critical Control and Planning for Obstacle Avoidance between Polytopes with Control Barrier Functions](https://arxiv.org/abs/2109.12313)
