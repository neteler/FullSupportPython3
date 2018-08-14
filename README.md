# FullSupportPython3
GSOC 2018 - GRASS GIS - Full support of Python 3 in GRASS GIS

![Project Image](https://raw.githubusercontent.com/sanjeetbhatti/FullSupportPython3/master/GSoC-final-report-project-pic.png)

There are patches in the respective directories in the grass_trunk.

**Patches** | **Patch for**
--- | ---
gui/patch_gui.diff | GUI (wxPython)
lib-python-ctypes/patch_ctypes_changes_from_fork.diff | ctypes library with latest changes from forked repo
lib-python-ctypes/patch_ctypes_old.diff | ctypes library with grass ctypes (old version)
lib-python-gunittest/patch_python_gunittest.diff | Gunittest library
lib-python-pydispatch/patch_pydispatch.diff | Pydispatch library
lib-python-pygrass/patch_pygrass.diff | Pygrass library
lib-python-script/patch_python_script.diff | Script library
lib-python-temporal/patch_temporal.diff | Temporal library
scripts/patch_trunk_scripts.diff | all the scripts in the trunk

These patches can be applied using `svn patch` command from the root directory of grass.
