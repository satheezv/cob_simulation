^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.7.6 (2022-07-29)
------------------

0.7.5 (2020-12-02)
------------------
* Merge pull request `#178 <https://github.com/ipa320/cob_simulation/issues/178>`_ from fmessmer/test_noetic
  test noetic
* Bump CMake version to avoid CMP0048 warning
* Contributors: Felix Messmer, fmessmer

0.7.4 (2020-03-18)
------------------
* Merge pull request `#175 <https://github.com/ipa320/cob_simulation/issues/175>`_ from LoyVanBeek/feature/python3_compatibility
  [ci_updates] pylint + Python3 compatibility
* fix pylint error
* Merge pull request `#174 <https://github.com/ipa320/cob_simulation/issues/174>`_ from fmessmer/ci_updates
  [travis] ci updates
* fix test dependendies
* use catkin_install_python
* catkin_lint fixes
* Contributors: Felix Messmer, fmessmer

0.7.3 (2019-11-07)
------------------

0.7.2 (2019-08-10)
------------------

0.7.1 (2019-08-07)
------------------

0.7.0 (2019-08-07)
------------------

0.6.10 (2018-07-21)
-------------------
* update maintainer
* Contributors: fmessmer

0.6.9 (2018-01-07)
------------------
* Merge pull request `#160 <https://github.com/ipa320/cob_simulation/issues/160>`_ from ipa320/indigo_release_candidate
  Indigo release candidate
* Merge pull request `#154 <https://github.com/ipa320/cob_simulation/issues/154>`_ from ipa-fxm/update_maintainer
  update maintainer
* update maintainer
* Merge pull request `#151 <https://github.com/ipa320/cob_simulation/issues/151>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Contributors: Felix Messmer, ipa-fxm, ipa-uhr-mk

0.6.8 (2017-07-31)
------------------
* remove cob_controller_configuration_gazebo
* use exported robotlist and envlist
* use cob_bringup robot.xml in simulation
* manually fix changelog
* Empty launch file changed and empty urdf created
* wait parameter removed. it was not working when launching a empty world
* Contributors: Bruno Brito, ipa-fxm

0.6.7 (2016-10-24)
------------------

0.6.6 (2016-10-10)
------------------
* generic wait for environment before spawn robot
* inserted wait for model, hopefully fixes max range bug
* Contributors: Benjamin Maidel, ipa-srd

0.6.5 (2016-04-01)
------------------
* fix dependency
* remove robot_id
* better default robot_id
* new line
* tf_prefix in higher level
* better diff
* nicer structure
* Revert "spawn two robots"
  This reverts commit b66aa13d920824a052d398dd8b49cb52c2c4a155.
* spawn two robots
* Contributors: Felix Gruber, Florian Weisshardt, ipa-fxm

0.6.4 (2015-08-29)
------------------
* migration to package format 2
* remove trailing whitespaces
* remove obsolete autogenerated mainpage.dox files
* sort dependencies
* review dependencies
* Contributors: ipa-fxm

0.6.3 (2015-06-17)
------------------
* beautify CMakeLists
* Contributors: ipa-fxm

0.6.2 (2014-12-15)
------------------
* Merge branch 'indigo_dev' into indigo_release_candidate
* missing dependencies for control plugins
* delete desire
* delete cob3-7
* delete cob3-5
* delete cob3-4
* delete cob3-2
* delete cob3-1
* introduce launchfile argument for -J option of spawn_model
* Contributors: Florian Weisshardt, ipa-fxm

0.6.1 (2014-09-22)
------------------

0.6.0 (2014-09-18)
------------------
* Merge pull request `#65 <https://github.com/ipa320/cob_simulation/issues/65>`_ from ipa320/hydro_dev
  bringin updates from hydro_dev
* Merge pull request `#64 <https://github.com/ipa320/cob_simulation/issues/64>`_ from ipa320/hydro_release_candidate
  Hydro release candidate
* 0.5.2
* update changelog
* Contributors: Florian Weisshardt

0.5.2 (2014-08-28)
------------------
* cleaning up
* New maintainer
* no OpenCV required in cob_gazebo
* Contributors: ipa-fxm, ipa-nhg

