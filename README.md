# ntmux (Network Terminal MUltipleXer)

Ntmux executes a command and sends keystrokes from the original terminal and bytes read from TCP client sockets to the command.

It lets any commands:

* interpreters of any language (ruby, python and etc.),
* vi and
* even a shell

can be controlled from anywhere:

* vim buffers,
* emacs buffers,
* other tmux windows,
* other terminals and
* other machines

using any TCP client:

* vim script,
* emacs lisp,
* telnet,
* nc and
* tcp test tools.

## Compile and install

Edit the Makefile
    
```bash
$ make          # Build for OSX or Linux automatically
$ make install  # Install to /usr/bin
```

## Usage

% ntmux *port* *command-and-args...*

## Disclaimer

Currently tested only under

OSX
    % uname -pv
    Darwin Kernel Version 13.1.0: Thu Jan 16 19:40:37 PST 2014; root:xnu-2422.90.20~2/RELEASE_X86_64 i386
    
    % cc --version
    Apple LLVM version 5.0 (clang-500.2.79) (based on LLVM 3.3svn)
    Target: x86_64-apple-darwin13.1.0
    Thread model: posix

LINUX
    $ uname -a
    Linux tux-I3000 3.13.0-36-generic #63-Ubuntu SMP Wed Sep 3 21:30:45 UTC 2014 i686 i686 i686 GNU/Linux
    
    $ cc --version
    cc (Ubuntu 4.8.2-19ubuntu1) 4.8.2
    Copyright (C) 2013 Free Software Foundation, Inc.
    This is free software; see the source for copying conditions.  There is NO
    warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

## Demo

<a href="https://www.youtube.com/watch?v=dKNr3rk58YI">![ss 2014-03-06 21.38.02.png](https://qiita-image-store.s3.amazonaws.com/0/12593/20ebc62f-a085-d708-143b-c49fde705802.png "ss 2014-03-06 21.38.02.png")</a>

## License

Copyright (c) 2014 Yoshinori Kohyama.  Distributed under the BSD 3-Clause License.  See the file LICENSE.md.

