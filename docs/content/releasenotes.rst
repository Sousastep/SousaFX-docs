Release Notes
=============

0.9.4
-----

SousaFX 
~~~~~~~~~~~~~

- Works in time signatures other than 4/4

- Transients can trigger :ref:`octaver <Octaver>` synth ramp down

- :ref:`Startup Preferences <startupprefs>` can launch custom Ableton projects.

- :ref:`Looper <Loopers>` can auto-record after main audio input drops below the noise gate a certain number of times.

- After the looper's done fading out, the auto-preset change now waits until the tuba stops playing.

- Drum and looper mute buttons now unmute when held, and toggle mute when single-clicked.

- Main output sidechained to the talkback mic.

- :ref:`Lowpass filter type <Select Lowpass Filter Type>` can randomize when looper finishes fading out.

- Initial preset can be set for the :ref:`bindings <Controller Bindings>` and :ref:`main presets <Main Presets>`.

- Refactor envelopes and add :ref:`main envelope sensitivity <Main Envelope>` parameter.

- Allow :ref:`delay sends <swirl>` to feedback into eachother

- Allow :ref:`RNBO compressors' <Mix Bus>` sidechain EQ's midfreq to boost up to 36 dB.

- Allow :ref:`post-crossfade FX <postxfadefx>` to effect the attack signal path, sustain signal path, or both, and let this be set by looper status.

- Add :ref:`BasicFX <BasicFX>` for using SousaVFX without SousaFX.


SousaPlayback 
~~~~~~~~~~~~~~~~~~~

- On startup, enable Live Link.

- On startup, play first scene, and select second scene.

- Next scene auto-plays when SousaFX's looper finishes fading out.

- Talkback mic auto-mutes itself when tuba starts playing.


SousaVFX 
~~~~~~~~~~~~~~

- Improve efficiency by using ``xray.jit.cellvalue`` instead of ``getcell``

- Remove Twitch bot. Will return later. 

|

0.9.3
-----

- First release! 🥳

|

Known Bugs
----------

.. note:: 
	
	Feel free to submit bug reports or feature requests to `GitHub Issues <https://github.com/Sousastep/sousastep/issues>`_

- plugin selectors can only clear plugin slot by manually deleting json file in data folder.

- the About window shows "0 0" as install date on first boot.

- four rnbo filterdelays can't load at once, but three can. So if delay send 4 is bypassed, which it is by default, it will insta-feedback when opened, so no bindings are connected to it by default.

- :ref:`Param Control Logic's <Parameter Control Logic>` "This control is mapped to the joystick" message is only correct on load and won't update when switching presets. It will update when manually adding and removing connections.

