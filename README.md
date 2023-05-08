# check-macos-installer

A script that deeply validates a macOS installer.

Inspired by Howard Oakley's [Checking a macOS installer app is easier with Taccy 1.6](https://eclecticlight.co/2019/10/28/checking-a-macos-installer-app-is-easier-with-taccy-1-6/), but command-line-ized. Tested with macOS High Sierra, Mojave, and Catalina installers.

Depends on [portable-color](https://github.com/mattieb/portable-color), which is included as a submodule if you wish to use it directly from your clone. However, if portable-color has been installed to your PATH, check-macos-installer will find it.

## Installation

I recommend you install or link "check-macos-installer" to `${HOME}/.local/bin`, and add this directory to your PATH if it is not already there.

portable-color will work if you follow [its installation instructions](https://github.com/mattieb/portable-color#installation) and put "portable-color.sh" on your PATH as well.

## Usage

Just point it at an installer app:

```
check-macos-installer "Install macOS Catalina.app"
```
