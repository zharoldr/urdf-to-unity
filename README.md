# urdf-to-unity

This repo contains submodules that the Turtlebot repo depends upon.
Running `./setup.sh` compiles everything, creates the Turtlebot URDF,
and strips all collision, inertial, plugin, and sensor data from the
file. Some folders are also copied around so that when the URDF is
imported into Unity, Unity knows where all of the mesh data is.
