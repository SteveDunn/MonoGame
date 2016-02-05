# Contributing to MonoGame

We're glad that you have chosen to contribute to the MonoGame project!

The MonoGame Team has defined the simple guide below to help you as a new contributor to the project.  Please read this document carefully and try to conform to our process and guidelines as you help us improve and grow MonoGame.


## How To Contribute

MonoGame consists of a `master` branch with the latest stable releases and a `develop` branch with the day to day development changes. All new contributions and fixes should be directed to the `develop` branch.

The MonoGame project follows standard [GitHub flow](https://guides.github.com/introduction/flow/index.html).  You should learn and be familiar with how to [use Git](https://help.github.com/articles/set-up-git/), how to [create a fork of MonoGame](https://help.github.com/articles/fork-a-repo/), and how to [submit a Pull Request](https://help.github.com/articles/using-pull-requests/).

After you submit a PR the [MonoGame build bot](https://github.com/mgbot?tab=activity) will automatically build your changes and verify all unit tests pass.  One or more of the project maintainers and other contributors will help review your changes and provide constructive feedback to improve your submission.

Once we are satisfied that your changes are good for MonoGame it will be merged.


## Quick Guidelines

Here are a few simple rules and suggestions to remember when contributing to MonoGame:

* :bangbang: **NEVER** commit code that you didn't personally write.
* :bangbang: **NEVER** use decompiler tools to steal code and submit them as your own work.
* :bangbang: **NEVER** decompile XNA assemblies and steal Microsoft's copyrighted code.
* **PLEASE** try keep your PRs focused on a single topic and of a reasonable size or we may ask you to break it up.
* **DO NOT** surprise us with new APIs or big new features. Open an issue to discuss your ideas first.
* **DO NOT** reorder type members as it makes it very difficult to compare code changes in a PR.
* **DO** try to follow our [coding style](https://github.com/mono/MonoGame/wiki/Coding-Guidelines) for new code.
* **DO** give priority to the existing style of the file you're changing even if it diverges from the style above.
* **DO** try to add to our [unit tests](Test) when adding new features or fixing bugs.
* **DO NOT** send PRs for code style changes or make code changes just for the sake of style.
* **PLEASE** keep a civil and respectful tone when discussing and reviewing contributions.
* **PLEASE** tell others about MonoGame and your contributions via social media!


## Decompiler Tools

This includes, but is not limited to tools like dotPeek, ILSpy, JustDecompiler, .NET Reflector, or any others which convert compiled assemblies back into readable code.

There has been confusion on this point in the past, so we want to make this perfectly clear.  It is **NEVER ACCEPTABLE** to decompile any assemblies containing copyrighted code and submit that code to the MonoGame project.

* It **DOES NOT** matter how much you change the code.
* It **DOES NOT** matter what country you live in or what your local laws say.  
* It **DOES NOT** matter that XNA is discontinued.  
* It **DOES NOT** matter how small the bit of code you have stolen is.  
* It **DOES NOT** matter what your opinion is of stealing code.

If you did not write the code yourself, you do not have ownership of that code, and it should never be submitted to the MonoGame code base.

If a contribution is found to be in violation of copyright it will be immediately removed and the contributor will be barred from future collaboration in the MonoGame project.


## Licensing

The MonoGame project is under the [Microsoft Public License](https://opensource.org/licenses/MS-PL) with the exception of a few smaller sections of code.  See the [LICENSE.txt](LICENSE.txt) file for additional details.  Third-party libraries used by MonoGame are under their own licenses Please refer to those libraries for details on the license they use.

We accept contributions in "good faith" that they are your own work and not bound to any conflicting license.  By submitting a PR you are agreeing to allow us to distribute your contribution under the MonoGame license and the MonoGame Team copyright.

To this end when submitting new files you should include the following copyright and license in the header when appropriate:
```
// MonoGame - Copyright (C) The MonoGame Team
// This file is subject to the terms and conditions defined in
// file 'LICENSE.txt', which is part of this source code package.
```

## Need More Help?

If you need more help in building MonoGame, using Git or GitHub, or general development advice feel free to ask questions at either our [Community discussion forums](http://community.monogame.net/) or in our [live Gitter discussion](https://gitter.im/mono/MonoGame).
