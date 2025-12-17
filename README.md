# minielectron
Minielectron is an lightweight version of the cross-platform development framework Electron. Based on retaining most of Electron's APIs, usage patterns, and compatibility, it trims the original Electron down to around 60–70 MB. It requires only a single executable file (i.e., a single .exe file on Windows) to run.
The usage of Minielectron is exactly the same as that of the original Electron, so projects based on the original Electron can be seamlessly migrated over without modification.
Minielectron comes with its own built-in kernel called miniblink, which is a completely rewritten new kernel based on Chromium’s Blink + V8. It focuses on minimizing size and memory usage, runs in single-process mode, and retains Chromium’s layout and rendering capabilities.
Currently, Minielectron does not yet support DevTools, so please develop your application using the original Electron, and then package and release it with Minielectron.

minielectron是跨平台开发框架electron的极致精简版，在保留大部分electron api、用法、兼容性的基础上，把原版electron裁剪到60-70M左右，并且只需要一个可执行文件（在windows下即单个exe文件）即可运行。
minielectron的使用方式和原版electron完全一致，基于原版electron的项目可以直接无缝迁移过来。
minielectron本身自带了一个内核miniblink，这是个在chromium的blink+v8基础上完全重写的全新内核，专注于体积、内存的精简，单进程模式，并保留了chromium的排版渲染能力。
目前minielectron还未支持Devtools，所以请在原版electron上开发，发布的时候再使用minielectron打包、发布即可。

