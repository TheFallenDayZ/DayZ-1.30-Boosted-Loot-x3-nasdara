::: {align="center"}
# ☣ FALLENZ

### DAYZ 1.30 · x3 BOOSTED LOOT

**Survive the outbreak. Gear up. Stay alive.**

*FallenZ Community Servers · PlayStation*

------------------------------------------------------------------------

**BOOSTED LOOT · SURVIVAL · COMMUNITY**
:::

## 🧟 About FallenZ

Welcome to **FallenZ**, a DayZ community built around survival, boosted
loot, and an active player community.

This repository documents the **FallenZ DayZ 1.30 x3 Boosted Loot
configuration**. It is intended as a clear reference for the loot
economy files and server setup associated with the FallenZ experience.

> **Loot more. Explore further. Survive longer.**

## 📦 What Does x3 Boosted Loot Mean?

The **x3** label describes the intended boosted-loot experience: more
rewarding scavenging than a standard survival setup, while keeping
exploration and survival at the heart of the game.

Actual loot quantities and spawn behaviour depend on the configuration
files used by the server. The x3 label alone does not automatically
multiply every item or every loot setting by three.

## 🌍 FallenZ Community

FallenZ community server worlds include:

-   **NASDARA**
-   **SAKHAL**

Server features and schedules may vary by world. Check the community's
latest announcements for current server details, events, raid schedules,
and updates.

## 🗂️ Configuration Overview

The repository may contain DayZ economy and loot configuration files,
such as:

  -----------------------------------------------------------------------
  File / setting                      Purpose
  ----------------------------------- -----------------------------------
  `types.xml`                         Defines item types and
                                      economy-related values, including
                                      nominal and minimum quantities,
                                      lifetime, restock, and flags where
                                      supported

  `events.xml`                        Defines dynamic event
                                      configuration, where used

  `globals.xml`                       Contains global economy settings,
                                      where used

  `cfgeconomycore.xml`                Connects economy configuration
                                      files and folders, where used
  -----------------------------------------------------------------------

Only files actually included in this repository should be treated as
part of the supplied configuration. File names and supported values can
differ by server setup.

## ⚙️ Installation Notes

1.  **Back up your current files** before making any changes.
2.  Confirm that the configuration is intended for your **DayZ version
    and platform**.
3.  Upload the required XML files to the correct location in your
    server's mission or economy configuration.
4.  Keep the existing XML structure and required attributes intact.
5.  Restart the server as required by your host.
6.  Review server logs and test loot spawns in-game after applying
    changes.

**Important:** This README is documentation, not a guarantee that every
setting is compatible with every DayZ 1.30 server environment. Verify
the target file paths, XML schema, and platform limitations before
deploying. Do not replace unrelated economy files unless you intend to
change their behaviour.

## 🔍 Troubleshooting

-   **Loot does not appear boosted:** Check that the intended XML file
    was uploaded to the active mission and that the server is loading
    it.
-   **Some items are uncommon or missing:** Check the item's
    configuration, category, spawn flags, and any related event
    configuration.
-   **Server errors after an edit:** Restore your backup and validate
    the XML syntax before trying again.
-   **Changes do not appear immediately:** Follow your host's restart
    and persistence guidance, and test in a controlled area.

## 🛡️ Community & Credits

**FALLENZ** is the community identity for this configuration. Please
retain the branding when sharing or adapting this repository, and credit
FallenZ when redistributing your own modified version.

For the latest server information, updates, and community announcements,
visit:

**FallenZ Hub:** https://www.fallenzhub.shop

------------------------------------------------------------------------

::: {align="center"}
### ☣ WELCOME TO THE WASTELAND

**FALLENZ · DAYZ 1.30 · x3 BOOSTED LOOT**

*Trust no one. Watch your back. Keep surviving.*
:::
