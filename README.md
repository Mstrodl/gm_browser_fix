# browser_fix
A simple Garry's Mod module aiming to let you open URLs in your favorite browser instead of the Steam overlay. 

### Compiling for linux
1) Get [premake](https://github.com/premake/premake-core/releases/download/v5.0.0-alpha14/premake-5.0.0-alpha14-linux.tar.gz) add it to your `PATH`
2) Get [garrysmod_common](https://github.com/danielga/garrysmod_common) and set an env var called `GARRYSMOD_COMMON` to the path of the local repo
3) Get [source-sdk minimal](https://github.com/danielga/sourcesdk-minimal) and set an env var called `SOURCE_SDK` to the path of the local repo
4) Run `premake5 gmake` in your local copy of this repo
5) Navigate to the makefile directory (`cd /projects/linux/gmake`)
6) Run `make config=release_x86`

### Usage
Get one the pre-compiled binaries or build it yourself, then put the binary under `garrysmod/lua/bin`.