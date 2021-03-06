# c\_irc

A simple messaging system prototype (aka CSCE 3600 Major Assignment)

### Overview

**UPDATE 17 NOV 2017**: This project was submitted on May 9, 2017, and received an A.

### Project Structure

```
.
+-- client
|   +-- (client source files)
+-- lib
|   +-- (header files required by both client and server)
+-- server
|   +-- (server source files)
+-- sessions
|   +-- (`script` session files)
+-- submit
|   +-- (files to be submitted to TAs via Bb)
+-- .gitignore (files ignored by Git -- mainly compiled binaries)
+-- README.md (this README)
+-- makefile
+-- test.sh
```

### Submission Requirements

- Well-documented code – each file has a header, commented blocks, etc.
- Client source file named **cliMajor.c**. Client binary named **cliMajor**. \*\*
- Server source file named **srvMajor.c**. Server binary named **srvMajor**. \*\*
- Include README or makefile to ensure code is compiled correctly
- Ensure code compiles and runs correctly on the CSE machines
  - This should not be an issue, as all development and testing should be done on the CSE machines anyway.

<sup>\*\* Requirement satisfied by `makefile`. See [#1](https://github.com/ChaoticWeg/csce3600-major/issues/1) for more.</sup>

### Deployment/Submission

```
$ make deploy
$ cd submit/
$ make
```

Make sure that we test the deployed code before submitting through Bb!
