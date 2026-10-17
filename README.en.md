# FreeD TV Live Stream Source Configuration

A repository compiling various live stream source configurations for TV box applications.

## Project Overview

This project integrates live stream source configurations suitable for TVBox and FreeDTV, including source addresses and parsing configurations for multiple mainstream live streaming platforms.

## Directory Structure

```
freed/
├── TVBox/               # TVBox Configuration Files
│   ├── meow.json        # Main Configuration Source
│   ├── meow_uncensored.json
│   └── meowcf.json
│
└── tv/                  # FreeDTV Live Stream Sources
    ├── Bilibili.json    # Bilibili Live Stream Source
    ├── Bilibili.txt
    ├── douyu.json       # Douyu Live Stream Source
    ├── douyu.txt
    ├── huya.json        # Huya Live Stream Source
    ├── huya.txt
    ├── live.txt         # Live Channel List
    ├── public.json      # Public Sources
    ├── searchUrl.json   # Search URLs
    ├── searchUrl2.json
    ├── sourceNavigation.json
    ├── vipParse.json    # VIP Parsing Configuration
    └── webPlugNavigation.json
```

## Configuration Sources

### TVBox Configuration
- **meow.json** - Main Configuration Source
- **meow_uncensored.json** - Uncensored Version Configuration
- **meowcf.json** - CF Version Configuration

### Streaming Platform Support
- Bilibili
- Douyu Live
- Huya Live
- Public Live Stream Sources

## Usage Instructions

### TVBox Usage Method
1. Open the TVBox application
2. Configure the data source address
3. Switch the data source to start using

### FreeDTV Usage Method
1. Install the FreeDTV application
2. Import the corresponding configuration file
3. Start watching live streams

## Notes

- Some live stream sources may require VIP parsing
- Please comply with the terms of service of relevant live streaming platforms
- Update configurations regularly for the best experience

## License

This project is for learning and exchange purposes only; please do not use for commercial purposes.