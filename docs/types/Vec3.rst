Vec3
****

.. module:: Vec3

.. attribute:: x
	
	X Value

.. attribute:: y
	
	Y Value

.. attribute:: z
	
	Z Value

.. method:: getX()

	:returns double: X value

.. method:: getY()

	:returns double: Y value

.. method:: getZ()

	:returns double: Z value

.. method:: isValid()

	:returns boolean: Whether or not this Vec3 is valid

	This is usually not needed, but kept in for debugging purposes 

.. method:: toString()

	:returns string: 

.. method:: add(other)

	:param Vec3|double other:

	Adds other to this and returns the result (original vector remains unchanged).
	
	Element-wise addition if other is double

	:returns: :mod:`Vec3`

.. method:: add(ox, oy, oz)

	:param double ox:
	:param double oy:
	:param double oz:

	Adds arguments to this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec3`

.. method:: sub(other)

	:param Vec3|double other:

	Subtracts other from this and returns the result (original vector remains unchanged).

	Element-wise subtraction if other is double

	:returns: :mod:`Vec3`

.. method:: sub(ox, oy, oz)

	:param double ox:
	:param double oy:
	:param double oz:

	Subtracts arguments from this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec3`

.. method:: mul(other)

	:param Vec3|double other:

	Multiplies other with this and returns the result (original vector remains unchanged).

	Element-wise multiplication if other is double

	:returns: :mod:`Vec3`

.. method:: mul(ox, oy, oz)

	:param double ox:
	:param double oy:
	:param double oz:

	Multiplies arguments with this vector and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec3`

.. method:: div(other)

	:param Vec3|double other:

	Divides this by other and returns the result (original vector remains unchanged).

	Element-wise division if other is double

	:returns: :mod:`Vec3`

.. method:: div(ox, oy, oz)

	:param double ox:
	:param double oy:
	:param double oz:

	Divides this vector by the arguments and returns the result (original vector remains unchanged).

	:returns: :mod:`Vec3`