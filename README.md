# `Hello World!` VSCode Example

This is an example [TypeScript](https://www.typescriptlang.org) program set up to do a watched build inside [VSCode](https://code.visualstudio.com/) using [ContainIt](https://github.com/unboundedsystems/containit).

The program itself is a simple `Hello World!` with a minimalist `tsconfig.json`, `package.json`, a `tasks.json` file to make everything work.

When VSCode is asked to run the Build Task, it will use [ContainIt](https://github.com/unboundedsystems/containit) to launch npm inside a container from the DockerHub `node:8` image to execute the build.

See this [video](https://youtu.be/f1uOrfX3sJc) for an explanation of the example.
