💾 Installation
===============

|

SousaFX
-------

1. `Download Max <https://cycling74.com/downloads>`_ from Cycling '74. 

2. Open Max, go to ``Menubar > Max > Preferences...``, and set the following preferences:
        
    - Interface > Restore Windows on Launch [uncheck]
    
    - Mixer > Enable Mixer Parallel Processing [check]

3. Open Max's Package Manager: ``Menubar > File > Show Package Manager``, and install the following packages:

    - ease

    - link

    - RNBO Synth Building Blocks

    - ISF

4. Add ``/sousastep/`` to Max's global search path: Go to ``Menubar > Options... > File Preferences...``, "Add Path" +, "choose", and select ``~/Documents/​Max 8/​Project/​sousastep``.

5. `Download sousastep <https://github.com/Sousastep/sousastep/releases/latest>`_ to your ``~/Documents/​Max 8/​Projects/`` folder. ``sousastep`` contains SousaFX, SousaVFX, and SousaPlayback.

.. important::

    SousaFX remains fully operational after Max's `30 day trial ends <https://support.cycling74.com/hc/en-us/articles/360049995834-Max-8-Max-7-Authorization#link-2>`_ thanks to Max not disabling `pattrstorage <https://docs.cycling74.com/max8/refpages/pattrstorage>`_.

|

SousaPlayback
-------------

6. To open the SousaPlayback template project ``~/Documents/​Max 8/​Projects/​sousastep/​default/​SousaPlayback template Project/​SousaPlayback template.als``, `download Live Suite <https://www.ableton.com/en/trial/>`_ from Ableton.

    Open Live, click ``Menubar > Live > Settings...``, and set the following:

    a. Audio > Audio Device [select your audio interface]

    b. Audio > In/Out Sample Rate [48000]

    c. Audio > Buffer Size [256]

    d. File Folder > Max Application > browse for ``/Applications/Max.app``

    e. Link Tempo MIDI > MIDI Ports

        f. In: from Max 1 - Remote [check]

        g. Out: to Max 1 - Track [check]


.. important::

    The SousaPlayback template project will not work after Ableton Live's `free trial <https://www.ableton.com/en/trial/>`_ ends. The template uses Max for live devices that require Ableton Live 11/12 Suite or Standard with the Max for Live addon.

7. Download Black Octopus Sound's `excellent free samples <https://blackoctopus-sound.com/product/free-1gb-of-black-octopus-samples/>`_ and place `Black Octopus Sound - Free Samples Bundle` into ``~/Documents/​Max 8/​Projects/​sousastep/​SousaFX/​default/​SousaPlayback template Project/​Clips/``

|

Updating
--------
When updating to new versions of SousaFX, 
copy all files from 
``~/Documents/​Max 8/​Projects/​sousastep/​SousaFX/​data/`` 
to the new version's 
``sousastep/​SousaFX/​data/`` 
folder to ensure that your presets are carried over.

|

Recommended Free Plugins
------------------------

1.  `Sonobus <https://sonobus.net/#download>`_ for networked jamming with folks in the same continent.

2.  `Jamtaba <https://github.com/elieserdejesus/JamTaba/releases>`_ for networked jamming with folks in different continents.

Sonobus or Jamtaba may be placed in SousaPlayback's "NETWORK" track.

3. `ToneLib BassDrive <https://tonelib.net/tl-bassdrive.html>`_ "Ready to unleash the true power of the lowest guitar frequencies."

4. `Valhalla Super Massive <https://valhalladsp.com/shop/reverb/valhalla-supermassive/>`_ "Designed from the ground up for MASSIVE delays and reverbs."

5.  `Kilohearts Essentials <https://kilohearts.com/products/kilohearts_essentials>`_ "A free collection of extremely useful effects."

6.  `Melda Production <https://www.meldaproduction.com/MFreeFxBundle>`_ "The biggest and the most powerful free plugins pack available."
