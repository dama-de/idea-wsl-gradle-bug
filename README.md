1. Checkout this project in WSL
2. Using a Windows installation of IDEA, open this project (`\\wsl.localhost\...`)
3. Trigger the Gradle Sync
4. Open *Project Structure -> Artifacts* and look at the output directory of the exploded artifact

The path generated reads `\\exploded\wsl.localhost\...` which is obviously wrong, and causes deployments of this artifact to fail.