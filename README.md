<h1 align="center">
	<img src="assets/logo.png" width="304" alt="Blåmba!">&nbsp;
</h1>
We'd love to have your content on Blåmba!  

Please [send a pull request](https://github.com/blamba-de/blamba-content-ingest/pulls) with your files to this repo.  
If you have trouble converting the files, have other cool ideas or other cool assets, please [open an issue](https://github.com/blamba-de/blamba-content-ingest/issues/new).

Ideally, sort your content into the folders by type and put it in a folder named after your nickname.

### Operator / group logos

<img src="assets/logo596.gif" width="288">

- ideally .gif file (.png acceptable)
- 72x14 pixel
- 1-bit color (no grayscale), file format itself doesn't matter (RGB24 is OK)
- background color: RGB 102, 204, 102 (#66CC66)
- foreground color: RGB 0, 0, 0 (#000000)

### Color bitmaps (logos)

<img src="assets/cyber-yellow.png" width="208">

- ideally .png file
- 208x208 pixel (or 128x128 pixel)
- RGB24 (8bit color)

### RTTTL ringtones (monophonic)

[butterfly.txt](assets/butterfly.txt)

- .txt file
- compatible with [ringtonetools](https://www.mikekohn.net/file_formats/ringtonetools.php)
- (check with `./ringtonetools -intype rtttl -outtype mid ringtone.txt ringtone.mid`)

### MIDI ringtones (polyphonic)

[AvastYourAss.mid](assets/AvastYourAss.mid)

- .mid file
- compatible with Nokia phones (seem to be a bit picky, ideally try first)
- `Standard MIDI data (format 0) using 1 track`, according to file(1) is probably ideal
- will get parsed by [ringtonetools](https://www.mikekohn.net/file_formats/ringtonetools.php)

### J2ME software/games

- .jar file
- .png preview image (same filename)
- ideally: info about the required screen size (pixels, etc.)

### Wave ringtones ("Real music")

- **not yet supported by Blåmba!**
- .mp3 file (ideally mono already)
- max 15s long
- will get downmixed to 8000 Hz, 1ch (mono)
- will be compressed to either AMR-NB or RealMedia (internally)

### Nokia themes

- **not yet supported by Blåmba!**
- .nth file (really .zip files with different extension)
- .png preview image (same filename)
- .nth archive contains theme_descriptor.xml
- .nth archive contains a number of assets
- please specify screen resolution and tested phone models

### Other cool content?

- If you have other cool content, compatible with retro phones and downloadable via WAP, please send a pull request/issue!