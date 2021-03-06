.. _BatteryStateful:

BatteryStateful
***********************************

Wrapper for SAM Simulation Core model: `cmod_battery_stateful.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_battery_stateful.cpp>`_

Input Consistency Warning
==================================

As described in :ref:`Possible Problems <possible_problems>`, some input parameters are interdepedent but the equations accounting for these
interdependencies that enforce consistency among these input parameters are not available in the PySAM module. Therefore,
the onus is on the PySAM user to check that interdependencies are correctly handled. The variables which may require
additional logic include:


Provided for each of these inputs is a list of other inputs that are potentially interdependent. 

Creating an Instance
===================================

Refer to the :ref:`Initializing a Model <initializing>` page for details on the different ways to create an instance of a PySAM class.

**BatteryStateful model description**

.. automodule:: PySAM.BatteryStateful
	:members:

Functions
===================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful
	:members:

Controls Group
======================================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful.Controls
	:members:

ParamsCell Group
======================================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful.ParamsCell
	:members:

ParamsPack Group
======================================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful.ParamsPack
	:members:

StatePack Group
======================================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful.StatePack
	:members:

StateCell Group
======================================================

.. autoclass:: PySAM.BatteryStateful.BatteryStateful.StateCell
	:members:

