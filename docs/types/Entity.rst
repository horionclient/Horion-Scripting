Entity
******

.. module:: Entity

.. method:: isValid()

	:returns boolean:

	Use this to check whether the Entity still exists


.. method:: getPosition()
	
	:returns: :mod:`Vec3`

.. method:: getVelocity()
	
	:returns: :mod:`Vec3`

.. method:: isOnGround()
	
	:returns boolean:

	True when the entity is standing on ground, might not work on non-player-entites

.. method:: getSize()

	:returns: :mod:`Vec3`

	Hitbox size

.. method:: toString()

	:returns string:

.. method:: getViewAngles()

	:returns: :mod:`Vec3`

	returns a Vec3(Pitch, Yaw, 0)

.. method:: getYaw()

	:returns double:

.. method:: getPitch()

	:returns double: