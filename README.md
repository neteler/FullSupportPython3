# FullSupportPython3
GSOC 2018 - GRASS GIS - Full support of Python 3 in GRASS GIS

![Project Image](https://raw.githubusercontent.com/sanjeetbhatti/FullSupportPython3/master/GSoC-final-report-project-pic.png)

There are patches in the respective directories in the grass_trunk.

**Patches** | **For**
--- | ---
gui/patch_gui.diff | Patch for GUI (wxPython)
lib-python-ctypes/patch_ctypes_changes_from_fork.diff | Patch for ctypes library with latest changes from forked repo
lib-python-ctypes/patch_ctypes_old.diff | Patch for ctypes library with grass ctypes (old version)
lib-python-gunittest/patch_python_gunittest.diff | Patch for Gunittest library
lib-python-pydispatch/patch_pydispatch.diff | Patch for Pydispatch library
lib-python-pygrass/patch_pygrass.diff | Patch for Pygrass library
lib-python-script/patch_python_script.diff | Patch for Script library
lib-python-temporal/patch_temporal.diff | Patch for Temporal library
scripts/patch_trunk_scripts.diff | Patch for all the scripts in the trunk

These patches can be applied using `svn patch` command from the root directory of grass.
