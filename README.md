# Minecraft Launcher Index
An ever-expanding list of Minecraft game launchers.

# Adding a launcher
You can either: <br>
* [Create a new issue](https://github.com/deprecatedbrain/minecraft-launcher-index/issues/new) with the project and basic information or <br>
* [Fork](https://github.com/deprecatedbrain/minecraft-launcher-index/fork) this repository, add your project to the README.md, and make a pull request.
If you're going to fork it and modify the readme, I'd recommend using [this](https://www.tablesgenerator.com/markdown_tables) markdown table editor with compact mode turned on. You can import the table through it and edit it.

# Launchers

## Modular Launchers
Launchers designed for flexibility and customization. They support adding mods, resource packs, modloaders (like Forge, Fabric, or Quilt), and managing multiple game instances.
| Project | Description | Language |
|---|---|---|
| [Modrinth](https://modrinth.com/app) | A unique, open source launcher that allows you to play your favorite mods, and keep them up to date, all in one neat little package. | Closed-Source |
| [CurseForge](https://www.curseforge.com/download/app) | Download and manage your addons, CC and mods with the CurseForge app! | Closed-Source |
| [Prism Launcher](https://prismlauncher.org) | An open source Minecraft launcher with the ability to manage multiple instances, accounts and mods. Focused on user freedom and free redistributability. | C++ |
| [SKlauncher](https://skmedix.pl/) | SKlauncher is a launcher that offers seamless integration of Fabric, Forge, NeoForge and Quilt modloaders, enabling you to effortlessly customize your Minecraft experience. | Closed-Source |
| [X Minecraft Launcher](https://xmcl.app) | An Open Source Minecraft Launcher with Modern UX. Provide a Disk Efficient way to manage all your Mods! | TypeScript / Vue (Electron) |
| [OLauncher](https://github.com/olauncher/olauncher) | A modified version of the old Minecraft Launcher supporting Microsoft authentication and more. | Closed-Source / Shell [^1] |

## PVP/Performance-focused Launchers
Launchers tailored for competitive play and performance. They provide optimized Minecraft clients with built-in performance tweaks, cosmetics, and PvP enhancements. Typically do not support adding custom mods.
| Project | Description | Language |
|---|---|---|
| [Lunar Client](https://www.lunarclient.com/) | Popular, fast, and modern client focused on PvP and performance. Offers many built-in mods and cosmetics. | Closed-Source |
| [Badlion Client](https://www.badlion.net/) | PvP and performance-enhancing client with built-in mods, anti-cheat (BAC), and cosmetic options. Owned by Lunar Client. | Closed-Source |
| [LabyMod](https://labymod.net/) | LabyMod is a free Minecraft client that upgrades the game experience with improved performance and a faster launcher. | Closed-Source |
| [Feather Client](https://feathermc.com/) | Lightweight and modern PvP client with mod support. | Closed Source |
| [CheatBreaker](https://cheatbreaker.net/) | One of the first major PvP clients with built-in mods, FPS boosting, and cosmetics. Inspired newer clients like Lunar. | [Java](https://github.com/Decencies/CheatBreaker) |
| [Salwyrr](https://www.salwyrr.com/) | Fairly basic but still good client with mods, cosmetics, support for modern versions, and an anti-cheat. | Closed-Source |

## Server Wrappers
Tools that help manage Minecraft servers more easily by adding features like console access, automation, plugin management, backups, and web interfaces.
| Project | Description | Language |
|---|---|---|
| [MC Server Soft](https://www.mcserversoft.com/) | A long-standing server wrapper for Windows that provides a graphical user interface for managing Minecraft servers. | C# [^2] |
| [Fork](https://www.fork.gg/) | A modern, open-source server manager with a focus on a clean user interface and ease of use, designed for Windows. | C# / Blazor |
| [Moonlight](https://moonlightpanel.xyz/) | A next-generation, open-source hosting panel with a responsive UI and an efficient backend for managing game servers. | C# / Blazor / SCSS |
| [McMyAdmin](https://mcmyadmin.com/) | A well-established and widely-used web control panel and administration console for Minecraft servers. No longer active, succeeded by AMP. | Closed-Source |
| [PufferPanel](https://pufferpanel.com/) | An open-source game server management panel with support for a wide variety of games, including Minecraft. | Go / Vue.js |
| [Crafty Controller](https://craftycontrol.com/) | A free and open-source, self-hosted web server for creating and managing Minecraft servers with a user-friendly interface. | Python |
| [Pterodactyl](https://pterodactyl.io/) | A popular, free, and open-source game server management panel that runs game servers in isolated Docker containers. | PHP / React / Go |
| [AMP](https://cubecoders.com/AMP) | A simple-to-use, self-hosted web control panel for game servers on Windows and Linux. | Closed-Source (Web) |
| [Mark2](https://github.com/mark2devel/mark2) | A Minecraft multi-server wrapper with a rich feature-set and powerful plugin interface. | Python / Twisted |

#### Notes
[^1]: Modifies the original closed-source launcher with shell commands.
[^2]: Original is closed-source so the language is either an educated guess or from the creator or another source.
