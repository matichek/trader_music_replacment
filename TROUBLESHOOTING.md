# Music Not Replacing - Troubleshooting Steps

## Check These Issues:

### 1. Mod Priority/Loading Order
- X4 sometimes doesn't load mods properly if content.xml has issues
- Make sure no other mods conflict with music

### 2. Version Issue in content.xml
- Your version="100" might be too high
- Try changing to version="1.0" instead

### 3. File Encoding/Format
- Make sure OGG files are proper Vorbis encoding
- Check file sizes aren't 0 bytes
- Verify files aren't corrupted

### 4. Game Cache
- X4 might be caching the original files
- Try clearing game cache/temp files

### 5. Mod Loading
- Disable mod, restart game
- Re-enable mod, restart game again
- Check Extensions menu shows mod as "loaded" not just "enabled"

## How to Check if Mod is LOADED vs ENABLED:

1. **Extensions Menu Check:**
   - In X4 main menu → Extensions
   - Your mod should show with a checkmark (enabled)
   - Look for any error messages or red text
   - Some mods show "Status: Loaded" vs just enabled

2. **Debug Method - Break Something on Purpose:**
   - Rename content.xml to content_backup.xml temporarily
   - Restart X4 and check Extensions menu
   - If mod disappears = it WAS loading the content.xml
   - If mod still shows = game isn't reading your mod folder

3. **Log File Check:**
   - Check X4 logs in: Documents\Egosoft\X4\[your save]\
   - Look for mod loading errors

## Quick Fixes to Try:

1. **Fix content.xml version** ✓ (Done)
2. **Try the debug method above**
3. **Check OGG file integrity**
4. **Test with just one file first**
5. **Try different mod ID name**
