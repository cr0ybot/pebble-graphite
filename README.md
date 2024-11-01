# Graphite

Download at https://stefanheule.com/graphite/.

## Overview

See [stefanheule.com/graphite/](https://stefanheule.com/graphite/).

## Changelog

**Version 1.6** (2024-10-28)

- Update to OpenWeatherMap One Call API 3.0.


**Version 1.5** (2021-10-04)

- Add support for hourly rain forcast from openweathermap.org.


**Version 1.4** (2020-02-18) (no version change, since only the config changed)

- Fix "Celsius" typo in config page.  Thanks @crazyquark.


**Version 1.4** (2017-05-11)

- Fix localized date issue.  Dates should show up in the local language again.


**Version 1.3** (2017-04-10)

- Secondary widgets: shake your watch for 6 additional widgets.
- Add sunrise/sunset widgets.
- Add phone battery widgets (only on Android).
- Add option to change accent color when in quiet mode.
- Improve usage of bluetooth.
- Size optimizations.
- UTC as an explicit option (available as of 2017-03-08 through server-side configuration page update).


**Version 1.2** (2017-03-04)

- Add up to 3 additional timezone widgets.
- Add a battery text widget (two versions, one with percent sign, one without).
- Add option for hourly vibration.
- Fix position of small icons in preview.


**Version 1.1** (2017-02-17)

- Fix position of small icons.


**Version 1.0** (2017-02-16)

- Initial version.


## Building from Source

To build the project in a release configuration, run

    ./configure
    make release

For development, you can build a debug build by running

    ./configure
    make build

### Versioning

The watchface itself uses relatively arbitrary version numbers of MAJOR.MINOR.  In addition to that, the configuration format (the JavaScript config object) is versioned, too, using a single integer.  Different version of the watchface may share the same configuration format.

| Watchface version | Configuration version |
|------------------:|----------------------:|
|     1.0 until 1.1 |                     1 |
|               1.2 |                     2 |
|     1.3 until now |                     3 |

## Contributing

Pull requests are welcome.

## License

Copyright 2016-2017 Stefan Heule

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

