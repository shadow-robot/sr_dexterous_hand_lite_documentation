Dexterous Hand Lite Documentation
==================================

Preface
--------

The Shadow Dexterous Hand Lite is an advanced humanoid robot hand system that provides 16
movements to reproduce as closely as possible the kinematics and dexterity of the human hand. It
has been designed to provide comparable force output and movement precision to the human hand.
Shadow Hand systems have been used for research in grasping, manipulation, neural control, brain
computer interface, industrial quality control, and hazardous material handling.
The Shadow Dexterous Hand Lite is a self-contained system - all actuation and sensing is built into
the hand and forearm.

All versions of the Hand use an EtherCAT bus (Ethernet for Control Automation Technology),
providing a 100Mbps Ethernet-based communications field-bus, and full integration into ROS
(Robot Operating System).

The Hands use Shadow's electric “Smart Motor” actuation system and integrates force and position
control electronics, motor drive electronics, motor, gearbox, force sensing and communications into
a compact module, 13 of which are packed into the Hand base.

.. image:: img/index_shadow_dexterous_hand.png
   :width: 100%

Overview
--------

* :doc:`/user_guide/ov_pelicase_contents`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/ov_laptopbox_contents`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/ov_abbreviations`


.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Overview
   
   user_guide/ov_pelicase_contents
   sr_dexterous_hand_documentation/docs/user_guide/ov_laptopbox_contents
   sr_dexterous_hand_documentation/docs/user_guide/ov_abbreviations

   
Setting up the hand
--------------------

* :doc:`/user_guide/sh_connecting_cables`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sh_desktop_icons`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sh_mounting_hand_arm`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sh_launching_hand`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sh_lights`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sh_uploading_logs`
   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Setting up the hand
   
   user_guide/sh_connecting_cables
   sr_dexterous_hand_documentation/docs/user_guide/sh_desktop_icons
   sr_dexterous_hand_documentation/docs/user_guide/sh_mounting_hand_arm
   sr_dexterous_hand_documentation/docs/user_guide/sh_launching_hand
   sr_dexterous_hand_documentation/docs/user_guide/sh_lights
   sr_dexterous_hand_documentation/docs/user_guide/sh_uploading_logs
   
Simulation
--------------------------------

* :doc:`/user_guide/sim_gazebo`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Simulation
   
   user_guide/sim_gazebo
   
Software description
---------------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_First_time_users`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Controling_hand`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Accesing_data`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_User_Interface`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Command_line`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Repositories`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Robot_commander`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Saving_states`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Autodetection`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Robot_description`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Fingertips`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sd_Firmware`
   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Software description
   
   sr_dexterous_hand_documentation/docs/user_guide/sd_First_time_users
   sr_dexterous_hand_documentation/docs/user_guide/sd_Controling_hand
   sr_dexterous_hand_documentation/docs/user_guide/sd_Accesing_data
   sr_dexterous_hand_documentation/docs/user_guide/sd_User_Interface
   sr_dexterous_hand_documentation/docs/user_guide/sd_Command_line
   sr_dexterous_hand_documentation/docs/user_guide/sd_Repositories
   sr_dexterous_hand_documentation/docs/user_guide/sd_Robot_commander
   sr_dexterous_hand_documentation/docs/user_guide/sd_Saving_states
   sr_dexterous_hand_documentation/docs/user_guide/sd_Autodetection
   sr_dexterous_hand_documentation/docs/user_guide/sd_Robot_description
   sr_dexterous_hand_documentation/docs/user_guide/sd_Fingertips
   sr_dexterous_hand_documentation/docs/user_guide/sd_Firmware

Mechanical description
-----------------------------------

* :doc:`/user_guide/md_dimentions`
* :doc:`/user_guide/md_kinematics`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/md_finger`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/md_thumb`
* :doc:`/user_guide/md_ranges`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/md_position_sensors`
* :doc:`/user_guide/md_motor_unit`
* :doc:`/user_guide/md_motor_layout`
   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Mechanical description

   user_guide/md_dimentions
   user_guide/md_kinematics
   sr_dexterous_hand_documentation/docs/user_guide/md_finger
   sr_dexterous_hand_documentation/docs/user_guide/md_thumb
   user_guide/md_ranges
   sr_dexterous_hand_documentation/docs/user_guide/md_position_sensors
   user_guide/md_motor_unit
   user_guide/md_motor_layout

Electrical description
-----------------------------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/ed_chipset`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/ed_dataflow`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/ed_control_description`
   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Electrical description

   sr_dexterous_hand_documentation/docs/user_guide/ed_chipset
   sr_dexterous_hand_documentation/docs/user_guide/ed_dataflow
   sr_dexterous_hand_documentation/docs/user_guide/ed_control_description
   
Connectors and Pinouts
-----------------------------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/cp_external_connectors`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/cp_internal_connectors`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Connectors and Pinouts

   sr_dexterous_hand_documentation/docs/user_guide/cp_external_connectors
   sr_dexterous_hand_documentation/docs/user_guide/cp_internal_connectors
   
Maintaining the system
-----------------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/mh_mechanical_maintenance`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/mh_electronic_maintenance`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/mh_installing_the_software`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Maintaining the hand
   
   sr_dexterous_hand_documentation/docs/user_guide/mh_mechanical_maintenance
   sr_dexterous_hand_documentation/docs/user_guide/mh_electronic_maintenance
   sr_dexterous_hand_documentation/docs/user_guide/mh_installing_the_software

FAQ & Changelog
----------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/fc_FAQ`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/fc_nuc_server`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/fc_changelog`
   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: FAQ & Changelog
   
   sr_dexterous_hand_documentation/docs/user_guide/fc_FAQ
   sr_dexterous_hand_documentation/docs/user_guide/fc_nuc_server
   sr_dexterous_hand_documentation/docs/user_guide/fc_changelog

Support & Teamviewer
---------------------

* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sp_support`
* :doc:`/sr_dexterous_hand_documentation/docs/user_guide/sp_restore_backup`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Support & Teamviewer
   
   sr_dexterous_hand_documentation/docs/user_guide/sp_support
   sr_dexterous_hand_documentation/docs/user_guide/sp_restore_backup
