Goals for "my perfect c++ database library"
----

Usage
===

* Simple, unambiguous style for  client code
* We don't really care too much about the back end code (no really - who ever looks)


Dynamic query support
===

All drivers do this, and any tool dynamically building queries needs this.

Static query support
==
This is the opposite end of the spectrum - something that should satisfy 
 * stable
 * maintainable
 * as automatic as possible / necessary


Pluggable backends
===
 NO BUILD FLAGS!
 Seriously.

Design Style supporting "extension points"
===

This would be a nice thing to consider from the outset to support <algorithm> style use where it is apt.

# Crazy thoughts:

## schemas!
### "compatible with" / "identical to" for applications to verify they are properly connected?
This crops up a lot.

## error handling style

Maybe use error_code and keep both camps happy? 

