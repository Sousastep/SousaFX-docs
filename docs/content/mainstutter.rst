Main Stutter Tremolo & Filters
==============================

Six parameters here are available in the :ref:`bindings <Controller Bindings>`. Both the stutter and tremolo's subdivisions are attached to the binding's subdivisions.

.. image:: media/mainstutter.png
   :width: 65%
   :align: center
   :alt: loopers

Stutter
-------

Inspired by `Pioneer's Stutter FX <https://www.youtube.com/watch?v=hb0XLX0b4Y4&t=972s>`_, this stutter is unique in that it does its best to retime the stutter after it accelerates and returns to its original speed.

Parameters
~~~~~~~~~~

:button: 

   Selects a random subdivision. Bound to ``Main Input Stutter Random Rhythm (trig)``

:No Stut:

   Toggle stutter on and off. Bound to ``Main Input Stutter Enable (trig)``

:vol dip:

   Determines how much the stutter volume will decrease as the acceleration increases from neutral.

:offset:

   Positive offset can improve transients at the beginning of the loop by shifting them outside of the declick window.

:window:

   Prevents clicks by quickly muting the stutter at the loop point. Determines how long muting should take.

:accel:

   Slow down and speed up the stutter FX. Bound to ``Main Input Stutter Accel (bi)``

:stutter volume:

   The volume of the stutter.

:subdivision menu:

   The rhythm of the subdivision. Attached to binding's subdivisions.

:sync:

   Same as the subdivision menu.

:gated or thru:

   Should the input be gated by the stutter, 
   or always pass through regardless of if the stutter is occuring? 
   This may be hardcoded to change dynamically. Don't worry about it.

Tremolo 
-------

A simple, musical, square-wave tremolo.

Parameters
~~~~~~~~~~

:depth mix: 

   Amount of tremolo. Bound to ``Main Input Tremolo Depth (uni)``

:duty cycle: 

   The fraction of one period in which the signal is active. Bound to ``Main Input Tremolo Duty (bi)``

   .. image:: media/PWM_duty_cycle_with_label.gif
      :width: 20%
      :align: center
      :alt: duty

Filter
------

Also inspired by Pioneer, a classic DJ filter.

Parameters
~~~~~~~~~~

:filter sweep:

   Bypass at 50%. Approaching 100% is a lowpass sweep up, and approaching 0% is a highpass sweep down. The filters are an MS20-like 24 dB/oct `Sallen Key filter <https://en.wikipedia.org/wiki/Sallen%E2%80%93Key_topology>`_ by :ref:`Surreal Machines <SousaFX Max Patches>`. Bound to ``Main Input Filters (bi)``

:smooth:

   Smooths the filter frequency modulation. If mapped to a joystick, lower values follow the joystick more closely, while higher values glide towards the joystick.





