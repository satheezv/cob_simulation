^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_bringup_sim
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
* Merge pull request `#174 <https://github.com/ipa320/cob_simulation/issues/174>`_ from fmessmer/ci_updates
  [travis] ci updates
* fix test dependendies
* catkin_lint fixes
* Contributors: Felix Messmer, fmessmer

0.7.3 (2019-11-07)
------------------
* Merge pull request `#172 <https://github.com/ipa320/cob_simulation/issues/172>`_ from fmessmer/cob_gazebo_tools
  new package cob_gazebo_tools
* move scripts to cob_gazebo_tools
* Contributors: Felix Messmer, fmessmer

0.7.2 (2019-08-10)
------------------

0.7.1 (2019-08-07)
------------------
* Merge pull request `#167 <https://github.com/ipa320/cob_simulation/issues/167>`_ from floweisshardt/feature/spawn_with_explicit_package_and_type
  allow explicit definition of package and type for spawn object
* fix xacro file type
* fix naming of objects
* allow explicit definition of package and type for spawn object
* Merge pull request `#166 <https://github.com/ipa320/cob_simulation/issues/166>`_ from floweisshardt/fix/add_dependency_to_cob_gazebo_objects
  add dependency to cob_gazebo_objects which is used in spawn_object.py
* add dependency to cob_gazebo_objects which is used in spawn_object.py
* Contributors: Felix Messmer, floweisshardt

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
* Merge pull request `#156 <https://github.com/ipa320/cob_simulation/issues/156>`_ from ipa-fxm/add_move_initialpose_mode
  add move_initialpose mode
* add move_initialpose mode
* Merge pull request `#154 <https://github.com/ipa320/cob_simulation/issues/154>`_ from ipa-fxm/update_maintainer
  update maintainer
* update maintainer
* Merge pull request `#151 <https://github.com/ipa320/cob_simulation/issues/151>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Contributors: Felix Messmer, ipa-fxm, ipa-uhr-mk

0.6.8 (2017-07-31)
------------------
* refactored the code and added retreating model while on circular motion
* provision for re-spawning the person object to the start, due to presence of obstacle
* use xacro --inorder
* allow single letter option for move_object
* rospy.sleep exception handling
* wait for models and cleanup
* launch argument world_name
* use exported robotlist and envlist
* manually fix changelog
* debug functionality
* continue motion if object is far away enough
* metavars for parser options
* introduce stop_objects list and stop_distance
* remove throttled
* add missing robots to robotlist
* added stopping of objects
* Contributors: fmw-ss, hannes, ipa-fxm

0.6.7 (2016-10-24)
------------------
* Merge branch 'indigo_dev' into indigo_release_candidate
* make roslaunch a denend (was only exec_depend)
* Contributors: Florian Weisshardt

0.6.6 (2016-10-10)
------------------
* enable tests for ipa-office
* fix roslaunch tests
* fix roslaunch tests
* delete ipa-factory
* support relative defined objects in remove_objects.py and tabs vs spaces
* Added feature of deleting multiple objects included in a group to script remove_object.py
* enable roslaunch checks
* remove prints and rename groups namespace
* Updated structure of spawn_object.py to reduce code redundance
* Added the functionality to spawn sdf's using spawn_object and a check if object is there before deleting it
* Updated spawn objects script so that it takes object groups into account
* generic wait for environment before spawn robot
* spawn_object supports children objects
* added script file to spawn racks and other objects
* Contributors: Benjamin Maidel, Florian Weisshardt, ipa-fmw, ipa-fxm, ipa-mig-mc, ipa-nhg, ipa-srd-rd

0.6.5 (2016-04-01)
------------------
* fix install tags and dependencies
* fix move_object script
* Update move.py
* added people, move.py and changed model names
* added people and the possibility to move objects
* enable other gazebo worlds packages
* remove robot_id
* better default robot_id
* delete two_robots.launch
* Merge pull request `#91 <https://github.com/ipa320/cob_simulation/issues/91>`_ from ipa-mig-mc/fix/issue_number_90_missing_import_roslib
  added import roslib to spawn_object.py and did corresponding addition…
* launch file for spawning two robots
* added import roslib to spawn_object.py and did corresponding addition to packages.xml
* space
* nicer structure
* Revert "spawn two robots"
  This reverts commit b66aa13d920824a052d398dd8b49cb52c2c4a155.
* spawn two robots
* Contributors: Felix Gruber, Felix Messmer, Florian Weisshardt, hannes, ipa-fmw, ipa-fxm, ipa-mig-mc

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
* introduce launchfile argument for -J option of spawn_model
* Contributors: ipa-fxm

0.6.1 (2014-09-22)
------------------

0.6.0 (2014-09-18)
------------------
* remove object script working
* Merge pull request `#65 <https://github.com/ipa320/cob_simulation/issues/65>`_ from ipa320/hydro_dev
  bringin updates from hydro_dev
* Merge pull request `#64 <https://github.com/ipa320/cob_simulation/issues/64>`_ from ipa320/hydro_release_candidate
  Hydro release candidate
* 0.5.2
* update changelog
* Contributors: Florian Weisshardt, ipa-nhg

0.5.2 (2014-08-28)
------------------
* cleaning up
* New maintainer
* Contributors: ipa-fxm, ipa-nhg

0.5.1 (2014-03-21)
------------------
* merge with groovy_dev
* setup tests
* Merge branch 'hydro_dev' of github.com:ipa-nhg/cob_simulation into hydro_dev
* change dependency from gazebo to gazebo_ros
* waiting for gazebo services
* Hydro migration
* installation stuff
* Initial catkinization.
* merge
* adding additional launch file parameters for gazebo simulation
* filename for uploading navigation goals is now taking into account update default_env_config structure in cob_environments
* adjust launch file names and add script to remove objects
* opt env for ROBOT
* removed outdated file
* move tf listener to gazebo worlds; git push origin master
* Spawn_object script also set a description parameter
* enhanced spawn_objects script for better error_handling and updating of already spawned objects
* Addapted spawn_object to spawn multiple times the same object in different positions
* cleanup launch files and substitute env through arg
* fix directory
* fix copy and paste error
* fix test
* Merge branch 'review-ipa320'
* Merge pull request `#15 <https://github.com/ipa320/cob_simulation/issues/15>`_ from ipa-nhg/master
  Moved ipa-apartment.launch file
* addapted robot.launch to the new cob_gazebo_worlds structure
* add arg for robot_config and env_config
* update manifest
* upload default parameters in bringup_sim
* moved cob_sound include to cob_controller_configuration_gazebo
* update deps
* New name space for objects
* merge
* adapt roslaunch tests
* The spawn_object.py script can be called with several arguments
* moved cob_controller_config_gazebo to cob_robots and changed some minor things to support new structure
* Test for ipa-apartment in CMakelists
* filled manifest
* Move spawn_object script to cob_bringup_sim
* Move script spawn_object.py to cob_bringup simscripts/spawn_object.py
* fix icob simulation
* add cob3-4 tests
* merge with ipa320
* update stack
* reduced dependencies
* added bringup_sim package
* Contributors: Alexander Bubeck, Florian Weißhardt, Frederik Hegger, abubeck, ipa-fmw, ipa-fxm, ipa-nhg, ipa-uhr-fm
