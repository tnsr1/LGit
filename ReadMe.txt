Visual Git is a Git porcelain and MSSCCI IDE plugin.

Check out the site https://visualgit.io for details and binary builds.

Please contact calvin@cmpct.info for questions.

## Build Instructitons

* Visual C++ 6, SP5 with Processor Pack
  * Newer VC++ will probably work by converting the project
* Dependency build instructions in DEPS.md.
* Some paths may be hardcoded in the project file, just convert as needed
* StaticRelease profile is used for static deps/CRT

## Why the name LGit?

This was before it had a name, so it stuck in the project file.

Для сборки потребуется 
c:\src\libgit2-built\git2.lib 

git2.lib собирается с помощью
https://github.com/tnsr1/libgit2/blob/main/build32.cmd
