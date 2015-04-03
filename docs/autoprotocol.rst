============
autoprotocol
============

autoprotocol.protocol
---------------------

protocol.Protocol
~~~~~~~~~~~~~~~~~

.. autoclass:: autoprotocol.protocol.Protocol

Protocol.container_type()
^^^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.container_type

Protocol.ref()
^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.ref

Protocol.append()
^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.append

Protocol.as_dict()
^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.as_dict

Protocol.distribute()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.distribute

Protocol.transfer()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.transfer

Protocol.dispense()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.dispense

Protocol.dispense_full_plate()
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.dispense_full_plate

Protocol.stamp()
^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.stamp

Protocol.sangerseq()
^^^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.sangerseq

Protocol.mix()
^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.mix

Protocol.spin()
^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.spin

Protocol.thermocycle()
^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.thermocycle

Protocol.incubate()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.incubate

Protocol.absorbance()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.absorbance

Protocol.fluorescence()
^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.fluorescence

Protocol.luminescence()
^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.luminescence

Protocol.gel_separate()
^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.gel_separate

Protocol.seal()
^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.seal

Protocol.unseal()
^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.unseal

Protocol.cover()
^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.cover

Protocol.uncover()
^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.uncover

Protocol.spread()
^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.spread

Protocol.autopick()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.protocol.Protocol.autopick

protocol.Ref
~~~~~~~~~~~~

.. autoclass:: autoprotocol.protocol.Ref


autoprotocol.container
----------------------

container.Container
~~~~~~~~~~~~~~~~~~~
.. autoclass:: autoprotocol.container.Container

Container.well()
^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.well

Container.wells()
^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.wells

Container.robotize()
^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.robotize

Container.humanize()
^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.humanize

Container.decompose()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.decompose

Container.all_wells()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.all_wells

Container.wells_from()
^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.wells_from

Container.inner_wells()
^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Container.inner_wells

container.Well
~~~~~~~~~~~~~~
.. autoclass:: autoprotocol.container.Well

Well.set_properties()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Well.set_properties

Well.add_properties()
^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Well.add_properties

Well.set_volume()
^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Well.set_volume

Well.humanize()
^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Well.humanize

Well.__repr__()
^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.Well.__repr__

container.WellGroup
~~~~~~~~~~~~~~~~~~~
.. autoclass:: autoprotocol.container.WellGroup

WellGroup.set_properties()
^^^^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.set_properties

WellGroup.indices()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.indices

WellGroup.append()
^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.append

WellGroup.__getitem__()
^^^^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.__getitem__

WellGroup.__len__()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.__len__

WellGroup.__repr__()
^^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.__repr__

WellGroup.__add__()
^^^^^^^^^^^^^^^^^^^
.. automethod:: autoprotocol.container.WellGroup.__add__

autoprotocol.container_type
---------------------------

container_type.ContainerType
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: autoprotocol.container_type.ContainerType

ContainerType.robotize()
^^^^^^^^^^^^^^^^^^^^^^^^

.. automethod:: autoprotocol.container_type.ContainerType.robotize

ContainerType.humanize()
^^^^^^^^^^^^^^^^^^^^^^^^

.. automethod:: autoprotocol.container_type.ContainerType.humanize

ContainerType.decompose()
^^^^^^^^^^^^^^^^^^^^^^^^^

.. automethod:: autoprotocol.container_type.ContainerType.decompose

ContainerType.row_count()
^^^^^^^^^^^^^^^^^^^^^^^^^

.. automethod:: autoprotocol.container_type.ContainerType.row_count


autoprotocol.unit
-----------------

unit.Unit
~~~~~~~~~

.. autoclass:: autoprotocol.unit.Unit

Unit.fromstring()
^^^^^^^^^^^^^^^^^

.. automethod:: autoprotocol.unit.Unit.fromstring


autoprotocol.util
-----------------

util.make_dottable_dict
~~~~~~~~~~~~~~~~~~~~~~~

.. autoclass:: autoprotocol.util.make_dottable_dict

util.deep_merge_params()
~~~~~~~~~~~~~~~~~~~~~~~~

.. autofunction:: autoprotocol.util.deep_merge_params

autoprotocol.harness
--------------------

harness.run()
~~~~~~~~~~~~~

.. autofunction:: autoprotocol.harness.run

harness.Manifest
~~~~~~~~~~~~~~~~

.. autoclass:: autoprotocol.harness.Manifest


.. autoprotocol.container_type
.. ---------------------------

.. .. automodule:: autoprotocol.container_type
..     :members:
..     :show-inheritance:

.. autoprotocol.harness
.. --------------------

.. .. automodule:: autoprotocol.harness
..     :members:
..     :show-inheritance:

.. autoprotocol.instruction
.. ------------------------

.. .. automodule:: autoprotocol.instruction
..     :members:
..     :show-inheritance:

.. autoprotocol.protocol
.. ---------------------

.. .. automodule:: autoprotocol.protocol
..     :members:
..     :show-inheritance:


.. autoprotocol.unit
.. -----------------

.. .. automodule:: autoprotocol.unit
..     :members:
..     :show-inheritance:

.. autoprotocol.util
.. -----------------

.. .. automodule:: autoprotocol.util
..     :members:
..     :show-inheritance:
