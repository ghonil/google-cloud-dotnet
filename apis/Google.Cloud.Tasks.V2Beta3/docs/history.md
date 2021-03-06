# Version history

# Version 2.0.0-beta02, released 2020-03-19

No API surface changes compared with 2.0.0-beta01, just dependency
and implementation changes.

# Version 2.0.0-beta01, released 2020-02-19

This is the first prerelease targeting GAX v3. Please see the [breaking changes
guide](https://googleapis.github.io/google-cloud-dotnet/docs/guides/breaking-gax2.html)
for details of changes to both GAX and code generation.

# Version 1.0.0-beta08, released 2019-12-09

- Remove use of Tasks-specific LocationName; use the one in GAX instead
- IAM methods now accept IResourceName instead of specific resource name types
- Retry settings removed
- Resource name types have format methods

# Version 1.0.0-beta07, released 2019-06-18

(No API surface changes.)

# Version 1.0.0-beta06, released 2019-06-18

(No API surface changes.)

# Version 1.0.0-beta05, released 2019-06-17

- [Commit ee5c7dc](https://github.com/googleapis/google-cloud-dotnet/commit/ee5c7dc): Added client builders for simplified configuration

# Version 1.0.0-beta04, released 2019-05-15

- Queue.LogSamplingRatio removed
- Methods accepting resource name parameters now have equivalents accepting string parameters
- Added StackdriverLoggingConfig

# Version 1.0.0-beta03, released 2019-04-08

- [Commit fb520db](https://github.com/googleapis/google-cloud-dotnet/commit/fb520db): Added HttpRequest authorization

# Version 1.0.0-beta02, released 2019-03-12

- Extra HttpMethod enum values
- Added HttpRequest support

# Version 1.0.0-beta01, released 2018-09-03

Initial beta release.

