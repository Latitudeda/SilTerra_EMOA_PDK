PDK structure
======================

Process Design Kit (PDK) is a tool for designated users to generate circuit layouts based on SilTerra design rules and technology settings.

``SilTerra_EMOA_PDK_rev6p0_Latitude`` package includes five subfolders: ``components``, ``examples``,  ``schematic``, ``symbols`` and ``technology``.

* ``components``

    * Parametrized cells (PCells): Designed by **Latitude**, including ``Bend``, ``Straight``, etc. Please see ``gpdk > components`` for more designed components by **Latitude**.

* ``examples``

    * ``tech_test.py`` : Test that waveguide types, metal wire types, auto routing, auto link and auto vias function work normally under the PDK setting. Please see ``gpdk > examples`` for more circuit examples.

* ``schematic``

    * Store the schematic setting for linking PhotoCAD to AdvancedSDL.

* ``symbols``

    * Store the symbol setting for linking PhotoCAD to AdvancedSDL.

* ``technology``

    * Store the technology setting which matched the SilTerra design rules. We recommend users not to change the settings in technology folder.

    * See chapter ``Technology setting`` for more specific definition.

* ``SilTerra_EMOA_PDK_rev6p0_Latitude.lyp`` : This file allows layout tools e.g. KLayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp.png
       :width: 80%
