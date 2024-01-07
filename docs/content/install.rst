💾 Installation
===============

Required
--------

1. `Download Max <https://cycling74.com/downloads>`_ from Cycling '74. 

2. Open Max, click "Menubar > Max > Preferences...", and set the following preferences:
        
    - Interface > Restore Windows on Launch [uncheck]
    
    - RNBO > Start RNBO Server on Launch [uncheck]
    
    - Mixer > Enable Mixer Parallel Processing [check]

3. Click "Menubar > File > Show Package Manager", and install the following packages:

    - ease

    - link

    - RNBO Synth Building Blocks

    - ISF

4. There will probably be a bunch of operating system security settings that you have to enable for Max as well.

5. `Download sousastep <https://github.com/Sousastep/sousastep/releases/latest>`_ to your `~/Documents/Max 8/Projects/` folder. `sousastep` contains SousaFX, SousaVFX, and SousaPlayback.

.. note::

    SousaFX remains fully operational after Max's `30 day trial ends <https://support.cycling74.com/hc/en-us/articles/360049995834-Max-8-Max-7-Authorization#link-2>`_ thanks to Max not disabling `pattrstorage <https://docs.cycling74.com/max8/refpages/pattrstorage>`_.

.. important::

    When updating to new versions of SousaFX, copy all files from `~/Documents/Max 8/Projects/sousastep/SousaFX/data/` to the new version's `sousastep/SousaFX/data/` folder to ensure that your presets are carried over.

Optional
--------

6. To open the SousaPlayback template project (`~/Documents/Max 8/Projects/sousastep/default/SousaPlayback template Project/SousaPlayback template.als`), [download Live Suite](https://www.ableton.com/en/trial/) from Ableton.

    Open Live, click "Menubar > Live > Settings...", and set the following preferences:

    - Audio > Audio Device [set preferred interface]

    - Audio > In/Out Sample Rate [48000]

    - Audio > Buffer Size [256]

    - Link Tempo MIDI > MIDI Ports

        - In: from Max 1 - Remote [check]

        - Out: to Max 1 - Track [check]

.. note::

    The SousaPlayback template project will not work after Ableton's `free trial <https://www.ableton.com/en/trial/>`_ ends. The template uses a few Max for live devices that require Ableton Live 11/12 `Suite or Standard with the Max for Live addon <https://help.ableton.com/hc/en-us/articles/360000036850-Max-for-Live-bundled-in-Live>`_.

7. Download Black Octopus Sound's `excellent free samples <https://blackoctopus-sound.com/product/free-1gb-of-black-octopus-samples/>`_ and place `Black Octopus Sound - Free Samples Bundle` into `~/Documents/Max 8/Projects/sousastep/SousaFX/default/SousaPlayback template Project/Clips/`

Recommended Free Plugins
------------------------

9.  `Sonobus <https://sonobus.net/#download>`_, for networked jamming with folks in the same continent.

10.  `Jamtaba <https://github.com/elieserdejesus/JamTaba/releases>`_, for networked jamming with folks in different continents.

> [!NOTE]
> Sonobus or Jamtaba may be placed in SousaPlayback's "NETWORK" track.

11. `ToneLib BassDrive <https://tonelib.net/tl-bassdrive.html>`_ "Ready to unleash the true power of the lowest guitar frequencies."

12. `Valhalla Super Massive <https://valhalladsp.com/shop/reverb/valhalla-supermassive/>`_ "Designed from the ground up for MASSIVE delays and reverbs."

13.  `Kilohearts Essentials <https://kilohearts.com/products/kilohearts_essentials>`_ "A free collection of extremely useful effects."

14.  `Melda Production <https://www.meldaproduction.com/MFreeFxBundle>`_ "The biggest and the most powerful free plugins pack available."

15. `Why Reaper <https://whyreaper.com/plugins-resources/>`_ "Free and/or inexpensive resources for professional computer-based music production."