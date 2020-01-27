To build and publish to `build/repo`, use `./gradlew publishShadowPublicationToMavenRepository`.

Version matches published ASM version, with optional .0.X for internal "patch" releases.
For example, version 7.2.0.1 matches ASM 7.2, with a minor change that resulted in a "patch" release.
In this case, the minor change was bundling ASM's license in the final jar.
