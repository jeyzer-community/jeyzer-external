# jeyzer-external
The Jeyzer External project is a facade - for build and dev run purposes - over the external libraries, external repositories and related common resources.
It must contain the master branch of the .


Prerequisites
------------------

**IMPORTANT** :
To setup this project, you must under the jeyzer-external/lib directory :

- Clone the Graphstream alt library : 
  git clone https://github.com/jeyzer-community/graphstream-core-alt

- Clone the Retrace alt library :
  git clone https://github.com/jeyzer-community/retrace-alt


Usage
------------------

- The Jeyzer Web Analyzer will load the external repositories from this directory in a developer environment, 
  assuming that the local_first is set in the base.xml.

- The Maven build will build the external libraries.


Build instructions
------------------

The jeyzer-all project is responsible for calling the current project builds.


 
 License
-------

Copyright 2023 Jeyzer.

Licensed under the [Mozilla Public License, Version 2.0](https://www.mozilla.org/media/MPL/2.0/index.815ca599c9df.txt)