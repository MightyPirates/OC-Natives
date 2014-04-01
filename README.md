This is a repository containing the C sources used to build the native library that ships with [OpenComputers][], for anyone interested. As it is, it builds on Windows and Linux. I could/did not test it for MacOS. The gradle script is not necessarily "nice", but it works, which was good enough for me to push this repo. Improvements to it are very much welcome, in particular when it comes to make it work on different platforms out of the box.

Note that to compile the 64 bit version on Windows you'll probably need Visual Studio 2011. At least for me 2010 doesn't come with a 64 bit compiler.

To build the libraries, adjust the paths as necessary (in particular to your JDK), then run `gradlew gradlew x86NativesSharedLibrary x64NativesSharedLibrary`.


[OpenComputers]: https://github.com/MightyPirates/OpenComputers