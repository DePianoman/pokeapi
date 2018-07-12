PokéAPI
*******

Pokemon
=======
.. function:: def setPokemonByName(name, level)

	This sets what pokemon it is by name, and sets the level.

	:param name: The name of the Pokemon - *str*
	:param level: The level of the Pokemon - *int*

.. function:: def setPokemonByID(pid, level)

	This sets what pokemon it is by the Pokemon's National Dex ID, and sets the level

	:param id: The id of the Pokemon - *int*
	:param level: The level of the Pokemon - *int*

.. function:: def setAbility(choice)

	This sets what ability the Pokemon has by the three possible choices:

	- Ability 1
	- Ability 2
	- Hidden Ability

	:param choice: The chosen ability (can be ``1``, ``2``, or ``"H"``) - *int or str*

.. function:: def setLevel(level)

	This sets the level of the Pokemon
	
	:param level: The level of the Pokemon - *int*
