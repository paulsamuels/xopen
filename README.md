# xopen

Command to quickly open Xcode projects.

- It starts by attempting to open a workspace and then falls back to an xcodeproj if no workspace is found.
- If inside a git project it will attempt to lookup the project in the root of the repository.
