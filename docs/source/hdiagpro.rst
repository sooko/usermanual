HDiag Pro
=========



Hardware Overview
-----------------
- 1. HDiagPro Hardware
- 2. BLE Dongle
- 3. DLC Connector
- 4. Euro 5 DLC Connector
- 5. 12 volt Adaptor
- 6. Backdor kit
- 7. USB Cable


Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

