# Winamp Driver for KaraokeManager

A KaraokeManager driver for Winamp.

For key changes, you need to have the [Pacemaker plugin](https://www.surina.net/pacemaker/) installed.

### To use

- Install [the package](https://pypi.org/project/karaokemanagerwinampdriver/) with `pip install karaokemanagerwinampdriver`
- Edit your KaraokeManager .yaml file, and set driver class to `karaokemanagerwinampdriver.winamp_driver.Driver`
- In the driver-specific section, you can add an `exe` string, set to the path where `winamp.exe` can be found. If you do this, Winamp will be launched when KaraokeManager starts.
