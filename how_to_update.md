How to update the mod

Gradle pulls resources from GitHub during build. You do not need to update any resource of data files in this project.

1. Update the resource/datapack on github first
2. Open `gradle.properties` and in the bottom update the `datapack_ref` variable to the branch that has the latest resources
3. In the same file, update the mod_version variable to the new version number
4. Run the `mod development/runClient` gradle task for testing
5. Run the `build/build` gradle task
6. The new jar file can then be found in `build/libs/`