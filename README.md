HLang
=====


WIP: **ANGRY AXOLOTL release 0 draft 4**

HLang is a scripting language made primarily for becoming the main shell scripting language for [HelenOS](http://www.helenos.org). Currently the system is under development, with only primitive lexing and parsing capabilities. Variable management subsystem is currently in place, however parser does not uses it. HLang is unstable and in many terms UNUSABLE at current stage. For stable versions, lookup the release page [here](https://www.github.com/supragya/HLang/releases). Still, USE WITH CAUTION - DO NOT DEPLOY.


Building HLang from source
----------------
The HLang interpreter is at present a set of lexer and analyser system. To build HLang from source, download the code from the repository to a local machine, `cd` to the codebase and use the following commands:

To build the system:

    make

To build the system, clean:

    make clean

To revert back to original sources:

    make reset

To run the interpreter

    ./run
