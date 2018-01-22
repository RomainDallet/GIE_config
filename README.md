# GIE_config

Here is the ![Jupyter Docker container](https://github.com/bgruening/docker-jupyter-notebook) I use.

The jupyter folder come from $GALAXY_PATH/config/plugins/interactive_environments/

And below, where are the different configuration files.

	/etc/nginx/
	|
	+-- conf.d/galaxyconf.d
	|
	+-- sites-available/galaxy
	|
	+-- sites-enabled/galaxy -> sites-available/galaxy
	|
	+-- nginx.conf
