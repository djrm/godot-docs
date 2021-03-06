.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the doc/base/classes.xml source instead.

.. _class_GradientTexture:

GradientTexture
===============

**Inherits:** :ref:`Texture<class_texture>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------



Member Functions
----------------

+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`add_point<class_GradientTexture_add_point>`  **(** :ref:`float<class_float>` offset, :ref:`Color<class_color>` color  **)** |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_color>`                    | :ref:`get_color<class_GradientTexture_get_color>`  **(** :ref:`int<class_int>` point  **)** const                                 |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PoolColorArray<class_poolcolorarray>`  | :ref:`get_colors<class_GradientTexture_get_colors>`  **(** **)** const                                                            |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                    | :ref:`get_offset<class_GradientTexture_get_offset>`  **(** :ref:`int<class_int>` point  **)** const                               |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PoolRealArray<class_poolrealarray>`    | :ref:`get_offsets<class_GradientTexture_get_offsets>`  **(** **)** const                                                          |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                        | :ref:`get_point_count<class_GradientTexture_get_point_count>`  **(** **)** const                                                  |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_color>`                    | :ref:`interpolate<class_GradientTexture_interpolate>`  **(** :ref:`float<class_float>` offset  **)**                              |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`remove_point<class_GradientTexture_remove_point>`  **(** :ref:`int<class_int>` offset  **)**                                |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_color<class_GradientTexture_set_color>`  **(** :ref:`int<class_int>` point, :ref:`Color<class_color>` color  **)**      |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_colors<class_GradientTexture_set_colors>`  **(** :ref:`PoolColorArray<class_poolcolorarray>` colors  **)**              |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_offset<class_GradientTexture_set_offset>`  **(** :ref:`int<class_int>` point, :ref:`float<class_float>` offset  **)**   |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_offsets<class_GradientTexture_set_offsets>`  **(** :ref:`PoolRealArray<class_poolrealarray>` offsets  **)**             |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_width<class_GradientTexture_set_width>`  **(** :ref:`int<class_int>` width  **)**                                       |
+----------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`float<class_float>` **colors**
- :ref:`float<class_float>` **offsets**
- :ref:`int<class_int>` **width**

Member Function Description
---------------------------

.. _class_GradientTexture_add_point:

- void  **add_point**  **(** :ref:`float<class_float>` offset, :ref:`Color<class_color>` color  **)**

.. _class_GradientTexture_get_color:

- :ref:`Color<class_color>`  **get_color**  **(** :ref:`int<class_int>` point  **)** const

.. _class_GradientTexture_get_colors:

- :ref:`PoolColorArray<class_poolcolorarray>`  **get_colors**  **(** **)** const

.. _class_GradientTexture_get_offset:

- :ref:`float<class_float>`  **get_offset**  **(** :ref:`int<class_int>` point  **)** const

.. _class_GradientTexture_get_offsets:

- :ref:`PoolRealArray<class_poolrealarray>`  **get_offsets**  **(** **)** const

.. _class_GradientTexture_get_point_count:

- :ref:`int<class_int>`  **get_point_count**  **(** **)** const

.. _class_GradientTexture_interpolate:

- :ref:`Color<class_color>`  **interpolate**  **(** :ref:`float<class_float>` offset  **)**

.. _class_GradientTexture_remove_point:

- void  **remove_point**  **(** :ref:`int<class_int>` offset  **)**

.. _class_GradientTexture_set_color:

- void  **set_color**  **(** :ref:`int<class_int>` point, :ref:`Color<class_color>` color  **)**

.. _class_GradientTexture_set_colors:

- void  **set_colors**  **(** :ref:`PoolColorArray<class_poolcolorarray>` colors  **)**

.. _class_GradientTexture_set_offset:

- void  **set_offset**  **(** :ref:`int<class_int>` point, :ref:`float<class_float>` offset  **)**

.. _class_GradientTexture_set_offsets:

- void  **set_offsets**  **(** :ref:`PoolRealArray<class_poolrealarray>` offsets  **)**

.. _class_GradientTexture_set_width:

- void  **set_width**  **(** :ref:`int<class_int>` width  **)**


