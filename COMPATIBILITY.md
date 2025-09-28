# Mod Compatibility Guide

The Sons of Sparda mod is designed to be compatible with most RimWorld mods. Below is detailed compatibility information.

## ✅ **Fully Compatible Mods**

### **Character Creation & Customization**
- **Prepare Carefully** - Recommended for creating Sons of Sparda characters
- **Character Editor** - Full support for trait editing
- **Facial Stuff** - Character appearance works normally
- **Hair Modded** - All hair styles compatible

### **Combat & Weapons**
- **Combat Extended** - Special penetration bonuses included
- **Vanilla Weapons Expanded** - All weapons work with damage bonuses
- **Medieval Overhaul** - Melee bonuses apply to all melee weapons
- **Rimsenal** - Firearm bonuses work with modded guns
- **Run and Gun** - Movement bonuses stack properly

### **Races & Genetics**
- **Humanoid Alien Races** - Sons of Sparda can be any race
- **Pawnmorpher** - Transformations don't conflict with traits
- **Genetic Rim** - Genetic modifications stack with demonic heritage
- **Alpha Animals** - Entity slayer bonuses work against modded creatures

### **Magic & Supernatural**
- **RimWorld of Magic** - Vergil conflicts with magic traits (lore accurate)
- **Vanilla Psycasts Expanded** - Reduced psychic sensitivity affects all psycasts
- **Call of Cthulhu** - Demonic resistance helps against cosmic horrors
- **Alpha Gods** - Divine powers don't conflict with demonic heritage

### **Technology & Science Fiction**
- **Android Tiers** - Androids can't have demonic traits (balanced)
- **Vanilla Factions Expanded - Mechanoids** - Entity bonuses work vs all mechs
- **Save Our Ship 2** - Vacuum resistance works in space
- **Glittertech** - Advanced weapons benefit from damage bonuses

### **Quality of Life**
- **Dubs Bad Hygiene** - Hygiene stats work normally
- **RocketMan** - Performance optimization compatible
- **Camera+** - No conflicts
- **Allow Tool** - No conflicts

### **Multiplayer**
- **Multiplayer Mod** - Fully synchronized, no desync issues
- **Rimworld Together** - Compatible with shared sessions

## ⚠️ **Partial Compatibility**

### **Trait Mods**
- **Vanilla Traits Expanded** - Some negative traits conflict by design
- **More Trait Slots** - Works but balance may be affected
- **Consolidated Traits** - May need load order adjustment

### **Survival Mods**
- **Dubs Bad Hygiene** - Enhanced constitution affects hygiene needs
- **Combat Extended** - Armor penetration values may need balancing
- **Vanilla Cooking Expanded** - Food preferences work but may be overwhelming

## ❌ **Known Incompatibilities**

### **None Currently Identified**
The mod uses standard RimWorld systems and should work with any properly made mod.

## 🔧 **Load Order Recommendations**

### **Essential Load Order:**
1. **Harmony** (if separate)
2. **Core**
3. **Royalty/Ideology/Biotech/Odyssey**
4. **Humanoid Alien Races**
5. **Character creation mods** (Prepare Carefully, etc.)
6. **Major framework mods** (VFE Core, etc.)
7. **Combat mods** (Combat Extended)
8. **Other content mods**
9. **Sons of Sparda** (load near the end)
10. **Patch mods**

## 🛠️ **Technical Compatibility Features**

### **Conditional Patches**
- Automatic compatibility with Combat Extended
- Dynamic trait conflicts with other mods
- Safe stat additions that don't break other systems

### **Safe Implementation**
- Uses standard RimWorld stat systems
- No custom C# code that could conflict
- Follows vanilla naming conventions
- Proper XML structure and inheritance

### **Compatibility Stats**
When compatible mods are detected, additional stats are applied:
- **Combat Extended**: Penetration bonuses
- **Magic Mods**: Anti-magic resistance for Vergil
- **Alien Races**: Works with all race stat modifiers

## 🐛 **Reporting Compatibility Issues**

If you encounter issues with specific mods:

1. **Check load order** - Sons of Sparda should load after most content mods
2. **Verify mod versions** - Ensure all mods are updated
3. **Test without other mods** - Isolate the conflict
4. **Report on GitHub** - Include mod list and error logs

### **Issue Report Template**
```
- RimWorld Version: 
- Sons of Sparda Version:
- Conflicting Mod:
- Error Details:
- Load Order:
```

## 📋 **Future Compatibility Plans**

- **Alpha Genes**: Enhanced genetic compatibility
- **Vanilla Expanded Series**: Specific patches for new content
- **Popular Race Mods**: Dedicated race-specific bonuses
- **Major Combat Overhauls**: Balanced integration

---

The Sons of Sparda mod prioritizes compatibility and should work seamlessly with your existing mod setup!