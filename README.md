# Winamp Driver for Karaoke Manager

A Winamp driver for [Karaoke Manager](https://github.com/peeveen/karaokemanager).

It relies on some Winamp plugins being installed.

- For CDG visuals, you need to have a suitable CDG plugin installed. [I heartily recommend this one](https://github.com/peeveen/gen_cdgPro), though [others are available](https://winampheritage.com/plugin/cdg-plug-in/100775).
- For key changes, you need to have the [Pacemaker plugin](https://www.surina.net/pacemaker/) installed.

### To use

- Install [the package](https://pypi.org/project/karaokemanagerwinampdriver/) with `pip install karaokemanagerwinampdriver`
- Edit your Karaoke Manager .yaml file, and set driver class to `karaokemanagerwinampdriver.winamp_driver.Driver`
- In the driver-specific section, you can add an `exe` string, set to the full path for `winamp.exe`. If you do this, Winamp will be launched when Karaoke Manager starts.
