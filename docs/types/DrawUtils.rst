DrawUtils
*********

.. module:: DrawUtils

All methods listed here may only be executed in the onRender callback


.. method:: setColor(r, g, b, a)

	:param double r: Red component (0-1)
	:param double g: Green component (0-1)
	:param double b: Blue component (0-1)
	:param double a: Alpha component (Transparency, 0-1, defaults to 1)

.. method:: drawLine3d(start, end, lineWidth)

	:param Vec3 start:
	:param Vec3 end:
	:param double lineWidth: not implemented

	Draws a line in 3d space, can not be seen through blocks or mobs

.. method:: drawLinestrip3d(pointList, lineWidth)

	:param Vec3[] pointList: array of Vec3's
	:param double lineWidth: not implemented

	Draws a linestrip with all the points in the list (at least 2 points needed)
	
	Can not be seen through blocks or mobs