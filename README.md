sawIntuitiveResearchKit
=======================

Libraries and applications for the da Vinci Research Kit

Links
=====

 * Documentation: http://github.com/jhu-dvrk/sawIntuitiveResearchKit/wiki
 * License: http://github.com/jhu-cisst/cisst/blob/master/license.txt
 * JHU-LCSR software: http://jhu-lcsr.github.io/software/
 * [Code of conduct](CODE_OF_CONDUCT.md)
 
Dependencies
============
 * da Vinci Research Kit hardware: http://research.intusurg.com/dvrkwiki
 * Linux only
 * cisst libraries: https://github.com/jhu-cisst/cisst
 * sawRobotIO1394: http://github.com/jhu-saw/sawRobotIO1394
 * sawControllers: http://github.com/jhu-saw/sawControllers


About this Fork
===============

This forked version removes an existing hardcode in the source code where everything is done with respect to the ECM. This is not always desired, so it has been changed here. The modified `dvrk_ros.rosinstall` file is provided to setup a dvrk workspace. 
