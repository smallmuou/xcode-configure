# xcode-configure

### What?
This command can generate makefile to build xcode project in command line just like <configure & make & make install> in C/C++ language world. Use it you can build xcode project very easy. See follow.
![image](https://github.com/smallmuou/xcode-configure/blob/master/xcode-configure.gif)

### Why?
* Build xcode project more easily.
* Combine thirdpart library more easily.

### How?
* Config
	1. Download xcode-configure to local and add to environment or alias like me (alias xcode-configure=/Users/starnet/Projects/xcode-configure/xcode-configure)
	2. Go to the xcode project root directory and type `xcode-configure`
	
* Usage
<pre>
USAGE: xcode-configure [-v|--version] [-h|--help] [-s|--enable-simulator] [-d|--enable-debug] [-p|--prefix < install directory >]
OPTION:
-v|--version                    show the version
-h|--help                       show the help
-s|--enable-simulator           enable simulator
-d|--enable-debug               enable debug
-p|--prefix PATH                assign the directory for install(default is ./target)
</pre>

### License?
This command follow MIT License.

### Contact?
If you has any problem with use it, you can contact me. My E-mail is smallmuou@163.com