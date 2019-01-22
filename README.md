# NRG

Seminar for Advanced computer graphics course 2018/19. This is a visualization of weather data on LiDAR point clouds. The application was developed and tested in Mozilla Firefox. To run the application, set up a web server as suggested at http://potree.org/getting_started.html. A python simple server should work as well but is not tested.

To enable night/day cycle simulation, set: 

viewer.setEDLEnabled(true);

at line 52 in testPage.html but beware of battery drain if running on a laptop.
