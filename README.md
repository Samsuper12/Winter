# Winter for OpenWallpaper

Winter is simple video wallpaper for the [OpenWallpaper Plasma][wallpaper_plasma].
Video demonstration: [YouTube][youtube_winter]

Music: Scythe of Luna × Yakui The Maid - Rainmeter (Feat. Macne Nana) [Bandcamp][luna_band] | [SoundCloud][luna_sc] | [VK][luna_vk]

[Download][music_link] music and add to `Winter/Source`folder.

![preview][preview_img]

## Parametres

All of the wallpaper packages must have `wallpaper.ini` file with the information below:

### Information about package and author
|  Variable    | Type           | Description               | Wallpaper Type  |
|    :---:     |     :---:      |     :---:                 |     :---:       |
| Name         | String         | Name of current package   | ALL             |
| Version      | String         | Package version           | ALL             |
| Author       | String         | Author name               | ALL             |
| Email        | String         | Author email              | ALL             |
| AuthorLink   | String         | Author website            | ALL             |
| Comment      | String         | Small text about package  | ALL             |

### Settings parameters
|  Variable    | Type           | Description               | Wallpaper Type  |
|    :---:     |     :---:      |     :---:                 |     :---:       |
| Type         | String         | One of three types        | ALL             |
| Music        | Bool           | Have music or not         | OGL, Gif        |
| StartVolume  | Float          | Start volume              | ALL             |
| FillMode     | String         | Video fill mode           | Video           |

### Resources

|  Variable    | Type           | Description               | Wallpaper Type  |
|    :---:     |     :---:      |     :---:                 |     :---:       |
| Source       | String         | Path to package source    | ALL             |
| MusicSource  | String         | Path to music source      | ALL             |
| PreviewImage | String         | Preview image for Manager | ALL             |


About FillMode you can read in [Qt Documentation][qt_fillmode_doc].

## How to create the wallpaper package

* Create `wallpaper.ini` and set needed variables. See Parametres above
* Add source files (videos, gifs or shared libraries(with source))
* Share!

## Links

* [OpenWallpaper Plasma][wallpaper_plasma]
* [OpenWallpaper Manager][wallpaper_manager]

## Author

* Scythe of Luna - [Bandcamp][luna_band] | [SoundCloud][luna_sc] | [VK][luna_vk]

[//]: # (LINKS)
[qt_doc]: https://doc.qt.io/qt-5/reference-overview.html
[qt_fillmode_doc]: https://doc.qt.io/qt-5/qml-qtmultimedia-video.html#fillMode-prop
[youtube_winter]: https://www.youtube.com/watch?v=saqVNwlUweo

[preview_img]: docs/preview_gh.png
[music_link]: https://drive.google.com/file/d/1o9ZlvhfUjFKOcbIXC5_2L2SzjPibUIcX/view?usp=sharing
[luna_band]: https://scythe-of-luna.bandcamp.com/
[luna_sc]: https://soundcloud.com/scythe_of_luna
[luna_vk]: https://vk.com/scythe_of_luna
[wallpaper_manager]: https://github.com/Samsuper12/OpenWallpaper-Manager
[wallpaper_plasma]: https://github.com/Samsuper12/OpenWallpaper-Plasma
