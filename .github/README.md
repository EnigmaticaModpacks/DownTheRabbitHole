# Down The Rabbit Hole

This is the official repository and issue-tracker for the modpack Down The Rabbit Hole for Minecraft 1.18

### Table of Contents

-   [Setup](#setup)
    -   [CurseForge App (Windows/Mac)](#curseforge-app-windows--mac)
    -   [MultiMC (Windows/Mac/Linux)](#multimc-linux--windows--mac)
-   [Links](#links)

<hr></hr>

# Setup

### For Contributors and Testers

Follow these steps to setup your workspace:

## MultiMC (Linux / Windows / Mac)

#### Setup MultiMC Instance

1. Download [MultiMC](https://multimc.org/#Download) and [Git](https://git-scm.com/downloads) if you haven't already.
2. Open MultiMC.
3. Click Add Instance, choose Minecraft 1.18.1, click Ok.
4. Click Edit Instance.
5. Click Install Forge, pick the latest version.

#### Repository Setup

6. Fork and clone the repository into the MultiMC Instance.
7. Open the folder of the MultiMC Instance you made (step 1-5), and go into the .minecraft folder - Open a terminal/command line and use the following commands:

```sh
git init                                            # Initialize git in folder
git remote add origin URLToYourForkOfTheModpack     # Set remote origin to your fork of the modpack
git remote -v                                       # Verify remote
git fetch
git checkout develop
git pull
```

8. Now double click the script `InstanceSyncSetup.sh` to setup InstanceSync. It is found in the `automation` folder.

You're done!

Tip: If you run into issues, verify that you are using the right Minecraft and Forge version in your MultiMC instance!

## CurseForge App (Windows / Mac)

1. Download the [CurseForge App](https://curseforge.overwolf.com/) and [Git](https://git-scm.com/downloads) if you haven't already.
2. Fork and clone the repository to the Instances folder of the CurseForge App, the default path is `C:\Users\{UserName}\Documents\Curse\Minecraft\Instances`.

    - _Note: If you've previously used the Twitch App the path will most likely be `C:\Users\{UserName}\Documents\Twitch\Minecraft\Instances`._

3. Double click the script `InstanceSyncSetup.bat` to setup InstanceSync. It is found in the `automation` folder.
4. Open the CurseForge App and you should see the modpack. If you already had CurseForge App open, restart it.

You're done!

## Testing

If you would like to help test the modpack, you're very welcome to do so.
The best way you can test is by playing the modpack, reporting bugs and providing feedback from your experience.

There are a few things we would like testers to consider/look for:

-   Bugs
-   Things you find boring/tedious
-   Things that need small optimizations, such as advancement text and textures.

## Links

-   [CurseForge](https://www.curseforge.com/minecraft/modpacks/DownTheRabbitHole)

-   [Discord](https://discord.gg/HnWNd7X)