ModuleManager
*************

.. module:: ModuleManager


.. method:: getModuleByName(name)

	:returns: :mod:`Module`
	:param string name: Name of Module

	May return null when the module is not found

.. method:: registerModule(name)

	:returns: :mod:`JsModule`
	:param string name: Name of Module, should be between 3 - 30 characters long

	Only works when the script is executed as a file


