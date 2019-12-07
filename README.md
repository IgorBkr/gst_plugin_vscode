# gst_plugin_vscode
This is an example of building a basic GStreamer plugin with VSCode/GCC.
(Not with meson/ninja as in original gst-template)

Open 'gstmyfilter.c' and run "gcc build shared library from active file" (from tasks.json) to build the plugin (libgstmyfilter.so).

NOTE: launch.json has hardcoded test app, and a path to media file - replace with relevant values (see TODO in the file).
