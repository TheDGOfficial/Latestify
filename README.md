# Latestify
Latestify is a mod that bundles more recent version of the libraries Minecraft depends on for better security, bugfixes and performance improvements.

Fabric's jar-in-jar system with SemVer prioritizing loading newer versions of artifacts are used for this.

You will need to add -Dsodium.checks.issue2561=false to your startup arguments to disable Sodium's LWJGL version check. This is required to use the 3.4.2-SNAPSHOT version which fixes FFM API performance regressions with Java 25.