0.5.1 (2014-03-21)
------------------
* merge with groovy_dev
* setup tests
* fix launch file
* New structure
* merge with groovy_dev
* Adapt to the new cob_controller_configuration_gazebo structure
* removed a lot of code related to packages not available in hydro anymore
* change dependency from gazebo to gazebo_ros
* remove duplication
* changed to new gazebo_ros bridge
* installation stuff
* add roslaunch arg
* Initial catkinization.
* moved gazebo service to cob_controller_configuration_gazebo
* adding additional launch file parameters for gazebo simulation
* removed deprecated coloured_point_cloud nodes and libs + cleaning up
* unpause gazebo after spawning robot
* remove cob_ogre - not needed any more
* Removed cob_ogre dependency
* removed dependency to deleted cob_ogre package
* add cam3d throttle, renamed some topics
* added relay for color image
* removed pointcloud1 converter
* opt env for ROBOT
* adapted gazebo_services to FollowJointTrajectoryAction
* spawn cob a little lower
* cleanup launch files and substitute env through arg
* plugin file
* workaround for image_transport bug
* merge
* forget removing a line
* fuerte migration
* adapt roslaunch tests
* fix for raw
* moved cob_controller_config_gazebo to cob_robots and changed some minor things to support new structure
* changed manifest description
* Service /base_controller/stop able in simulation
* merge with ipa320
* merge with ipa320
* merge
* add cob3-4 tests
* Merge pull request `#4 <https://github.com/ipa320/cob_simulation/issues/4>`_ from ipa-goa/master
  connect callback for point cloud converter
* added connect and disconnect cb to converter
* added connect and disconnect callback
* removed point cloud conversion for faster simulation
* merge with ipa320
* remove env test
* fixed topic name
* Merge remote-tracking branch 'origin-ipa-fmw/master' into automerge
* Merge branch 'master' of github.com:ipa-fmw/cob_simulation into review-ipa-fmw
* add new gazebo services
* fix test
* reduced dependencies
* new directory structure in cob_description
* changes for creating colored point cloud
* merge
* added node to generate colored point cloud for kinect, removed obsolete point cloud fix
* added launch tests for simulation stack
* integrate tactile sensors in gazebo
* start the simulated tactile sensors with the simulation
* icob for simulation
* corrected the swissranger topics to the unified naming scheme
* worked on base controller for simulation
* modified launch file to include pointcloud fix
* node for fixing pointclouds from gazebo block laser
* tray parameters for component_test
* added point_cloud_converter for PointCloud2 in simulation
* modified
* parameter file
* fix sdh
* beautifying
* single arm and arm with sdh simulation running
* update component test
* modified unittest for components
* gazebo services for desire
* first gazebo test
* gazebo testing
* merge
* restructure urdf files and launch files for simulation
* changed launch files for single components
* bugfix
* changed launch file structure for bringup
* preparing release
* debugged service interface for gazebo
* service timeout for base and removed cob_defs from showdeps
* cleanup in simulation and common
* changed to spawn_model
* services for gazebo simulation
* services for gazebo simulation
* moved ekf domo publisher to nav; update positions for new urdf trafos; moved controller_manager to cob_controller_configuration_gazebo
* renamed manifest description
* deactivated cartesian interface in launch files
* populate ipa kitchen
* preparing for grasp script
* update documentation
* update dashboard
* cartesian arm movement is working with script_server
* merge with aub
* dual arm cob3 simulation and modified controllers for schunk simulation
* lbr.launch file added
* improvements of lbr simulation
* added lbr to simulation
* small fixes for simulation
* updated simulation files
* cleanup in cob_simulation
* missing files for simulation
* merge
* new simulation interfaces
* small fix
* missing bringup file
* new launch file for no contollers
* big changes to simulation structure
* new launch files for simulation
* modified manifests for documentation
* merge with master
* changed cob3_defs to cob_def in xacro, launch and urdf files
* adapt launch file to new packages names
* renamed packages to cob_ convention
* Contributors: Alexander Bubeck, Felix Messmer, Frederik Hegger, Georg Arbeiter, Richard Bormann, Sven Schneider, abubeck, brics, brudder, fmw-jiehou, fmw-jk, ipa-fmw, ipa-fxm, ipa-goa, ipa-nhg, ipa-uhr-fm, nhg-ipa
