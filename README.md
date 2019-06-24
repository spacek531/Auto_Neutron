# Auto-Neutron
Auto Neutron is an utility tool for neutron routes created using Spansh's route plotter or for CSV files that use spansh's syntax
## Dependencies
* <a href="https://pypi.org/project/PyQt5/">PyQt5</a>
* <a href="https://autohotkey.com/">AutoHotkey</a>
* <a href="https://pypi.org/project/ahk/">ahk python module</a>


# Application
The Auto Neutron app works by starting a new AutoHotkey script (located in settings) every time the current waypoint is reached with the "|SYSTEMDATA|" part being replaced with the next system
## Features
* Built in neutron plotter using Spansh's api
* Saving of routes
* Skipping jumps using doubleclick
