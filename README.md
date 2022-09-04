# plugin_sample

Each plugin includes a `pyproject.toml` file and a `setup.cfg` file. We introduce entry-points with desired group name in the `setup.cfg` file.
To use a plugin, go to its directory and install it with `pip install . `.  
After installing, that plugin is avalible in the main program, for example, `plugin_loader.py`.
