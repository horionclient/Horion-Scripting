Vec2
****

.. module:: Vec2

.. attribute:: x
	
	X Value

.. attribute:: y
	
	Y Value

.. method:: getX()

	:returns double: X value

.. method:: getY()

	:returns double: Y value

.. method:: isValid()

	:returns boolean: Whether or not this Vec2 is valid

	This is usually not needed, but kept in for debugging purposes 

.. method:: toString()

	:returns string: 

.. method:: add(other)

	:param Vec2|double other:

	Adds other to this and returns the result (original vector remains unchanged).
	
	Element-wise addition if other is double

	:returns: :mod:`Vec2`

.. method:: add(ox, oy)

	:param double ox:
	:param double oy:

	Adds arguments to this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec2`

.. method:: sub(other)

	:param Vec2|double other:

	Subtracts other from this and returns the result (original vector remains unchanged).

	Element-wise subtraction if other is double

	:returns: :mod:`Vec2`

.. method:: sub(ox, oy)

	:param double ox:
	:param double oy:

	Subtracts arguments from this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec2`

.. method:: mul(other)

	:param Vec2|double other:

	Multiplies other with this and returns the result (original vector remains unchanged).

	Element-wise multiplication if other is double

	:returns: :mod:`Vec2`

.. method:: mul(ox, oy)

	:param double ox:
	:param double oy:

	Multiplies arguments with this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec2`

.. method:: div(other)

	:param Vec2|double other:

	Divides this by other and returns the result (original vector remains unchanged).

	Element-wise division if other is double

	:returns: :mod:`Vec2`

.. method:: div(ox, oy)

	:param double ox:
	:param double oy:

	Divides this vector by the arguments and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec2`