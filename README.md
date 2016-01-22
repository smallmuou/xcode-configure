# xcode-configure

### What?
This command can generate makefile to build xcode project in command line just like <configure & make & make install> in C/C++ language world. Use it you can build xcode project very easy. See follow.
![image](https://github.com/smallmuou/xcode-configure/blob/master/xcode-configure.gif)

### Why?
* Build xcode project more easily.
* Combine thirdpart library more easily.

### How?
* Config
	1. Download xcode-configure to local and add to environment or alias like me follow 
	<pre>
	alias xcode-configure=/Users/starnet/Projects/xcode-configure/xcode-configure
	</pre>
	you can also add to ~/.bash_profile
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

### Tips?
* show version
	<pre>
xcode-configure -v
or 
xcode-configure --version
</pre>

* show help
	<pre>
xcode-configure -h
or 
xcode-configure --help
</pre>

* config for debug mode
	<pre>
xcode-configure -d
or
xcode-configure --enable-debug
</pre>

* support simulator
	<pre>
xcode-configure -s
or
xcode-configure --enable-simulator
</pre>

* assign a install directory
	<pre>
xcode-configure -p PATH
or
xcode-configure --prefix PATH
</pre>


* build all scheme
	<pre>
make
</pre>

* build a special scheme, like `test`
	<pre>
make test
</pre>

* install all scheme
	<pre>
make install
</pre>

* install a special scheme, like `test`
	<pre>
make test-install
</pre>

* clean all scheme
	<pre>
make clean
</pre>

* clean a special scheme, like `test`
	<pre>
make test-clean
</pre>


### License?
This command follow MIT License.

### Contact?
If you has any problem with use it, you can contact me. My E-mail is smallmuou@163.com