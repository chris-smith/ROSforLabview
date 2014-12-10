Active development on ROSforLabview is being continued at Tufts University.

You can find that work at https://github.com/tuftsBaxter/ROSforLabVIEW

ROSforLabview
=============

A Labview solution for communicating with ROS applications. Developed at Tufts University by the Mechanical Engineering Department and the Center for Engineering Education and Outreach. Currently in alpha.

Although all of the examples here, and many of the file names, are related to Baxter Research Robot (Rethink Robotics), none of the core functionality is dependent on using Baxter as opposed to other ROS systems. This package currently supports publishing and subscribing on topics as well as service clients. It does not currently support the creation of custom service providers or the ability to use Labview as the ROS master. In addition, publishers and subscribers only support a single connection. Any requests for a topic connection after the first has been established will be ignored.

ROSforLV_0.1 should be installed in your "Labview > user.lib" folder (Under applications in Mac OS X and program files in Windows). Labview will need to restart after installing the library.

Please send feedback on our mailing list at https://groups.google.com/forum/#!forum/ros-sig-rosforlabview
<!---

REQUIRED EXTERNAL PACKAGES
==========================
Use of this package requires the installation of the OpenG MD5 Library, which can be installed through the VI Package Manager ( http://jki.net/vipm )
-->

Use with Baxter Research Robot
==============================
This package has been developed with the use of Baxter Research Robot. Much of his functionality has already been implemented and can be found in the devices folder. If using Baxter's cameras, the included vis make use of a vision package previously developed at the Center for Engineering Education and Outreach which can be downloaded at http://www.legoengineering.com/image-processing-in-labview/

CompactRIO
==========
At this time the package is not able to be deployed to a cRIO as information is pushed and pulled from the servers through Front Panel controls. It should be possible to switch out the front panel calls with shared variables to get around this problem.
