pwmanager - A drop-dead simple passwordmanager running on the commandline
=========================================================================

This is a command line password manager that stores your passwords in a file, which you 
can put on your shared storage if you like.

Passwords are stored in a JSON file that and are encrypted using AES-256-CBC. The description
on how to decrypt your passwords is included in the json-file, so whereever you are, even if
you dont have this tool you will get your passwords (if you know your master password).

This tool allows you to

* generate passwords
* store passwords
* read passwords
* store / read passwords to/from the clipboard (currently on osx only)
* sync passwords between different instances of this application (see --server and --synchronize)

I will of course not guarantee that this tool provides any security. I'm not a security expert. Have
a look at the source yourself and see if it meets your security needs. (Don't worry it's only ~300 LOC)

Installation
------------

* download the tool
* chmod +x pwmanager
* ./pwmanager
* (You might want to move it to /usr/local/bin or some place else)
