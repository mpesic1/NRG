# NRG

Seminar for Advanced computer graphics course 2018/19. This is a visualization of weather data on LiDAR point clouds. The application was developed and tested in Mozilla Firefox. To run the application, set up a web server as suggested at http://potree.org/getting_started.html. A python simple server should work as well but is not tested.

LiDAR data will be available for some time at https://www.dropbox.com/s/9i78eal5i3khre4/pointclouds.zip?dl=0. Place the unzipped pointclouds file in the root directory.

To enable night/day cycle simulation, set: 

viewer.setEDLEnabled(true);

at line 52 in testPage.html but beware of battery drain if running on a laptop.
