DrawUtils
*********

.. module:: DrawUtils

All 3d draw methods listed here may only be executed in the onRender callback

All 2d draw methods listed here may only be executed in the onRender2d callback


.. method:: setColor(r, g, b, a)

	:param double r: Red component (0-1)
	:param double g: Green component (0-1)
	:param double b: Blue component (0-1)
	:param double a: Alpha component (Transparency, 0-1, defaults to 1)

.. method:: drawLine2d(start, end, lineWidth)

	:param Vec2 start:
	:param Vec2 end:
	:param double lineWidth: 

	Draws a line in 2d space on the play screen

.. method:: drawRectangle2d(start, end, lineWidth)

	:param Vec2 start: top left corner of the rectangle
	:param Vec2 end: bottom right corner of the rectangle
	:param double lineWidth: 

	Draws a hollow rectangle in 2d space on the play screen

.. method:: fillRectangle2d(start, end)

	:param Vec2 start: top left corner of the rectangle
	:param Vec2 end: bottom right corner of the rectangle

	Draws a filled rectangle in 2d space on the play screen

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