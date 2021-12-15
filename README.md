# Lunar-Agents
A collection of MC Agents for the LCQT Launcher (A wrapper for Lunar Client)

Use these with LCQT, an open source Lunar Client wrapper. 

LCQT basically, in a nutshell, launches Lunar Client with sme custom code, so you can do fancy things to it, like change the window title, or remove pinned servers.

# Sources

**Lunar Enable, KunarHitDelayFix and NoPinnedServers:**  https://github.com/Nilsen84/lunar-client-agents

# Lunar Enable
**Unlocks Freelook and AutoTextHotKey.**
Source: **Closed.**
To use, just add it to the Agents tab in LCQT, no changes needed.

# LunarHitDelayFix
**Fixes the delay between your sword swinging in 1.8.9. Reverts back to 1.7, with all clicks being registered. Is not _detected_ but may be seen as an _unfar advantage_ to some.**
Source: **https://github.com/Nilsen84/LunarHitDelayFix**
To use, just add it to the Agents tab in LCQT, no changes needed.

# NoPinnedServers
**Removes pinned servers from the Multiplayer server menu.**
Source: **https://github.com/Nilsen84/NoPinnedServers**
To use, just add it to the Agents tab in LCQT, no changes needed.

# CPatcher
**Changes the Window Name, Authentification servers, and Asset URL of Lunar Client.**
Source: **https://github.com/ArcaneCiCi/CPatcher**
To use, just add it to the Agents tab in LCQT. 

- To modify the properties go to: C:\%userprofile%\Dell\.lunarclient and in the file `cpatcher.properties`.

If you want the default AUTH and ASSET_URL set them both to be:
`ASSET_URL=default
AUTH_URL=default`

`"I cant see my cosmetics!"` - Change the first line of the propertise file to be `ASSET_URL=default`.
`"How do I change the title?"` - Change the last line of the propertise file to be `TITLE=YourTitleNameHere`, replacing `YourTitleNameHere` with, of course, your title.

