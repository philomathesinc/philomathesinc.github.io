# Tasks

## Linux

### Task 1

- Create two users **tux** and **octocat**.
- Create a group **friends**.
- Create a directory `/friends`.
- Allow the group **friends** read access to `/friends`.
- Allow the user **tux** write access to `/friends`.

### Task 2

- [Here is a Go application](https://gobyexample.com/http-server).
- Compile the application and store the resulting binary file at `/usr/local/bin/http-server`. (Check out the [Resources page](resources.md#go) for help with building a Go application)

_Note: The following two steps would block the shell from processing further inputs. You can exit the application by pressing `Ctrl+C`._
- Ensure the application binary is executable. Execute it using the full absolute path and verify it from a browser.
- Ensure the application is available to execute from any path using just the binary name(as opposed to the absolute path in the first step) - `http-server`. Execute it and verify from a browser.
- Ensure the application is running at all times. Verify by restarting your computer and checking if you can access the application from the browser without running any commands manually.