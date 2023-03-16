# Bad Echo Resource Creator
[![Discord](https://img.shields.io/discord/348353194801364992?style=flat-square&label=Discord&logo=discord&logoColor=white&color=7289DA)](https://discord.gg/omni) 

The `BadEcho.ResourceCreator` tool is used to generate resource files for assets we wish to bundle as resources for a program. The resulting **.resources** files created by this tool can then be embedded into an assembly using a language compiler, and  loaded at run-time through the use of a `ResourceManager`.

Visual Studio's built-in code generator for **.resx** files fails to function correctly when it comes to embedding audio (and possibly other types of) resources. Manual creation of a **.resources** file with this tool allows the loading of audio assets by an application to be both possible and fairly simple.

This package exists to aid in the development of Bad Echo applications, but is licensed under the GNU Affero General Public License so that others may enjoy it as well; see the accompanying [license](https://github.com/BadEcho/resource-creator/blob/master/LICENSE.md) for details.

## Usage

`resource-creator <RESOURCES_PATH> [options]`

To view detailed usage information, simply execute:

`resource-creator --help`

## About Bad Echo
Bad Echo is a collection of software technologies and [various writings](https://badecho.com) by Matt Weber: a software designer, partnered [Twitch](https://twitch.tv/omni) streamer, and game developer.

While Bad Echo code concerns itself a great deal with the "best approaches" to general software problems, it also focuses on game development and providing entertainment through the clever manipulation of games (the results of which are streamed by myself).

## Getting in Contact
I'm a partnered Twitch streamer, and talking to me during one of my [Omnified streams](https://twitch.tv/omni), on the off chance that I actually _am_ streaming, is most definitely the quickest way to get my attention!

You may also reach me [via email](mailto:matt@badecho.com).