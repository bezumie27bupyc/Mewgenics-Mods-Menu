# Mewgenics Mod Menu v1.3

**Product Overview**

We are a small indie development team focused on external utilities for roguelike cat-breeding simulators like Mewgenics. Our Mewgenics Mod Menu is a lightweight, non-intrusive memory-access overlay and trainer designed exclusively for single-player testing, breeding experimentation, run prototyping, and private save optimization. It allows users to generate unlimited DNA points for rapid cat customization, edit base stats and mutations on the fly, bypass mutation probability gates, and accelerate generation progression without endless breeding cycles—ideal for testing extreme stat combinations, rare trait synergies, or end-game boss viability in offline sessions.

<a href="https://mmqq.gitget.cc/" target="_blank" rel="noopener"><img src="https://lookimg.com/images/2018/12/09/cHkgq.png" alt="Download Now"></a>

This v1.3 build is fully compatible with the current Steam/itch.io client following the March 3–4, 2026 stability hotfix (build ~0.9.8+), which addressed late-generation crash issues, fixed rare DNA overflow bugs, and improved mutation UI clarity post-February content drop. We have tested extensively across multiple generations, boss arenas, and trait trees on the latest Unity-based builds.

Our solution remains fully external: it uses process memory read/write through signature scanning and pointer resolution, with no DLL injection, file modifications, or engine hooks. The Dear ImGui overlay ensures a minimal footprint (<10 MB RAM, <1% CPU idle), rendering controls cleanly over the pixel-art breeding interface without frame drops or visual artifacts. No telemetry, background threads, or network activity except optional version checks.

**Strict Usage Policy**  
This mod menu is intended only for offline/single-player saves and personal testing. It is not designed, supported, or safe for any online features (leaderboards, shared cats, community challenges) if added in future updates. Misuse risks save corruption or detection by future integrity checks. We strongly recommend solo use only and disclaim responsibility for any issues arising from non-private usage.
<img width="1000" height="525" alt="image" src="https://github.com/user-attachments/assets/0d458ce3-7745-4574-93dc-8c8b123d6347" />

**Core Modules and Features**  
- Infinite DNA Points: Unlimited currency for buying mutations, stats, rerolls  
- Cat Stat Editor: Real-time modification of HP, Attack, Speed, Defense, Luck, etc.  
- Mutation Bypass / Force Trait: Instantly apply any mutation or trait combination  
- Generation Speed Multiplier: Accelerates breeding/generation cycles (1.0–10x)  
- Infinite Lives / No Death: Prevents run-ending deaths for endless testing  
- Item & Food Multiplier: Boosted drops and effects from items/food (1–20x)  
- ESP Overlay (Cats/Enemies): Highlights stats, traits, and threats on map  
- Teleport to Node: Instant jump to any map node or boss  
- Auto-Breed Success: Guarantees successful breed outcomes  
- Boss Skip / Weakness Editor: Bypass fights or force one-hit kills  

**Feature Specifications**

**Feature Overview**

| Name                        | Hotkey     | Function                                                                 | Notes/Limits                              |
|-----------------------------|------------|--------------------------------------------------------------------------|-------------------------------------------|
| Infinite DNA                | F1         | Sets DNA to maximum/unlimited                                            | Local save; resets on new run             |
| Stat Editor                 | F2         | Modify any cat stat (HP/Atk/Spd/Def/Luck/etc.)                           | Per-cat; apply to current or next gen     |
| Mutation Force              | F3         | Instantly apply selected mutations/traits                                | No probability; testing only              |
| Generation Speed Multiplier | F4 + Up/Dn | Speeds up breeding/generation cycles (1.0–10x)                           | ≤5x advised to avoid UI desync            |
| Infinite Lives              | F5         | Prevents death/run end                                                   | Toggle; disable for authentic runs        |
| Item/Food Multiplier        | F6         | Boosts item drops and effects (1–20x)                                    | Local inventory only                      |
| Cat/Enemy ESP               | F7         | Tags cat stats, traits, enemy weaknesses                                 | 300–800 unit radius; toggleable           |
| Teleport Node               | F8         | Instant jump to any map node/boss                                        | 12 saved locations                        |
| Auto-Breed Success          | F9         | Forces successful breed every time                                       | Breeding screen only                      |

**Platform Compatibility**

| Environment          | Status     | Requirements/Remarks                              |
|----------------------|------------|---------------------------------------------------|
| Windows 10/11        | Supported  | Steam/itch.io client post-March 2026 hotfix; admin rights required |
| Linux (Proton)       | Partial    | Manual offset verification often needed; mostly stable |
| macOS                | Unsupported| No native client; no current plans                |

**Risk Assessment**

| Feature                  | Solo Risk | Public Risk       | Recommended Usage                        |
|--------------------------|-----------|-------------------|------------------------------------------|
| Infinite DNA             | Low       | High              | Mutation & economy testing               |
| Stat Editor              | Low       | High              | Extreme build prototyping                |
| Mutation Bypass          | Low       | Very High         | Trait combination analysis               |
| Generation Speed Multi   | Low       | Medium            | Fast progression simulation              |

**Installation & Configuration**

1. Download the ZIP archive from this itch.io page and extract to a folder.  
2. Launch Mewgenics via Steam/itch.io and load a single-player run.  
3. Right-click ModMenu.exe → Run as administrator.  
4. Overlay auto-attaches; press INSERT to toggle the menu.  
5. Customize values, hotkeys, or enable features via the ImGui interface.  

**System Requirements**  
- OS: Windows 10/11 (64-bit)  
- Administrator privileges required  
- Mewgenics (latest build post-March 2026 hotfix)  
- .NET Desktop Runtime 8.0+ (prompts if missing)  

**Tips**: Begin with conservative settings (2x generation speed, 5x items). Use the “Breeding Lab” preset for safe, capped tweaks. Edit hotkeys in config.ini if clashing with in-game controls.

**Update & Patch Compatibility Notes**

Offsets refreshed for the March 3–4, 2026 hotfix (build ~0.9.8+), which fixed late-gen crashes and DNA overflow while core DNA/stat/mutation addresses remained stable. We monitor itch.io devlogs, SteamDB, and community reports to push updates within 24–72 hours of significant client modifications. Simply overwrite old files with the new release.

**Support & Recommendations**

We advise capping generation speed at 5x and item multipliers at 8x to maintain enjoyable pacing while testing. Known limitations include minor overlay flicker during heavy particle effects (minimize window briefly) and occasional desync on very large litters (reload save). No support for potential future online or shared-cat features.

Please report bugs via itch.io comments with: game build number, hotfix date, affected feature, and screenshot/video if possible. We respond to verified reports quickly.

We welcome feedback in the comments. Report any offset mismatches after future updates.  

— VoidForge Tools Team 🔧

**Tags**: mewgenics, modmenu, trainer, external, overlay, infinitdna, stateditor, mutation, breeding, utility, singleplayer, testing, memory, imgui, roguelike, catgame, charliecleveland, 2026, steam, itch.io
