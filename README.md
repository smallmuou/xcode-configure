# xcode-configure

### What?
This command can generate makefile to build xcode project in command line just like <configure & make & make install> in C/C++ language world. Use it you can build xcode project very easy. See follow.
![image](https://github.com/smallmuou/xcode-configure/blob/master/xcode-configure.gif)

### Features

* Support ipa
* Support framework
* Support static library

### Why
* Build xcode project more easily.
* Combine thirdpart library more easily.

### How
* Config
	* 1. Download xcode-configure to local and add to environment or alias like me follow 
	<pre>
	alias xcode-configure=/Users/starnet/Projects/xcode-configure/xcode-configure</pre>

	you can also add to ~/.bash_profile
	
	* 2. Go to the xcode project root directory and type `xcode-configure`
	
* Usage
<pre>
USAGE: xcode-configure [-t|--target] [-v|--version] [-h|--help] [-s|--enable-simulator] [-d|--enable-debug] [-p|--prefix <install directory>]
</pre>

### Tips
* show version

<pre>
xcode-configure -v
</pre>

* show targets

<pre>
xcode-configure -t
</pre>


* show help

<pre>
xcode-configure -h
</pre>

* config for debug mode

<pre>
xcode-configure -d
</pre>

* support simulator

<pre>
xcode-configure -s
</pre>

* assign a install directory

<pre>
xcode-configure -p PATH
</pre>

* build all targets (you can use `xcodebuild -list` to show all scheme)

<pre>
make
</pre>

* build a special target, like `test`

<pre>
make test
</pre>

* install all target

<pre>
make install
</pre>

* install a special target, like `test`

<pre>
make test-install
</pre>

* clean all targets

<pre>
make clean
</pre>

* clean a special target, like `test`

<pre>
make test-clean
</pre>


### License
This command follow MIT License.

### Contact
If you has any problem with use it, you can contact me. My E-mail is smallmuou@163.com