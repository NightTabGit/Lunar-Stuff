
# Lunar-Agents
A collection of MC Agents for the LCQT Launcher (A wrapper for Lunar Client)

Use these with LCQT, an open source Lunar Client wrapper. 

LCQT basically, in a nutshell, launches Lunar Client with sme custom code, so you can do fancy things to it, like change the window title, or remove pinned servers.

Source / Repo: https://github.com/Nilsen84/lunar-client-qt
Direct Download: 
https://github.com/Nilsen84/lunar-client-qt/releases/download/1.1/windows-x64.zip (Windows)
https://github.com/Nilsen84/lunar-client-qt/releases/download/1.1/lunarclientqt-linux-x64 (Linux)

# Sources

**Lunar Enable, LunarHitDelayFix and NoPinnedServers:**  https://github.com/Nilsen84/lunar-client-agents
**CPatcher:** https://github.com/ArcaneCiCi/CPatcher

# Lunar Enable
**Unlocks Freelook and AutoTextHotKey.**
Source: **Closed.**
To use, just add it to the Agents tab in LCQT, no changes needed.

- Download: https://github.com/NightTabGit/Lunar-Agents/raw/main/LunarEnable.jar
- From Source: https://github.com/Nilsen84/lunar-client-agents/raw/main/LunarEnable.jar

# LunarHitDelayFix
**Fixes the delay between your sword swinging in 1.8.9. Reverts back to 1.7, with all clicks being registered. Is not _detected_ but may be seen as an _unfar advantage_ to some.**

- Source: **https://github.com/Nilsen84/LunarHitDelayFix**
- To use, just add it to the Agents tab in LCQT, no changes needed.

Download: https://github.com/NightTabGit/Lunar-Agents/raw/main/LunarHitDelayFix.jar
From Source: https://github.com/Nilsen84/lunar-client-agents/raw/main/LunarHitDelayFix.jar

# NoPinnedServers
**Removes pinned servers from the Multiplayer server menu.**
Source: **https://github.com/Nilsen84/NoPinnedServers**
To use, just add it to the Agents tab in LCQT, no changes needed.

- Download: https://github.com/NightTabGit/Lunar-Agents/raw/main/NoPinnedServers.jar
- From Source: https://github.com/Nilsen84/lunar-client-agents/raw/main/NoPinnedServers.jar

# CPatcher
**Changes the Window Name, Authentification servers, and Asset URL of Lunar Client.**
Source: **https://github.com/ArcaneCiCi/CPatcher**
To use, just add it to the Agents tab in LCQT.

- Pre-Built download: https://github.com/NightTabGit/Lunar-Agents/raw/main/CPatcher.jar

- To build, download the source `https://github.com/ArcaneCiCi/CPatcher`, open in Idea/Eclipse and install the Maven project. Using the Maven project, run the build / compile command.

- To modify the properties go to: C:\%userprofile%\.lunarclient and in the file `cpatcher.properties`.

If you want the default AUTH and ASSET_URL set them both to be:
`ASSET_URL=default
AUTH_URL=default`

`"I cant see my cosmetics!"` - Change the first line of the propertise file to be `ASSET_URL=default`.

`"How do I change the title?"` - Change the last line of the propertise file to be `TITLE=YourTitleNameHere`, replacing `YourTitleNameHere` with, of course, your title.


# How to prevent Lunar Client updating.

Basically, whenever Lunar Client updates, its mappings change (Maybe a lot, sometimes not a lot). 

Some cheats, for example, Whiteout and Ploow, need up-to-date mappings of this new Lunar Client.

When Lunar Client updates, these clients may take from a few hours, to days to update thier mappings, to the new Lunar Client.

To prevent not being able to use the cheats with Lunar for the days where its not supported, launch using an external wrapper for Lunar client.

This launcher, will prevent Lunar client from being updated, therefore meaning, if you **always** launch with LC-QT or LCL, you will have the version of Lunar Client, that is supported, and has the same mappings.

Then, once your desired client (Whiteout, Ploow, etc) updates, you may launch Lunar from the **official** launcher, and update Lunar Client to the correct version.

Then, keep launching using LC-QT or LCL to prevent it from updating the next time Lunar pushes an update.

# I already updated Lunar Client? How do I downgrade?

If you already have the most updated version, you must find someone who hasnt updated Lunar Client yet, and ask them for thier files.

1 - Navigate to `Local Disk C -> Users -> YOURUSER -> .lunarclient -> offline`. You should see some folders in there, named `1.8.9`,`1.7`, etc.

2 - Download the old folder from someone else.

3 - Delete the `1.8.9` folder from your `.lunarclient` folder.

4 - Replace with the old 1.8.9 folder that you downloaded from someone else. (MAKE SURE YOU TRUST THEM).

5 - Launch with LC-QT or LCL to prevent Lunar from updating.

# Issues

Clients such as Vape Lite and Vape V4, do not crash upon injecting into a modified Lunar Client (To an extent), but clients such as Whiteout are prone to crashing when not on version **06e602c2**, and with a modified window title not including **Lunar Client (1.x.x-clientversion/master)**, due to it possibly reading the client version from title? (Unknown) so DON'T use CPatcher do modify title name, but feel free to patch AUTH_URL and ASSET_URL.

# Entropy

From testing, entropy requires a custom JRE path on LC-QT to work. Just navighate to the feault Javaw.exe in the minecraft launcher folder and use that.
