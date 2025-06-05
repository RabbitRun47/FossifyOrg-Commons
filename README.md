# Fork of [FossifyOrg/commons](https://github.com/FossifyOrg/commons)

-   Aim was to make Automatic Backup option in [FossifyOrg/Contacts](https://github.com/FossifyOrg/Contacts) app work in my old android 10 phone.

-   Publish to local or to jitpack.io and use it as a module in (my fork)[https://github.com/RabbitRun47/FossifyOrg-Contacts] of the [FossifyOrg/Contacts](https://github.com/FossifyOrg/Contacts) app.

# publish to maven local

1. `./gradlew publishToMavenLocal`

# publish to jitpack.io

1. Push your local commits to your fork on GitHub.
2. ```bash
       git commit
       git tag -a v1.0.4 -m "JitPack build for v1.0.4"
       git push origin v1.0.4
   ```
3. Go to https://jitpack.io/#RabbitRun47/FossifyOrg-Commons
    1. Click on "Get it" for your version v1.0.4
4. Go to gradle/libs.versions.toml and update the version
    ```
    #Fossify
    commons = "v1.0.4"
    ```
