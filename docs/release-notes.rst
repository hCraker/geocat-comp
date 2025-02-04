.. currentmodule:: geocat.comp

.. _release:
Release Notes
=============

v2023.03.1 (Mar 23, 2023)
-------------------------

Bug Fixes
^^^^^^^^^
* Add dpres_plev init file by `Heather Craker`_ in (:pr:`368`)
* Fix argument checks for interp_hybrid_to_pressure by `Heather Craker`_ in (:pr:`372`)
* Extrap args fix by `Heather Craker`_ in (:pr:`369`)
* Revert "Extrap args fix" by `Heather Craker`_ in (:pr:`371`)

Documentation
^^^^^^^^^^^^^
* Create a utility function to generate docstrings on wrapper functions by `Anissa Zacharias`_ in (:pr:`362`)
* adjust calendar example to follow similar template by `Julia Kent`_ in (:pr:`339`)
* Update release notes for v2023.03.0 by `Heather Craker`_ in (:pr:`365`)

Misc
^^^^
* version bump 2023 03 1 by `Alea Kootz`_ in (:pr:`379`)

**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2023.03.0...v2023.03.1

v2023.03.0 (Mar 2, 2023)
------------------------

New Features
^^^^^^^^^^^^
* Adding method to calculate delta pressure by `Julia Kent`_ in (:pr:`338`)

Deprecations
^^^^^^^^^^^^
* Remove deprecated functions from v2022.10.0 by `Heather Craker`_ in (:pr:`357`)
* Remove links to deleted function docs by `Heather Craker`_ in (:pr:`359`)
Bug Fixes
^^^^^^^^^
* Partial fix for _vertical_remap_extrap bug by `Heather Craker`_ in (:pr:`360`)

Documentation
^^^^^^^^^^^^^
* Fix typos in PR template by `Heather Craker`_ in (:pr:`353`)
* add climatology_average example by `Julia Kent`_ in (:pr:`341`)
* Fix some delta_pressure docs formatting by `Heather Craker`_ in (:pr:`361`)

Maintenance
^^^^^^^^^^^
* Add PR template to repository by `Heather Craker`_ in (:pr:`344`)
* Fix typos by `Heather Craker`_ in (:pr:`347`)
* Change conda badge to conda-forge channel by `Heather Craker`_ in (:pr:`349`)

New Contributors
^^^^^^^^^^^^^^^^
* `Julia Kent`_ made their first contribution in (:pr:`341`)

**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2023.02.0...v2023.03.0

v2023.02.0 (Feb 2, 2023)
------------------------

New Features
^^^^^^^^^^^^
* Add extrapolation feature to interp_hybrid_to_pressure by `Heather Craker`_ in (:pr:`237`)
* Add ``climate_anomaly`` by `Heather Craker`_ in (:pr:`332`)

Enhancements
^^^^^^^^^^^^
* Add check to avoid calculating monthly averages on monthly data by `Heather Craker`_ in (:pr:`304`)
* Add ``keep_attrs`` to climatology functions by `Heather Craker`_ in (:pr:`315`)

Deprecations
^^^^^^^^^^^^
* Fix pint bug in showalter_index and deprecate by `Heather Craker`_ in (:pr:`319`)
* Replace and deprecate ``anomaly`` and ``climatology`` by `Heather Craker`_ in (:pr:`332`)

Documentation
^^^^^^^^^^^^^
* Add rendered equations to docstrings by `Anissa Zacharias`_ in (:pr:`294`)
* Fix badge links by `Anissa Zacharias`_ in (:pr:`321`)

Maintenance
^^^^^^^^^^^
* Adding import nightly CI test by `Anissa Zacharias`_ in (:pr:`300`)
* Expand upstream CI by `Anissa Zacharias`_ in (:pr:`301`)
* Patch for import test by `Anissa Zacharias`_ in (:pr:`302`)
* Fix the import package CI test by `Anissa Zacharias`_ in (:pr:`303`)
* CI failures quick patch by `Anissa Zacharias`_ in (:pr:`312`)
* Resolve CI link-check issue by `Anissa Zacharias`_ in (:pr:`316`)
* Pin numpy for numba compatibility by `Anissa Zacharias`_ in (:pr:`325`)
* Improve speed of spherical harmonics tests by `Alea Kootz`_ in (:pr:`327`)
* Converting pytest to unittest for ``climatology.py`` by `Heather Craker`_ in (:pr:`331`)
* Allow upstream-dev to run on forks by `Anissa Zacharias`_ in (:pr:`335`)


**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2022.11.0...v2023.02.0


v2022.11.0 (Nov 17, 2022)
-------------------------

Documentation
^^^^^^^^^^^^^
* Docstring improvements by `Heather Craker`_ in (:pr:`284`)
* Update dependency list by `Heather Craker`_ in (:pr:`293`)


Maintenance
^^^^^^^^^^^
* Module reorganization by `Heather Craker`_ in (:pr:`266`)
* Update to conda-build badge link by `Mario Rodriguez`_ in (:pr:`288`)

**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2022.10.1...v2022.11.0


v2022.10.1 (Oct. 28, 2022)
--------------------------

Bug Fixes
^^^^^^^^^
* Pinned Pint version by `Mario Rodriguez`_ in (:pr:`281`)


**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2022.10.0...v2022.10.1


v2022.10.0 (Oct. 21, 2022)
--------------------------
New Features
^^^^^^^^^^^^
* Gradient, arc_lon_wgs84, arc_lat_wgs84, rad_lat_wgs84 by `Alea Kootz`_ in (:pr:`256`)

Documentation
^^^^^^^^^^^^^
* Creating quick start guide as part of overall docs improvements by `Heather Craker`_ in (:pr:`249`)
* Documentation style overhaul by `Anissa Zacharias`_ in (:pr:`260`)

Maintenance
^^^^^^^^^^^
* Make local install for docs better by `Anissa Zacharias`_ in (:pr:`273`)
* Documentation and Link Checker by `Anissa Zacharias`_ in (:pr:`274`)



**Full Changelog**: https://github.com/NCAR/geocat-comp/compare/v2022.08.0...v2022.10.0

..
    Add new names and GitHub links as needed

.. _`Heather Craker`: https://github.com/hCraker
.. _`Anissa Zacharias`: https://github.com/anissa111
.. _`Alea Kootz`: https://github.com/pilotchute
.. _`Mario Rodriguez`: https://github.com/marodrig
.. _`Julia Kent`: https://github.com/jukent
