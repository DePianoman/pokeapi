PokéAPI
*******

The Unofficial Pokemon API for Python! Powered by:

- https://bulbapedia.bulbagarden.net
- https://pokemondb.net/

If you have any problems: E-mail me at `depianoman2004@gmail.com <mailto:depianoman2004@gmail.com>`_

Functions
=========

.. function:: def IDfromPokemon(name)

	This function returns the name of a Pokemon from its National Dex ID

	:param name: The name of the Pokemon - *str*

.. function:: def PokemonfromID(pid)

	This function returns the National Dex ID from a Pokemon's name

	:param pid: The National Dex ID of the Pokemon - *int*

.. function:: def PokemonLearnset(name, generation)

	This function returns the Learnset in the form::

		{ 1: [["Growl", 40, 0, 100, "Normal", "Status"], ["Tackle", 35, 40, 100, "Normal", "Physical"], 7: ...}
		# Level: [[Move, PP, Power, Accuracy, Type, Status/Special/Physical], [Other Move...

	:param name: The name of the Pokemon - *str*
	:param generation: The generation of game learnset is in - *int*

.. function:: def PokemonLocations(name, game)

	This function returns the locations in ``', '.join(["Location1", "Location2"])`` form
	
	:param name: The name of the Pokemon - *str*
	:param game: The game you want the locations from - *str*

.. function:: def PokemonTypes(name)

	This function returns a list of the types of the Pokemon

	:param name: The name of the Pokemon - *str*

.. function:: def PokemonSprite(name)

	This function returns a URL of the Pokemon's sprite

	:param name: The name of the Pokemon - *str*
 
.. function:: def ShinyPokemonSprite(name)

	This function returns a URL of the Pokemon's Shiny sprite

	:param name: The name of the Pokemon - *str*

.. function:: def PokemonAbilities(name)

	This function returns a 3-element list of the Abilities a Pokemon has in the order: ``[Ability1, Ability2, HiddenAbility]``

	:param name: The name of the Pokemon - *str*


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
