<!--

    Copyright (c) 2002-2016, the original author or authors.

    This software is distributable under the BSD license. See the terms of the
    BSD license in the documentation provided with this software.

    http://www.opensource.org/licenses/bsd-license.php

-->
# Description

JLine is a Java library for handling console input. It is similar in functionality to [BSD editline](http://www.thrysoee.dk/editline/) and [GNU readline](http://www.gnu.org/s/readline/) but with additional features that bring it in par with [ZSH line editor](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html). People familiar with the readline/editline capabilities for modern shells (such as bash and tcsh) will find most of the command editing features of JLine to be familiar.

JLine 3.x is an evolution of [JLine 2.x](https://github.com/jline/jline2).

[![Build Status](https://travis-ci.org/jline/jline3.svg?branch=master)](https://travis-ci.org/jline/jline3)

# License

JLine is distributed under the [BSD License](http://www.opensource.org/licenses/bsd-license.php), meaning that you are completely free to redistribute, modify, or sell it with almost no restrictions.

# Documentation

* [demos](https://github.com/jline/jline3/wiki/Demos)
* [wiki](https://github.com/jline/jline3/wiki)

# Forums

* [jline-users](https://groups.google.com/group/jline-users)
* [jline-dev](https://groups.google.com/group/jline-dev)

# Maven Usage

Use the following definition to use JLine in your maven project:

    <dependency>
      <groupId>org.jline</groupId>
      <artifactId>jline</artifactId>
      <version>3.3.0</version>
    </dependency>

JLine can also be used with more low-level jars:

    <dependency>
      <groupId>org.jline</groupId>
      <artifactId>jline-terminal</artifactId>
      <version>3.3.0</version>
    </dependency>
    <dependency>
      <groupId>org.jline</groupId>
      <artifactId>jline-reader</artifactId>
      <version>3.3.0</version>
    </dependency>

# Building

## Requirements

* Maven 3.3+ (prefer included maven-wrapper)
* Java 8+

Check out and build:

    git clone git://github.com/jline/jline3.git
    cd jline3
    mvn install

