ROSforLabview
=============

A Labview solution for communicating with ROS applications. Developed at Tufts University by the Mechanical Engineering Department and the Center for Engineering Education and Outreach.

Although all of the examples here, and many of the file names, are related to Baxter Research Robot (Rethink Robotics), none of the core functionality is dependent on using Baxter as opposed to other ROS systems. This package currently supports publishing and subscribing on topics as well as service clients. It does not currently support the creation of custom service providers or the ability to use Labview as the ROS master. In addition, publishers and subscribers only support a single connection. Any requests for a topic connection after the first has been established will be ignored. 


REQUIRED EXTERNAL PACKAGES
==========================
Use of this package requires the installation of the OpenG MD5 Library, which can be installed through the VI Package Manager ( http://jki.net/vipm )
