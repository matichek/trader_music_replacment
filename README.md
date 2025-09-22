# Trader Music Replacement Mod for X4 Foundations

This mod replaces the annoying trader section music in stations with your own custom tracks.

## Installation

1. The mod is already in the correct location: `X4 Foundations\extensions\trader_music_replacment\`
2. Enable the mod in the X4 Extensions menu
3. Replace the music files as described below

## Adding Your Music

### Trader Music Files to Replace:

The exact trader section music files are:

- **market_block_music_01.ogg** - Trader music track 1
- **market_block_music_02.ogg** - Trader music track 2  
- **market_block_music_03.ogg** - Trader music track 3
- **market_block_music_04.ogg** - Trader music track 4

Located in: `sfx\`

### How to Replace:

1. **Find the original music files:**
   - You need to extract the original game files using X4's catalog tool
   - Or find the exact filename by listening to existing mods
   
2. **Prepare your replacement:**
   - Convert your music to OGG Vorbis format
   - Name it exactly the same as the original file
   - Place it in: `trader_music_replacment\sfx\[filename].ogg`

3. **Example structure:**
   ```
   trader_music_replacment\
   ├── content.xml
   └── sfx\
      ├── market_block_music_01.ogg
      ├── market_block_music_02.ogg
      ├── market_block_music_03.ogg
      └── market_block_music_04.ogg
   ```

## Notes

- OGG format is required for X4
- Keep file sizes reasonable for performance
- The mod will override original game music files
- Test in-game to ensure correct replacement

## Troubleshooting

- Make sure the mod is enabled in Extensions menu
- Verify file names match exactly (case-sensitive)
- Check that files are in OGG format
- Restart the game after adding new music files

Userful community guide for replacing general music:
https://docs.google.com/document/d/1IwzAoA_oAc2o9BKTlkBLUuzxUMQm2n0FRq5HzY-3zrI/edit?tab=t.0