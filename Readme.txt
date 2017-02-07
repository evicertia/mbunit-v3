Gallio Automation Platform and MbUnit v3
Copyright 2005-2010 Gallio Project - http://www.gallio.org/
===========================================================

Please refer to the Wiki for documentation on getting started with the
development tree and the build system.

http://www.gallio.org/wiki/development


Evicertia Devs:

Compile Workaround:

find src/ -path '*/obj/*' -delete
rm -rf build/
c:\Windows\Microsoft.NET\Framework\v4.0.30319\msbuild.exe /p:CCNetLabel=3.4.0.0 /p:FileVersion=3.4.0.0  /p:SkipSyncProjects=true /p:SkipSourceServer=true /p:SkipModules="MbUnitTemplates;DLR;Ambience;RSpec" CCNet.msbuild
