# MusicBot

[![GitHub release](https://img.shields.io/github/release/Just-Some-Bots/MusicBot.svg?style=flat-square)](https://just-some-bots.github.io/MusicBot/)
[![Python](https://img.shields.io/badge/python-3.5%2C%203.6-blue.svg?style=flat-square)](https://www.python.org/downloads/)
[![Discord](https://discordapp.com/api/guilds/129489631539494912/widget.png?style=shield)](https://discord.gg/bots)

Just-Some-Bot의 [MusicBot](https://github.com/Just-Some-Bots/MusicBot)을 기반으로 한글화 및 일부 기능이 수정(반복 재생 기능 및 사용성)된 디스코드 뮤직봇입니다. [Python](https://www.python.org "Python homepage") 3.5+ 이상의 환경에서 작동하며, [discord.py](https://github.com/Rapptz/discord.py) 라이브러리를 이용합니다. 
유튜브와 트위치 등의 미디어 서비스에서 요청한 노래를 디스코드의 음성 채널을 통해 재생합니다. 재생 대기 목록이 비어있는 경우 자동 재생 목록의 노래를 랜덤 재생하는 기능을 제공하며, 유저 그룹별로 사용 권한을 제한할 수도 있습니다. 게다가, 트위치의 라이브 스트리밍을 음성 채널을 통해 재생할 수도 있습니다!(실험단계)

![Main](https://i.imgur.com/EZljY52.png)

## 설치
원본 [가이드](https://just-some-bots.github.io/MusicBot/)를 확인해주세요.

가이드의 지침대로 설치한 뒤 메인 설정파일인 `config/options.ini`을 구성주세요. `example_options.ini`형태로 저장되어 있는 파일을 `options.ini`로 복사하여 사용하세요. 출력 메시지의 한글화를 위해서는 `i18nFile` 항목에 `config/i18n/ko_kr.json`을 추가 해야합니다.

### 명령어

많은 명령어가 포함되어 있습니다. 가장 기본적인 명령어인 `!재생 <url or 검색어>` 명령어가 해당 영상을 다운로드 및 처리하여 음성 채널을 통해 재생합니다. 모든 명령어는 [여기를 확인하세요](https://just-some-bots.github.io/MusicBot/using/commands/ "명령어").

### 기타 링크

* [Support Discord server](https://discord.gg/bots)
* [프로젝트 라이센스](LICENSE)
