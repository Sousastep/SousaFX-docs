Tickets
=======

Feel free to submit bug reports or feature requests to `GitHub Issues <https://github.com/Sousastep/sousastep/issues>`_


Known Bugs
----------

- plugin selectors can only clear plugin slot by manually deleting json file in data folder.

- the About window shows "0 0" as install date on first boot.

- four rnbo filterdelays can't load at once, but three can. So if delay send 4 is bypassed, which it is by default, it will insta-feedback when opened, so no bindings are connected to it by default.

    - implement max4cats delay fx as a choice for the delay sends. involves refactoring or making another version of plugin_selector

- :ref:`Param Control Logic's <Parameter Control Logic>` "This control is mapped to the joystick" message is only correct on load and won't update when switching presets. It will update when manually adding and removing connections. It also can't say when it's bound to a button.

- to initialize properly, the gamepad's joysticks must be jiggled after connecting to Max, which'll happen eventually anyways.

