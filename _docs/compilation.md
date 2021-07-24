---
title: Compilation
permalink: /docs/compilation/
---

* Clone the Nucleus Co-Op repositry from [here](https://github.com/zerofox5866/nucleuscoop). GitHub Desktop is a convenient way to do this. Make sure you are using the correct branch.

* Run the git command `git submodule update --init --recursive` in the root of the repository to download all submodules.

* Open `Submodules\ProtoInput\src\ProtoInput\ProtoInput.sln` in Visual Studio, and go to Build -> Batch Build and select these options (basically everything in Release x86 and x64, except Proto Input Host x64)

![Proto Input Batch Build](../../img/protoinput/protobatchbuild.png)

* Click Build and be prepared to wait a while

* The `Submodules\ProtoInput\src\ProtoInput\Release` folder should now look like

![Proto Input compiled](../../img/protoinput/protocompiled.png)

* Now open `Master\NucleusCoop.sln`, and go to Build -> Batch Build, then select:

![Nucleus Batch Build](../../img/nucleuscbatchbuild.png)

* Click Build and be prepared to wait significantly less time than before.

* The output files will be in `Master\NucleusCoopTool\bin\Release`

* Note that if you change Proto Input, the files will only be copied upon a ****rebuild**** of the Nucleus.Coop project.