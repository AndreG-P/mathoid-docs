# mathoid-docs
This repo contains additional documentation on mathoid

## Possible Problems on Windows
Note that an installation of `npm install librsvg` could produces some errors under Windows.

See [librsvg](https://www.npmjs.com/package/librsvg) for general infos. Note the links for Windows are broken. The actual links can be found here: [GTK+ Windows](https://www.gtk.org/download/windows.php). Follow the installation until step 2 (the rest is not needed). 

Furthermore, it's necessary to install Visual Studio. In the installation of Visual Studio, make sure you download the Windows 8.1 SDK (independent of your own Windows version). Once you have done that, you should found the following folder on your system: `C:\Program Files (x86)\MSBuild\Microsoft.Cpp\v4.0\v140`. Add this to a system environment variable called: `VCTargetsPath`.

See [GitHub-Sharp-Issue-985](https://github.com/lovell/sharp/issues/985).
