In this directory, you can add more resources that you want to bundle in your package.
So you cana arbitrary overload your package, but you should follow standard Funz directory structure:

  * lib/ will contains .dll, .so, .jar, ... that will be loaded at Funz startup
  * scripts/ will contains .sh, .bat scripts to launch calculations
  * plugins/io/ contains .jar or .ioplugin parsing plugins
  * plugins/doe/ contains .R algorithms
  * plugins/calc/ contains .cplugin.jar plugins to follow running calculations (for real-time reporting or manage errors)
