# Mythfrontend Release Repository
Releases of Mythfrontend for macOS

This houses the latest releases of the Mythfrontend.app.  These builds are mirrored over to the [SourceForge site](https://sourceforge.net/projects/mythtvformacosx/).

This is unofficial MythTV site,  please visit the [MythTV site](https://www.mythtv.org/) for the main project, and their official [GitHub site](https://github.com/MythTV) for the official code and issues tracker.

# SourceForge Repository
A large reopository of past (and current) MythTV / Mythfrontend builds are housed here at the [SourceForge site (https://sourceforge.net/projects/mythtvformacosx/).  These builds will be updated periodically from files generated here.

# Support
Support for using the compile script is available on this website, please file an [Issue](https://github.com/MythTVforMacOS/compileMythfrontend/issues) or would like to make a [Pull Request](https://github.com/MythTVforMacOS/compileMythfrontend/pulls) as apporpriate.

Support for **compiling or troubleshooting mythtv specific issues** will be referred to the official mythtv mailing list (http://lists.mythtv.org/mailman/listinfo/mythtv-users) and forums (https://forum.mythtv.org/). Please do not get offended if you are referred to these forums for help as opposed to the github Issues tracker. These forums are monitored by many more helpful/insightful developers than this unofficial GitHub sight.

# Why Build With MacPorts
For a fully functional MythTV with plugins, only MacPorts has all of the necessary dependencies for compiling MythTV in it's repository. For this reason alone, it significantly simplifies getting all of the dependencies installed and working without the need to maintain countless download links and specific to macOS patches.

Mythtv does successfully build under Homebrew, but with limited capability as key libraries such as qtwebkit are not available wihout manual installation.  If anyone is interested in trying the Homebrew route please do so. If you are successful - please make suggestions on how to update the compile script and ansible.
