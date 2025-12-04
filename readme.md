# NOTE
these changes have since been accepted into https://github.com/scientific-python/spec0-action and therefore this one is no longer maintained. The repo will exist for some time as an archive and eventually be removed. Please post any issues or PRs there.


# SPEC 0 Support Schedule

This repository provides human- and machine-readable artifacts for the [SPEC 0 support schedule](https://scientific-python.org/specs/spec-0000/) endorsed by the [Scientific Python Project](https://github.com/scientific-python/).

It primarily exists to publish generated versions of the dependency schedule. Most users will not need to use this repository directly. If you are looking for automation, see the companion GitHub Action: [update-spec0-dependencies](https://github.com/savente93/update-spec0-dependencies).

The schedule is updated every quarter.

## Usage

* **Machine-readable format:** `schedule.json`
* **Human-readable formats:**

  * `schedule.md`: Markdown table of versions to drop support for by quarter
  * `chart.md`: Visualization of the current support schedule

## Modifications and Licensing

This repository adapts the script [`SPEC0_versions.py`](https://github.com/scientific-python/specs/blob/main/spec-0000/SPEC0_versions.py) from the Scientific Python Project, originally licensed under the **BSD-3-Clause License**.

Changes by **Sam Vente** include:

* Adding generation of a JSON payload with the newest lower supported bounds of SPEC 0 dependencies, to support automation.

Copyright (c) 2025 Sam Vente
Licensed under the BSD-3-Clause License.

The original copyright notice and BSD-3 license text are preserved in this repository.
 

A proposal has been made to merge this work into the main Scientific Python Project. Until that process concludes, this repository provides an independent version for users.

However it is not currently associated or endorsed by the Scientific Python Project. 

