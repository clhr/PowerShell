![PowerShell Logo](assets/Powershell_64.png) PowerShell
========================

PowerShell is a task automation and configuration management platform,
consisting of a command-line shell and associated scripting language built
using the [.NET Command-Line Interface](https://github.com/dotnet/cli).
PowerShell provides full access to COM and WMI, enabling administrators to
automate administrative tasks on both local and remote Windows, Linux, and OS X systems.

New to PowerShell?
------------------
If you are new to PowerShell and would like to learn more, we recommend
reviewing the [getting started documentation][getting-started].

[getting-started]: docs/learning-powerShell/learning-powershell.md

Build Status
------------

| Platform     | `master` |
|--------------|----------|
| Ubuntu 14.04 | [![Build Status](https://travis-ci.com/PowerShell/PowerShell.svg?token=31YifM4jfyVpBmEGitCm&branch=master)](https://travis-ci.com/PowerShell/PowerShell) |
| OS X 10.11   | [![Build Status](https://travis-ci.com/PowerShell/PowerShell.svg?token=31YifM4jfyVpBmEGitCm&branch=master)](https://travis-ci.com/PowerShell/PowerShell) |
| Windows      | [![Build status](https://ci.appveyor.com/api/projects/status/jtefab3hpngtyesp/branch/master?svg=true)](https://ci.appveyor.com/project/PowerShell/powershell/branch/master) |

Get PowerShell
--------------

1. Download the package for your platform at [PowerShell Releases][releases].
1. Install the package. 
   * [Linux or OS X][inst-linux].
   * [Windows][inst-win].

Building PowerShell
-------------------

| Linux | Windows  | OS X |
|-------|----------|------|
| [Instructions][build-linux] | [Instructions][build-wc] | [Instructions][build-osx] |

Downloading the Source Code
----------------------
The PowerShell repository has a number of other repositories embedded as submodules.
To make things easy, we can just clone recursively.

```sh
git clone --recursive https://github.com/PowerShell/PowerShell.git
```

If you already cloned but forgot to use `--recursive`, you can update submodules manually:
```sh
git submodule init
git submodule update
```
See [working with the PowerShell repository][powershell-repo-101] for more information.

Developing and Contributing
--------------------------

Please see the [Contribution Guide][contribution] for how to develop and contribute.

If you encounter issues in your development, please consult the [known issues][known-issues]
and [FAQ][faq] documents to see if the issue you are running into is
captured and if a workaround exists.  

If you encounter issues with PowerShell itself, first search for it in our [issues][github-issues].
If you do not see your issue captured, please file a [new issue][new-issue].  For more details see [Contributing to issues][contribution-issues].

PowerShell Community
--------------------
`TODO` Missing community details

Legal and Licensing
-------------------

`TODO` Missing license details

`TODO` Missing link to contributor agreement

Code of Conduct
---------------

This project has adopted the [Microsoft Open Source Code of Conduct][conduct-code].
For more information see the [Code of Conduct FAQ][conduct-FAQ] or contact
[opencode@microsoft.com][conduct-email] with any additional questions or comments.

[build-linux]: docs/building/linux.md
[build-osx]: docs/building/osx.md
[build-wc]: docs/building/windows-core.md
[conduct-code]: http://opensource.microsoft.com/codeofconduct/
[conduct-email]: mailto:opencode@microsoft.com
[conduct-FAQ]: http://opensource.microsoft.com/codeofconduct/faq/
[contribution]: .github/CONTRIBUTING.md
[contribution-issues]: .github/CONTRIBUTING.md#contributing-to-issues
[faq]: docs/FAQ.md
[github-issues]:https://github.com/PowerShell/PowerShell/issues
[inst-linux]: docs/installation/linux.md
[inst-win]: docs/installation/windows.md
[known-issues]: docs/KNOWNISSUES.md
[new-issue]:https://github.com/PowerShell/PowerShell/issues/new
[releases]: https://github.com/PowerShell/PowerShell/releases
[powershell-repo-101]: docs/git/powershell-repository-101.md
