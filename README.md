#### Power assembly support for VSCode compatible editors

Language support for POWER/ppc/powerpc assembly in VSCode and friends.

Heavily borrows from [vscode-arm](https://github.com/dan-c-underwood/vscode-arm) by [Dan Underwood](https://github.com/dan-c-underwood), taking most of the instruction and regex stuff from my ancient and abandoned [Atom plugin](https://github.com/ruscur/language-powerpc-assembly/), which in turn borrowed heavily from [language-x86](https://github.com/taylorlapeyre/language-x86) by [taylorlapeyre](https://github.com/taylorlapeyre/).

That previous Atom plugin of mine thanked the following: Ben Stevens for being helpful with regex, Cyril Bur for being helpful with assembly, and [50Wliu](https://github.com/50Wliu) for pointing out a regex mistake.

The instructions dumped in here are almost certainly out of date and have no intelligence - it is absolutely possible to have usage checking (i.e. number of parameters), however it is unimplemented and would assumedly be a lot of work.  At present I have no plans to do anything other than make things easier on the eyes.

Updates are needed for the latest public ISA.

Here's an example of what it looks like with the Nord theme:

![from skiboot/asm/head.S](https://raw.githubusercontent.com/ruscur/vscode-power/main/images/preview.png)