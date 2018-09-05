# PyMeeus
> **Library of astronomical algorithms in Python**.

PyMeeus is a Python implementation of the astronomical algorithms described in
the classical book "Astronomical Algorithms, 2nd Edition, Willmann-Bell Inc.
(1998)" by Jean Meeus.

There are great astronomical libraries out there. For instance, if you're
looking for high precision and speed you should take a look at
[libnova](http://libnova.sourceforge.net/). For a set of python modules aimed
at professional astronomers, you should look at [Astropy](http://www.astropy.org/).
On the other hand, the advantages of PyMeeus are its simplicity, ease of use,
ease of reading, ease of installation (it has the minimum amount of
dependencies) and abundant documentation.

## Installation

The easiest way of installing PyMeeus is using pip:

```sh
pip install pymeeus
```

Or, for a per-user installation:

```sh
pip install --user pymeeus
```

## Meta

Author: Dagoberto Salazar

Distributed under the GNU Lesser General Public License v3 (LGPLv3). See
``LICENSE.txt`` and ``COPYING.LESSER`` for more information.

Documentation: [https://pymeeus.readthedocs.io/en/latest/](https://pymeeus.readthedocs.io/en/latest/)

GitHub: [https://github.com/architest/pymeeus](https://github.com/architest/pymeeus)

## Contributing

The preferred method to contribute is through forking and pull requests:

1. Fork it (<https://github.com/architest/pymeeus/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

Please bear in mind that PyMeeus follows the PEP8 style guide for Python code
[(PEP8)](https://www.python.org/dev/peps/pep-0008/?). We suggest you install
and use a linter like [Flake8](http://flake8.pycqa.org/en/latest/) before
contributing.

Additionally, PyMeeus makes heavy use of automatic tests. As a general rule,
every function or method added must have a corresponding test in the proper
place in `tests` directory.

Finally, documentation is also a big thing here. Add proper and abundant
documentation to your new code. This also includes in-line comments!!!.

## What's new

* 0.1.6
    * Added function 'times_rise_transit_set()' to Coordinates module
* 0.1.5
    * Added functions for parallactic angle, ecliptic points in the horizon, angle between north celestial pole and north pole of the ecliptic, and diurnal path vs. the horizon at time of rising or setting
* 0.1.4
    * Added several conversion functions to Coordinates module
* 0.1.3
    * Added Coordinates module
* 0.1.2
    * Added precession and proper motion methods, and changed handling of Epoch class
* 0.1.1
    * Added methods related to nutation corrections
* 0.1.0
    * Earth class added
* 0.0.9
    * Significant documentation improvements
* 0.0.8
    * Epoch class finished
* 0.0.7
    * Epoch class added
* 0.0.6
    * CurveFitting class added
* 0.0.5
    * Interpolation class added
* 0.0.4
    * Angle class finished
* 0.0.3
    * Removed unnecessary dependencies
* 0.0.2
    * Documentation improvements
* 0.0.1
    * Initial commit

