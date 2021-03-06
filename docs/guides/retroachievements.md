# RetroAchievements In RetroArch

## **What are RetroAchievements?**

[retroachievements.org](https://retroachievements.org/) is a service that provides a trophy/achievement unlocking mechanism similar to modern consoles, for retro games.

!!! Warning
    The service is not maintained by RetroArch or the Libretro team.

!!! Note
    If you want to contribute, please update RetroArch and cores to get the latest fixes on the RetroAchievements feature, then in order to propose improvements to this document, [do it via GitHub](https://github.com/libretro/docs/tree/master/docs/guides/retroachievements.md) using "Pull Requests".

## **How to setup achievements**

1. Register an account on [retroachievements.org](https://retroachievements.org/) (don't forget to confirm your account creation with the email they send to you).
2. Open Retroarch and go to Settings->Achievements.
3. Enable the functionality and fill in your retroachievements credentials.

!!! Note
    The hardcore mode prevents you from using emulation features like savestates, slow motion, and cheats, **BUT** it gives you double points.

![](../image/retroarch/retroachievements/achievements_settings.jpg)

## **Check your connection to the service**

**You need an active internet connection.**

In this example, we are using the game Chrono Trigger (USA) with the Snes9x core.

Launch the game and trigger the Quick Menu.

Go to Achievements and you should see a list of the unlockable trophies for this game.

![](../image/retroarch/retroachievements/achievements_list.png)

## **Check your progress**

On the retroachievements website, you can login and access your account page.

You should be able to check your progress in the games and see which trophies you unlocked.

Trophies unlocked in hardcore mode are marked with a special color.

You can also check the progress of your friends and add comments on their trophies.

![](../image/retroarch/retroachievements/achievements_progress.png)

## **Cores Compatibility**

### Arcade (various manufacturers)

#### Arcade

| Core                                               | Supported | Notes |
|----------------------------------------------------|:---------:|:------|
| [FinalBurn Neo](https://github.com/libretro/FBNeo) | ✔         | AES bios is required for most Neo Geo achievements. AES Asia is generally English. |
| [MAME](https://github.com/libretro/mame)           | ✕         |       |

### Atari

#### 2600

| Core                                                           | Supported | Notes |
|----------------------------------------------------------------|:---------:|:------|
| [Stella](https://github.com/libretro/stella-libretro)          | ✔         |       |
| [Stella 2014](https://github.com/libretro/stella2014-libretro) | ✔         |       |

#### 7800

| Core                                                        | Supported | Notes |
|-------------------------------------------------------------|:---------:|:------|
| [ProSystem](https://github.com/libretro/prosystem-libretro) | ✔         |       |

#### Lynx

| Core                                                             | Supported | Notes |
|------------------------------------------------------------------|:---------:|:------|
| [Beetle Handy](https://github.com/libretro/beetle-lynx-libretro) | ✔         | Also known as Beetle Lynx |
| [Handy](https://github.com/libretro/libretro-handy)              | ✔         |       |

### Bandai

#### Wonderswan / Wonderswan Color

| Core                                                              | Supported | Notes |
|-------------------------------------------------------------------|:---------:|:------|
| [Beetle Cygne](https://github.com/libretro/beetle-wswan-libretro) | ✔         |       |

### Coleco

#### ColecoVision

| Core                                                    | Supported | Notes |
|---------------------------------------------------------|:---------:|:------|
| [blueMSX](https://github.com/libretro/blueMSX-libretro) | ✔         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)      | ✔         | Requires games in `coleco` subdirectory, exact archives just like arcade. Not all games may be linked for this core. |
| [SMS Plus GX](https://github.com/libretro/smsplus-gx)   | ✕         | Coleco games aren't fully playable in this core yet. |

### GCE

#### Vectrex

| Core                                              | Supported | Notes |
|---------------------------------------------------|:---------:|:------|
| [vecx](https://github.com/libretro/libretro-vecx) | ✔         |       |

### Microsoft

#### MSX / MSX2

| Core                                                    | Supported | Notes |
|---------------------------------------------------------|:---------:|:------|
| [blueMSX](https://github.com/libretro/blueMSX-libretro) | ✔         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)      | ✔         | Requires games in `msx` subdirectory, exact archives just like arcade. Not all games may be linked for this core. MSX2 is not supported. |
| [fMSX](https://github.com/libretro/fmsx-libretro)       | ✕         | Emulation is too unstable to support. |

### NEC

#### PC Engine - TurboGrafx-16 / PC Engine CD - TurboGrafx-CD

| Core                                                                        | Supported | Notes |
|-----------------------------------------------------------------------------|:---------:|:------|
| [Beetle PCE FAST](https://github.com/libretro/beetle-pce-fast-libretro)     | ✔         | Highest speed. Does not support SuperGrafx games. |
| [Beetle SuperGrafx](https://github.com/libretro/beetle-supergrafx-libretro) | ✔         | High speed. Supports SuperGrafx games. |
| [Beetle PCE](https://github.com/libretro/beetle-pce-libretro)               | ✔         | High accuracy, lower speed. Supports SuperGrafx games. |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)                          | ✔         | Requires games in `pce`, `tg16`, or `sgx` subdirectories, exact archives just like arcade. Not all games may be linked for this core. CD is not supported. |

#### PC-FX

| Core                                                             | Supported | Notes |
|------------------------------------------------------------------|:---------:|:------|
| [Beetle PC-FX](https://github.com/libretro/beetle-pcfx-libretro) | ✔         |       |

#### PC-8000 / PC-8800

| Core                                                    | Supported | Notes |
|---------------------------------------------------------|:---------:|:------|
| [QUASI88](https://github.com/libretro/quasi88-libretro) | ✔         | Some games may be unsupported in Retroarch due to missing options. Sets generally expect the MkIISR bios. |

### Nintendo

#### Nintendo DS

| Core                                                    | Supported | Notes |
|---------------------------------------------------------|:---------:|:------|
| [DeSmuME](https://github.com/libretro/desmume)          | ✔         | External BIOS recommended, needs to be enabled in core options |
| [DeSmuME 2015](https://github.com/libretro/desmume2015) | ✔         |       |
| [MelonDS](https://github.com/libretro/melonDS)          | ✔         | BIOS required |

#### Game Boy / Game Boy Color

| Core                                                      | Supported | Notes |
|-----------------------------------------------------------|:---------:|:------|
| [SameBoy](https://github.com/libretro/SameBoy)            | ✔         |       |
| [Gambatte](https://github.com/libretro/gambatte-libretro) | ✔         |       |
| [Gearboy](https://github.com/libretro/gearboy)            | ✔         |       |
| [VBA-M](https://github.com/libretro/vbam-libretro)        | ✔         | Has gyro support via analog sticks |
| [mGBA](https://github.com/libretro/mgba)                  | ✔         |       |
| [Mesen-S](https://github.com/SourMesen/Mesen-S)           | ✔         | Currently the only supported core with complete SGB support. Supports GB and GBC without SGB as well. |
| [Emux GB](https://github.com/libretro/emux)               | ✕         |       |
| [TGB Dual](https://github.com/libretro/tgbdual-libretro)  | ✕         |       |
| [bsnes](https://github.com/libretro/bsnes-libretro)       | ✕         | SGB only |
| [bsnes-hd](https://github.com/DerKoun/bsnes-hd)           | ✕         | SGB only |
| [higan Accuracy](https://gitlab.com/higan/higan)          | ✕         | SGB only, [Achievement support isn't going to be added](https://forums.libretro.com/t/is-higan-105-accuracy-supposed-to-be-slow-on-a-3-ghz-ivy-bridge-i7/13405/7?u=esoptron) |
| [nSide Balanced](https://github.com/libretro/nSide)       | ✕         | SGB only, [Achievement support isn't going to be added](https://forums.libretro.com/t/is-higan-105-accuracy-supposed-to-be-slow-on-a-3-ghz-ivy-bridge-i7/13405/7?u=esoptron) |

#### Game Boy Advance

| Core                                                          | Supported | Notes |
|---------------------------------------------------------------|:---------:|:------|
| [mGBA](https://github.com/libretro/mgba)                      | ✔         |       |
| [VBA-M](https://github.com/libretro/vbam-libretro)            | ✔         |       |
| [VBA Next](https://github.com/libretro/vba-next)              | ✔         |       |
| [Beetle GBA](https://github.com/libretro/beetle-gba-libretro) | ✔         |       |
| [gpSP](https://github.com/libretro/gpsp)                      | ✕         |       |
| [Meteor](https://github.com/libretro/meteor-libretro)         | ✕         |       |

#### NES

| Core                                                  | Supported | Notes |
|-------------------------------------------------------|:---------:|:------|
| [FCEUmm](https://github.com/libretro/libretro-fceumm) | ✔         | Supports FDS |
| [Mesen](https://github.com/SourMesen/Mesen)           | ✔         | Supports FDS, very high accuracy |
| [QuickNES](https://github.com/libretro/QuickNES_Core) | ✔         |       |
| [Nestopia UE](https://github.com/libretro/nestopia)   | ✕         | [**Achievements are not fully supported yet**](https://github.com/libretro/docs/pull/10) |
| [bnes](https://github.com/libretro/bnes-libretro)     | ✕         |       |
| [Emux NES](https://github.com/libretro/emux)          | ✕         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)    | ✕         | Requires games in `nes` or `fds` subdirectories, exact archives just like arcade. Not supported at this time. |

#### Nintendo 64

| Core                                                                 | Supported | Notes |
|----------------------------------------------------------------------|:---------:|:------|
| [Mupen64Plus-Next](https://github.com/libretro/mupen64plus-libretro) | ✔         | Supports greater graphic customization and upscaling |
| [ParaLLEl N64](https://github.com/libretro/parallel-n64)             | ✔         | Supports 64DD games. Can play -some- hacks reliant on low accuracy via alternate plugins. |

#### Pokemon Mini

| Core                                             | Supported | Notes |
|--------------------------------------------------|:---------:|:------|
| [PokeMini](https://github.com/libretro/PokeMini) | ✔         |       |

#### SNES

| Core                                                                         | Supported | Notes |
|------------------------------------------------------------------------------|:---------:|:------|
| [Snes9x](https://github.com/libretro/snes9x)                                 | ✔         | High speed, moderate accuracy. Actively maintained. |
| [Snes9x 2010](https://github.com/libretro/snes9x2010)                        | ✔         |       |
| [Snes9x 2005 Plus](https://github.com/libretro/snes9x2005)                   | ✔         |       |
| [Snes9x 2005](https://github.com/libretro/snes9x2005)                        | ✔         |       |
| [Snes9x 2002](https://github.com/libretro/snes9x2002)                        | ✔         |       |
| [Mesen-S](https://github.com/SourMesen/Mesen-S)                              | ✔         | High accuracy, high performance cost. Actively maintained. |
| [Beetle bsnes](https://github.com/libretro/beetle-bsnes-libretro)            | ✔         |       |
| [bsnes](https://github.com/libretro/bsnes-libretro)                          | ✕         |       |
| [bsnes-hd](https://github.com/DerKoun/bsnes-hd)                              | ✕         |       |
| [bsnes-mercury Accuracy](https://github.com/libretro/bsnes-mercury)          | ✔         |       |
| [bsnes-mercury Balanced](https://github.com/libretro/bsnes-mercury)          | ✔         |       |
| [bsnes-mercury Performance](https://github.com/libretro/bsnes-mercury)       | ✔         |       |
| [bsnes 2014 Accuracy](https://github.com/libretro/bsnes-libretro)            | ✔         |       |
| [bsnes 2014 Balanced](https://github.com/libretro/bsnes-libretro)            | ✔         |       |
| [bsnes 2014 Performance](https://github.com/libretro/bsnes-libretro)         | ✔         |       |
| [bsnes C++98 (v085)](https://github.com/libretro/bsnes-libretro-cplusplus98) | ✔         |       |
| [higan Accuracy](https://gitlab.com/higan/higan)                             | ✕         | [Achievement support isn't going to be added](https://forums.libretro.com/t/is-higan-105-accuracy-supposed-to-be-slow-on-a-3-ghz-ivy-bridge-i7/13405/7?u=esoptron) |
| [nSide Balanced](https://github.com/libretro/nSide)                          | ✕         | [Achievement support isn't going to be added](https://forums.libretro.com/t/is-higan-105-accuracy-supposed-to-be-slow-on-a-3-ghz-ivy-bridge-i7/13405/7?u=esoptron) |

#### Virtual Boy

| Core                                                        | Supported | Notes |
|-------------------------------------------------------------|:---------:|:------|
| [Beetle VB](https://github.com/libretro/beetle-vb-libretro) | ✔         |       |

### Sega

#### Master System / MegaDrive - Genesis

| Core                                                           | Supported | Notes |
|----------------------------------------------------------------|:---------:|:------|
| [Genesis Plus GX](https://github.com/libretro/Genesis-Plus-GX) | ✔         |       |
| [BlastEm](https://github.com/libretro/blastem)                 | ✔         | Cycle accurate. Genesis/MegaDrive only. |
| [Picodrive](https://github.com/libretro/picodrive)             | ✔         |       |
| [Gearsystem](https://github.com/drhelius/Gearsystem)           | ✔         |       |
| [SMS Plus GX](https://github.com/libretro/smsplus-gx)          | ✔         | Master System only |
| [Emux SMS](https://github.com/libretro/emux)                   | ✕         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)             | ✕         | Requires games in `megadriv` or `sms` subdirectories, exact archives just like arcade. Not supported at this time. |

#### 32X / 32X CD

| Core                                               | Supported | Notes |
|----------------------------------------------------|:---------:|:------|
| [Picodrive](https://github.com/libretro/picodrive) | ✔         | Emulation quality can be dodgy. |

#### Game Gear

| Core                                                           | Supported | Notes |
|----------------------------------------------------------------|:---------:|:------|
| [Genesis Plus GX](https://github.com/libretro/Genesis-Plus-GX) | ✔         |       |
| [Gearsystem](https://github.com/drhelius/Gearsystem)           | ✔         |       |
| [SMS Plus GX](https://github.com/libretro/smsplus-gx)          | ✔         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)             | ✕         | Requires games in `gamegear` subdirectory, exact archives just like arcade. Not supported at this time. |

#### SG-1000

| Core                                                           | Supported | Notes |
|----------------------------------------------------------------|:---------:|:------|
| [Genesis Plus GX](https://github.com/libretro/Genesis-Plus-GX) | ✔         |       |
| [Gearsystem](https://github.com/drhelius/Gearsystem)           | ✔         |       |
| [blueMSX](https://github.com/libretro/blueMSX-libretro)        | ✔         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)             | ✔         | Requires games in `sg1000` subdirectory, exact archives just like arcade. Not all games may be linked for this core. |

#### Sega CD - Mega-CD

| Core                                                           | Supported | Notes |
|----------------------------------------------------------------|:---------:|:------|
| [Genesis Plus GX](https://github.com/libretro/Genesis-Plus-GX) | ✔         |       |
| [Picodrive](https://github.com/libretro/picodrive)             | ✔         |       |

#### Saturn

| Core                                                                | Supported | Notes |
|---------------------------------------------------------------------|:---------:|:------|
| [Beetle Saturn](https://github.com/libretro/beetle-saturn-libretro) | ✔         |       |
| [Yabause](https://github.com/libretro/yabause)                      | x         |       |
| [Yabasanshiro](https://github.com/libretro/yabause)                 | x         |       |
| [Kronos](https://github.com/libretro/yabause)                       | x         |       |

### SNK

#### Neo Geo Pocket / Neo Geo Pocket Color

| Core                                                             | Supported | Notes |
|------------------------------------------------------------------|:---------:|:------|
| [Beetle NeoPop](https://github.com/libretro/beetle-ngp-libretro) | ✔         |       |
| [RACE](https://github.com/libretro/RACE)                         | ✔         |       |
| [FinalBurn Neo](https://github.com/libretro/FBNeo)               | ✕         | Requires games in `ngp` subdirectory, exact archives just like arcade. Not supported at this time. |

### Sony

#### PlayStation

| Core                                                             | Supported | Notes |
|------------------------------------------------------------------|:---------:|:------|
| [Beetle PSX HW](https://github.com/libretro/beetle-psx-libretro) | ✔         | Identical to Beetle PSX, with extra hardware features. High accuracy. |
| [Beetle PSX](https://github.com/libretro/beetle-psx-libretro)    | ✔         |       |
| [PCSX ReARMed](https://github.com/libretro/pcsx_rearmed)         | ✔         | Lower accuracy than Beetle PSX (HW), higher speed. |

### The 3DO Company (various manufacturers)

#### 3DO

| Core                                                | Supported | Notes |
|-----------------------------------------------------|:---------:|:------|
| [Opera](https://github.com/libretro/opera-libretro) | ✔         |       |
