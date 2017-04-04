# Make Log
This repository provides a simple log function that can be used in Makefiles.

# Usage
Since this function doesn't really change it is easiest to download the `make-log.mk` file and copy its contents into your Makefile. 
Please add a little comment above it telling people where you got it.

Then call it like so:
```Makefile
$(call log,level,message)
```
Where level can be `ok`, `warn`, or `error` and message can be an message.
