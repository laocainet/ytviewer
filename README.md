# YTViewer

**YTViewer** is simple YouTube views bot.

## Content

- [Content](#content)
- [Installation](#installation)
  - [Windows](#windows)
  - [Unix](#unix)
- [Usage](#usage)
- [Documentation](#documentation)
- [Disclaimer](#disclaimer)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Installation

### Windows

* Install [Git](https://git-scm.com/download/win), [Python3.6+](https://www.python.org/downloads) and web browser ([Google Chrome](https://www.google.com/chrome) or [Firefox](https://www.mozilla.org/firefox/new)).
* [Download](https://github.com/DeBos99/ytviewer/archive/master.zip) this repository or run following command in the command prompt:
```
git clone https://gitlab.com/DeBos/ytviewer.git
```
* Open ytviewer folder.
* Run install.bat

### Unix

* Run following commands in the terminal:
```
curl -fs https://gitlab.com/DeBos/mpt/raw/master/mpt.sh | sh -s install "git python"
git clone https://gitlab.com/DeBos/ytviewer.git
cd ytviewer
make
```

## Usage

* Run following command in the command prompt or the terminal:
```
python main.py -u URL -B <firefox|chrome> [-p N] [-P FILE] [-R REFERER|FILE] [-U USER_AGENT|FILE] [-D N]
```

## Documentation

| Short                | Long                          | Description                                    | Default value           | Required           |
| :------------------- | :---------------------------- | :--------------------------------------------: | :---------------------: | :----------------: |
| -h                   | --help                        | Show help message and exit.                    | :x:                     | :x:                |
| -u URL               | --url URL                     | Set URL.                                       | :x:                     | :heavy_check_mark: |
| -B <firefox\|chrome> | --browser <firefox\|chrome>   | Set browser.                                   | :x:                     | :heavy_check_mark: |
| -p N                 | --processes N                 | Set number of processes.                       | 15                      | :x:                |
| -P FILE              | --proxies FILE                | Set path to proxies list.                      | Proxy list from API.    | :x:                |
| -R REFERER\|FILE     | --referer REFERER\|FILE       | Set referer \| Set path to referer list.       | https://google.com      | :x:                |
| -U USER_AGENT\|FILE  | --user-agent USER_AGENT\|FILE | Set user agent \| Set path to user agent list. | Random user agent.      | :x:                |
| -D N                 | --duration N                  | Set duration of view.                          | 35-85% of video length. | :x:

## Disclaimer

**YTViewer** was created for educational purposes and I'm not taking responsibility for any of your actions.

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos](https://gitlab.com/DeBos)

## Contact

* Telegram: [@DeBos99](https://t.me/DeBos99)
* Instagram: [@DeBos98](https://www.instagram.com/DeBos98)
* Reddit: [DeBos99](https://www.reddit.com/user/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
