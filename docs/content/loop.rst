Loopers
=======

A simple one-button looper. The button is :ref:`bound <Controller Bindings>` to ``looper record / fade out``.

The looper has five states.

   1. Idle

   2. Prepared
   
   3. Recording
   
   4. Looping
   
   5. Fading Out

Hitting the button advances the looper state from Idle to Prepared, and playing tuba advances from Prepared to Recording. After 8 bars or so, the looper automatically stops Recording and starts Looping. Hitting the button a second time begins Fading Out the looper over the course of 8 bars. A second loop can be recorded while the first's fading out.

The loopers can be muted via the ``mute loopers`` binding.

.. image:: media/loopers.png
   :width: 60%
   :align: center
   :alt: loopers

Below the two loopers are the post-loop :ref:`Stutter, Tremolo, & Filters <Main Stutter Tremolo & Filters>` 
The same bindings as ``Main Stutter Tremolo & Filters`` exist for the loopers.