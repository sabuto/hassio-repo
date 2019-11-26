# Hass.io Add-on: Jackett Proxy Server


![Supports aarch64 Architecture][aarch64-shield] 
![Supports amd64 Architecture][amd64-shield] 
![Supports armhf Architecture][armhf-shield] 
![Supports armv7 Architecture][armv7-shield] 
![Supports i386 Architecture][i386-shield] 


[![GitHub Release][releases-shield]][releases]
![License][license-shield]
![Travis Ci][travis-shield]
[![GitHub Activity][commits-shield]][commits]

* * *
![Jackett Logo](images/jackett-banner.png)


## About

You can use this add-on to install Jackett, which is an open-source indexer scraper. Jackett works as a proxy server: it translates queries from apps (Sonarr, Radarr, SickRage, CouchPotato, Mylar, Lidarr, DuckieTV, qBittorrent, Nefarious etc) into tracker-site-specific http queries. For more information, please see [Jackett].

## Installation

The installation of this add-on is straightforward and easy to do.

1. Navigate in your Home Assistant frontend to **Hass.io** -> **Add-on Store**.
2. Add the Hass.io add-on repository https://github.com/Sabuto/hassio-repo/.
3. Install the "Jackett" add-on.

## How to use

To get the add-on running:

1. Start the add-on.
2. Have some patience and wait a couple of minutes.
3. Check the add-on log output to see the result.


## Configuration

**Note**: _Remember to restart the add-on when the configuration is changed._

Example add-on configuration, with all available options:

```json
{
    "black_hole": "/share/blackhole"
}
```

**Note**: _This should only be changed if you need the torrent files to be saved in a different location._

### Option: `black_hole`

The `black_hole` option controls the location of saved torrent files. It can be set to share, config or ssl folders.


## Support

In case you've found a bug, please open an issue on our GitHub [issue].

## License

MIT License
Copyright (c) 2019 Robert Dunne

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[Jackett]: https://github.com/Jackett/Jackett
[issue]: https://github.com/Sabuto/hassio-jackett/issues
[travis-shield]: https://img.shields.io/travis/sabuto/hassio-jackett
[releases-shield]: https://img.shields.io/github/v/release/sabuto/hassio-jackett
[releases]: https://github.com/sabuto/hassio-jackett/releases
[license-shield]: https://img.shields.io/github/license/sabuto/hassio-jackett
[commits-shield]: https://img.shields.io/github/commit-activity/y/Sabuto/hassio-jackett.svg
[commits]: https://github.com/Sabuto/hassio-jackett/commits/