# Go Language & Development
> Welcome to the world of Go. An ongoing curated list of frameworks, libraries, learning tutorials, best software development practices and resources in Go Language.


![go](https://github.com/veilair/go-development/blob/main/img/go-programming.png)

### Why Go?

Go is a really fast language. Because Go is compiled to machine code, it will naturally outperform languages that are interpreted or have virtual runtimes. Go programs also compile extremely fast, and the resulting binary is very small.

## Table of Contents

- [Go Development](#go-language--development)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Strings](#strings)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)
- [Other Useful Links](#other-useful-links)

[Back to top](#table-of-contents)



## Audio and Music

*Libraries for manipulating audio.*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - EasyMidi is a simple and reliable library for working with standard midi file (SMF).
* [flac](https://github.com/eaburns/flac) - No-frills native Go FLAC decoder that decodes FLAC files into byte slices.
* [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams. 
* [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [go-sox](https://github.com/krig/go-sox) - libsox bindings for go.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go. 
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. 
* [id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go. 
* [malgo](https://github.com/gen2brain/malgo) - Mini audio library. 
* [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
* [mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps. 
* [mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder. 
* [music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go. 
* [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. 
* [portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi. 
* [taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib. 
* [vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies). 
* [waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams. 

[Back to top](#table-of-contents)

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time. - :arrow_down:16 - :star:1426
* [branca](https://github.com/hako/branca) - Golang implementation of Branca Tokens. - :arrow_down:0 - :star:20
* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC. - :arrow_down:0 - :star:2445
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format. - :arrow_down:0 - :star:0
* [go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. - :arrow_down:284 - :star:536
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang. - :arrow_down:0 - :star:381
* [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. - :arrow_down:70 - :star:647
* [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. - :arrow_down:10 - :star:401
* [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. - :arrow_down:446 - :star:825
* [httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware. - :arrow_down:68 - :star:102
* [jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT). - :arrow_down:4 - :star:0
* [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library. - :arrow_down:0 - :star:1
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT). - :arrow_down:2878 - :star:1459
* [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam. - :arrow_down:0 - :star:589
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support. - :arrow_down:60 - :star:854
* [osin](https://github.com/openshift/osin) - Golang OAuth2 server library.
* [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO). - :arrow_down:1 - :star:116
* [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt. - :arrow_down:21 - :star:176
* [rbac](https://github.com/zpatrick/rbac) - Minimalistic RBAC package for Go applications. - :arrow_down:0 - :star:18
* [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding. - :arrow_down:0 - :star:17
* [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). - :arrow_down:7 - :star:6
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module. - :arrow_down:0 - :star:4
* [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. - :arrow_down:0 - :star:29
* [signedvalue](https://github.com/sashka/signedvalue) - Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`. - :arrow_down:0 - :star:5

[Back to top](#table-of-contents)

## Bot Building

*Libraries for building and working with bots.*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. - :arrow_down:103 - :star:122
* [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more. - :arrow_down:28 - :star:94
* [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware. - :arrow_down:1 - :star:71
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges. - :arrow_down:0 - :star:67
* [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library. - :arrow_down:0 - :star:15
* [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. - :arrow_down:3 - :star:5
* [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. - :arrow_down:6 - :star:35
* [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api. - :arrow_down:1 - :star:0
* [slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots. - :arrow_down:7 - :star:181
* [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http. - :arrow_down:5 - :star:2
* [telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go. - :arrow_down:78 - :star:229
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. - :arrow_down:38 - :star:304
* [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. - :arrow_down:0 - :star:160

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module. - :arrow_down:4 - :star:29
* [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. - :arrow_down:2 - :star:8
* [cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags. - :arrow_down:82 - :star:204
* [cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go. - :arrow_down:2 - :star:28
* [cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications. - :arrow_down:0 - :star:559
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command. - :arrow_down:7 - :star:98
* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. - :arrow_down:10018 - :star:2817
* [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. - :arrow_down:2 - :star:57
* [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. - :arrow_down:27 - :star:456
* [docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile. - :arrow_down:64 - :star:723
* [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. - :arrow_down:5 - :star:18
* [flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand. - :arrow_down:2 - :star:2
* [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support. - :arrow_down:0 - :star:8
* [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package. - :arrow_down:0 - :star:23
* [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. - :arrow_down:111 - :star:370
* [go-commander](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow. - :arrow_down:0 - :star:3
* [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. - :arrow_down:1863 - :star:623
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired on the flexibility of Perl’s GetOpt::Long. - :arrow_down:11 - :star:2
* [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications. - :arrow_down:0 - :star:15
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
* [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands. - :arrow_down:249 - :star:732
* [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. - :arrow_down:522 - :star:325
* [mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces. - :arrow_down:2589 - :star:460
* [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. - :arrow_down:207 - :star:367
* [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. - :arrow_down:8473 - :star:107
* [readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license. - :arrow_down:252 - :star:634
* [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
* [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries. - :arrow_down:4 - :star:52
* [strumt](https://github.com/antham/strumt) - Library to create prompt chain. - :arrow_down:3 - :star:19
* [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. - :arrow_down:2 - :star:69
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). - :arrow_down:2725 - :star:4621
* [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. - :arrow_down:5 - :star:5
* [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices. - :arrow_down:2 - :star:7

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. - :arrow_down:2 - :star:942
* [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf. - :arrow_down:33 - :star:199
* [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes. - :arrow_down:1 - :star:39
* [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. - :arrow_down:164 - :star:169
* [color](https://github.com/fatih/color) - Versatile package for colored terminal output. - :arrow_down:2775 - :star:1081
* [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. - :arrow_down:2 - :star:8
* [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method. - :arrow_down:0 - :star:4
* [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. - :arrow_down:0 - :star:5
* [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. - :arrow_down:999 - :star:136
* [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. - :arrow_down:363 - :star:148
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. - :arrow_down:696 - :star:80
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). - :arrow_down:34 - :star:1560
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. - :arrow_down:182 - :star:777
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. - :arrow_down:11 - :star:44
* [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. - :arrow_down:10 - :star:219
* [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS. - :arrow_down:7 - :star:282
* [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in terminal with Go. - :arrow_down:2 - :star:92
* [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API. - :arrow_down:1 - :star:11
* [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. - :arrow_down:1163 - :star:1603
* [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). - :arrow_down:4 - :star:15
* [termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output. - :arrow_down:33 - :star:64
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). - :arrow_down:299 - :star:5091
* [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime. - :arrow_down:49 - :star:465
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. - :arrow_down:82 - :star:831
* [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. - :arrow_down:124 - :star:347

## Configuration

*Libraries for configuration parsing.*

* [config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing. - :arrow_down:84 - :star:81
* [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. - :arrow_down:22 - :star:20
* [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct. - :arrow_down:1 - :star:44
* [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). - :arrow_down:88 - :star:162
* [envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs. - :arrow_down:1 - :star:79
* [envconf](https://github.com/ian-kent/envconf) - Configuration from environment. - :arrow_down:13 - :star:3
* [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. - :arrow_down:19 - :star:93
* [envh](https://github.com/antham/envh) - Helpers to manage environment variables. - :arrow_down:6 - :star:85
* [gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic. - :arrow_down:1 - :star:13
* [goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file. - :arrow_down:3 - :star:70
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). - :arrow_down:675 - :star:348
* [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. - :arrow_down:14 - :star:36
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. - :arrow_down:5 - :star:25
* [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. - :arrow_down:11 - :star:51
* [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. - :arrow_down:8 - :star:10
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files. - :arrow_down:379 - :star:370
* [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. - :arrow_down:0 - :star:192
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables. - :arrow_down:540 - :star:479
* [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. - :arrow_down:0 - :star:8
* [sprbox](https://github.com/oblq/sprbox) - Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars). - :arrow_down:1 - :star:3
* [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. - :arrow_down:1 - :star:202
* [viper](https://github.com/spf13/viper) - Go configuration with fangs. - :arrow_down:6478 - :star:1947
* [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html). - :arrow_down:2 - :star:5

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* [duci](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages. - :arrow_down:0 - :star:16
* [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace. - :arrow_down:0 - :star:4
* [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. - :arrow_down:0 - :star:285
* [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. - :arrow_down:0 - :star:27
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. - :arrow_down:0 - :star:0

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. - :arrow_down:20 - :star:356
* [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. - :arrow_down:34 - :star:36

## Data Structures

*Generic datastructures and algorithms in Go.*
* [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
* [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. - :arrow_down:1 - :star:24
* [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. - :arrow_down:0 - :star:20
* [bitset](https://github.com/willf/bitset) - Go package implementing bitsets. - :arrow_down:190 - :star:210
* [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. - :arrow_down:11 - :star:87
* [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. - :arrow_down:0 - :star:5
* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. - :arrow_down:25 - :star:736
* [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library. - :arrow_down:0 - :star:32
* [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). - :arrow_down:2 - :star:23
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. - :arrow_down:9 - :star:186
* [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
* [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue). - :arrow_down:0 - :star:8
* [encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go. - :arrow_down:0 - :star:46
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. - :arrow_down:5 - :star:10
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. - :arrow_down:0 - :star:2716
* [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding. - :arrow_down:0 - :star:5
* [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. - :arrow_down:9 - :star:201
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches. - :arrow_down:0 - :star:8
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. - :arrow_down:0 - :star:0
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. - :arrow_down:263 - :star:419
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. - :arrow_down:0 - :star:6
* [goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. - :arrow_down:3 - :star:35
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. - :arrow_down:6 - :star:585
* [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. - :arrow_down:13 - :star:0
* [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. - :arrow_down:4 - :star:5
* [mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing. - :arrow_down:16 - :star:214
* [merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures. - :arrow_down:1 - :star:61
* [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
* [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
* [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out. - :arrow_down:1 - :star:5
* [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.
* [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. - :arrow_down:59 - :star:154
* [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap. - :arrow_down:0 - :star:5
* [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation. - :arrow_down:0 - :star:67
* [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. - :arrow_down:0 - :star:30
* [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
* [trie](https://github.com/derekparker/trie) - Trie implementation in Go. - :arrow_down:4 - :star:142
* [ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang. - :arrow_down:3 - :star:31
* [willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters. - :arrow_down:86 - :star:251

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go. - :arrow_down:137 - :star:3792
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. - :arrow_down:36 - :star:774
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go. - :arrow_down:3599 - :star:4737
* [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. - :arrow_down:48 - :star:1048
* [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. - :arrow_down:25 - :star:110
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. - :arrow_down:0 - :star:7668
* [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. - :arrow_down:0 - :star:15
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. - :arrow_down:144 - :star:386
* [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
* [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. - :arrow_down:43 - :star:115
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications. - :arrow_down:212 - :star:620
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go. - :arrow_down:0 - :star:4
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. - :arrow_down:120 - :star:4747
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics. - :arrow_down:698 - :star:8728
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. - :arrow_down:166 - :star:276
* [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. - :arrow_down:25 - :star:30
* [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.
* [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. - :arrow_down:0 - :star:2
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [pudge](https://github.com/recoilme/pudge) - Fast and simple  key/value store written using Go's standard library.
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. - :arrow_down:0 - :star:1870
* [Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store. - :arrow_down:17 - :star:23
* [slowpoke](https://github.com/recoilme/slowpoke) - Key-value store with persistence. - :arrow_down:6 - :star:34
* [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. - :arrow_down:0 - :star:10
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. - :arrow_down:141 - :star:4651
* [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. - :arrow_down:0 - :star:1609
* [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. - :arrow_down:0 - :star:76

*Database schema migration.*

* [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. - :arrow_down:6 - :star:24
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. - :arrow_down:20 - :star:1
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
* [goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. - :arrow_down:1 - :star:17
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. - :arrow_down:2 - :star:9
* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library. - :arrow_down:15 - :star:198
* [pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc. - :arrow_down:0 - :star:12
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. - :arrow_down:273 - :star:497

*Database tools.*

* [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database. - :arrow_down:0 - :star:123
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small insterts and sends big requests to ClickHouse servers. - :arrow_down:0 - :star:66
* [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication. - :arrow_down:0 - :star:58
* [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. - :arrow_down:0 - :star:3630
* [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code. - :arrow_down:0 - :star:19
* [pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database. - :arrow_down:0 - :star:1684
* [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup. - :arrow_down:0 - :star:8
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. - :arrow_down:0 - :star:3923

*SQL query builder, libraries for building and using SQL.*

* [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease. - :arrow_down:12 - :star:237
* [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
* [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. - :arrow_down:0 - :star:43
* [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. - :arrow_down:10 - :star:266
* [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. - :arrow_down:4 - :star:53
* [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases. - :arrow_down:0 - :star:0
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. - :arrow_down:13 - :star:108
* [scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs. - :arrow_down:0 - :star:79
* [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. - :arrow_down:9 - :star:45
* [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. - :arrow_down:166 - :star:904
* [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. - :arrow_down:0 - :star:723

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql. - :arrow_down:2 - :star:13
    * [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. - :arrow_down:1 - :star:0
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. - :arrow_down:7 - :star:46
    * [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql. - :arrow_down:71 - :star:40
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. - :arrow_down:332 - :star:395
    * [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql. - :arrow_down:78 - :star:157
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. - :arrow_down:6830 - :star:2669
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql. - :arrow_down:3953 - :star:1408
    * [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org). - :arrow_down:1 - :star:39
    * [goracle](https://github.com/go-goracle/goracle) - Oracle driver for Go, using the ODPI-C driver. - :arrow_down:1 - :star:18
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. - :arrow_down:302 - :star:684
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. - :arrow_down:5873 - :star:2324

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. - :arrow_down:303 - :star:182
    * [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. - :arrow_down:6 - :star:34
    * [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. - :arrow_down:1 - :star:1
    * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB. - :arrow_down:1 - :star:18
    * [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. - :arrow_down:11 - :star:22
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. - :arrow_down:296 - :star:217
    * [go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go. - :arrow_down:18 - :star:35
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa. - :arrow_down:6 - :star:20
    * [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. - :arrow_down:1 - :star:42
    * [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. - :arrow_down:43 - :star:183
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. - :arrow_down:0 - :star:3
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. - :arrow_down:415 - :star:1024
    * [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. - :arrow_down:2 - :star:1
    * [mgo](https://github.com/globalsign/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. - :arrow_down:163 - :star:726
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
    * [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. - :arrow_down:0 - :star:15
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang. - :arrow_down:4 - :star:63
    * [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. - :arrow_down:113 - :star:271
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang. - :arrow_down:377 - :star:1105
    * [redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. - :arrow_down:11 - :star:107
    * [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. - :arrow_down:2 - :star:7

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. - :arrow_down:646 - :star:2796
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. - :arrow_down:161 - :star:827
    * [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. - :arrow_down:1 - :star:15
    * [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. - :arrow_down:1 - :star:799
    * [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch. - :arrow_down:1 - :star:4
    * [riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine. - :arrow_down:17 - :star:3565
    * [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - Golang Cache component for multiple drivers. - :arrow_down:0 - :star:10
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends. - :arrow_down:21 - :star:8622
    * [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. - :arrow_down:5 - :star:1
    * [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more)

## Date and Time

*Libraries for working with dates and times.*

* [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. - :arrow_down:6 - :star:45
* [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. - :arrow_down:3 - :star:3
* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. - :arrow_down:45 - :star:8
* [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go. - :arrow_down:16 - :star:124
* [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... - :arrow_down:2 - :star:1
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). - :arrow_down:0 - :star:47
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location. - :arrow_down:0 - :star:4
* [goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang. - :arrow_down:3 - :star:7
* [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex. - :arrow_down:0 - :star:4
* [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. - :arrow_down:135 - :star:701
* [NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`. - :arrow_down:0 - :star:1
* [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter. - :arrow_down:0 - :star:1
* [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration. - :arrow_down:1 - :star:35
* [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. - :arrow_down:8 - :star:110
* [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. - :arrow_down:1 - :star:5

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads. - :arrow_down:1 - :star:103
* [digota](https://github.com/digota/digota) - grpc ecommerce microservice. - :arrow_down:0 - :star:213
* [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
* [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. - :arrow_down:11 - :star:14
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
* [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
* [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. - :arrow_down:0 - :star:1184
* [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package. - :arrow_down:5 - :star:19
* [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. - :arrow_down:0 - :star:54
* [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. - :arrow_down:0 - :star:1210
* [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service. - :arrow_down:3 - :star:189
* [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. - :arrow_down:19 - :star:84
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. - :arrow_down:22 - :star:275
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. - :arrow_down:0 - :star:2391
* [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. - :arrow_down:0 - :star:22
* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system. - :arrow_down:0 - :star:4908
* [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. - :arrow_down:0 - :star:9
* [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. - :arrow_down:2 - :star:1
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform. - :arrow_down:0 - :star:2352
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems. - :arrow_down:0 - :star:2327
* [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
* [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
* [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. - :arrow_down:682 - :star:759
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [redis-lock](https://github.com/bsm/redis-lock) - Simplified distributed locking implementation using Redis. - :arrow_down:6 - :star:4
* [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. - :arrow_down:28 - :star:179
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. - :arrow_down:18 - :star:268
* [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). - :arrow_down:0 - :star:188
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. - :arrow_down:106 - :star:1325
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. - :arrow_down:0 - :star:203

## Email

*Libraries and tools that implement email creation and sending.*

* [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
* [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. - :arrow_down:0 - :star:64
* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. - :arrow_down:127 - :star:701
* [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. - :arrow_down:9 - :star:20
* [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. - :arrow_down:66 - :star:122
* [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. - :arrow_down:13 - :star:48
* [Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails.
* [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. - :arrow_down:0 - :star:72
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. - :arrow_down:13 - :star:1262
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. - :arrow_down:0 - :star:1198
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. - :arrow_down:157 - :star:211
* [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. - :arrow_down:14 - :star:25

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go. - :arrow_down:0 - :star:241
* [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). - :arrow_down:0 - :star:12
* [expr](https://github.com/antonmedv/expr) - an engine that can evaluate expressions. - :arrow_down:1 - :star:239
* [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. - :arrow_down:0 - :star:333
* [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. - :arrow_down:14 - :star:390
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. - :arrow_down:65 - :star:737
* [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. - :arrow_down:0 - :star:186
* [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. - :arrow_down:36 - :star:411
* [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. - :arrow_down:377 - :star:1317
* [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go. - :arrow_down:1 - :star:2
* [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go. - :arrow_down:1015 - :star:2409
* [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. - :arrow_down:0 - :star:13
* [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.

## Error Handling

*Libraries for handling errors.*

* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives. - :arrow_down:15775 - :star:1032
* [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
* [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. - :arrow_down:2643 - :star:205
* [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.
* [werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called. - :arrow_down:0 - :star:5

## Files

*Libraries for  handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. - :arrow_down:1689 - :star:703
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. - :arrow_down:3 - :star:23
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
* [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. - :arrow_down:0 - :star:5
* [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. - :arrow_down:77 - :star:178
* [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - PDF processor.
* [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. - :arrow_down:1 - :star:28
* [tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files. - :arrow_down:0 - :star:19
* [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

## Financial

*Packages for accounting and finance.*

* [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. - :arrow_down:11 - :star:221
* [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. - :arrow_down:1310 - :star:321
* [go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go. - :arrow_down:4 - :star:359
* [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
* [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. - :arrow_down:1 - :star:513
* [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). - :arrow_down:1 - :star:40
* [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
* [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies. - :arrow_down:2 - :star:42
* [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode. - :arrow_down:0 - :star:20
* [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. - :arrow_down:0 - :star:28

## Forms

*Libraries for working with forms.*

* [bind](https://github.com/robfig/bind) - Bind form data to any Go values. - :arrow_down:0 - :star:14
* [binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct. - :arrow_down:102 - :star:510
* [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. - :arrow_down:7 - :star:34
* [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. - :arrow_down:18 - :star:132
* [formam](https://github.com/monoculum/formam) - decode form's values into a struct. - :arrow_down:38 - :star:63
* [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. - :arrow_down:9 - :star:63
* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. - :arrow_down:124 - :star:136
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. - :arrow_down:126 - :star:667

## Functional

*Packages to support functional programming in Go.*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang. - :arrow_down:0 - :star:64
* [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go.
* [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities. - :arrow_down:1 - :star:866

## Game Development

*Awesome game development libraries.*

* [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.
* [Ebiten](https://github.com/hajimehoshi/ebiten) - dead simple 2D game library in Go. - :arrow_down:188 - :star:151
* [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. - :arrow_down:0 - :star:290
* [g3n](https://github.com/g3n/engine) - Go 3D Game Engine.
* [GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL. - :arrow_down:0 - :star:238
* [glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
* [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. - :arrow_down:8 - :star:156
* [go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format. - :arrow_down:15 - :star:9
* [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. - :arrow_down:0 - :star:112
* [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping. - :arrow_down:0 - :star:637
* [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. - :arrow_down:5 - :star:787
* [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
* [Oak](https://github.com/oakmound/oak) - Pure Go game engine. - :arrow_down:13 - :star:481
* [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. - :arrow_down:1 - :star:16
* [Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go. - :arrow_down:82 - :star:1367
* [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. - :arrow_down:25 - :star:658

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations. - :arrow_down:0 - :star:15
* [gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality. - :arrow_down:0 - :star:731
* [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. - :arrow_down:0 - :star:46
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. - :arrow_down:32 - :star:828
* [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types. - :arrow_down:0 - :star:573
* [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package. - :arrow_down:0 - :star:12
* [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
* [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. - :arrow_down:2 - :star:78
* [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. - :arrow_down:0 - :star:707
* [pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection. - :arrow_down:0 - :star:39

## Geographic

*Geographic tools and servers*

* [geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications. - :arrow_down:0 - :star:47
* [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. - :arrow_down:0 - :star:6
* [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
* [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs. - :arrow_down:15 - :star:9
* [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder. - :arrow_down:0 - :star:6
* [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go.
* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.

## Go Compilers

*Tools for compiling Go to other languages.*

* [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code. - :arrow_down:0 - :star:9
* [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code. - :arrow_down:0 - :star:9
* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. - :arrow_down:0 - :star:4209
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. - :arrow_down:0 - :star:316

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang. - :arrow_down:1 - :star:1052
* [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
* [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
* [breaker](https://github.com/kamilsk/breaker) - 🚧 Flexible mechanism to make your code breakable.
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang. - :arrow_down:0 - :star:12
* [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. - :arrow_down:0 - :star:140
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. - :arrow_down:1 - :star:2
* [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang. - :arrow_down:0 - :star:4
* [GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library. - :arrow_down:0 - :star:25
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. - :arrow_down:21 - :star:1484
* [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
* [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. - :arrow_down:6 - :star:123
* [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel. - :arrow_down:0 - :star:15
* [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. - :arrow_down:0 - :star:220
* [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. - :arrow_down:1 - :star:0
* [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). - :arrow_down:4 - :star:32
* [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. - :arrow_down:0 - :star:5
* [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation. - :arrow_down:1 - :star:4
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. - :arrow_down:2 - :star:379
* [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool. - :arrow_down:1 - :star:11
* [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. - :arrow_down:0 - :star:1

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. - :arrow_down:12 - :star:1
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows. - :arrow_down:6 - :star:269
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron). - :arrow_down:42 - :star:1643
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. - :arrow_down:6 - :star:1002
* [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. - :arrow_down:3 - :star:114
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). - :arrow_down:31 - :star:179
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. - :arrow_down:74 - :star:3288
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go. - :arrow_down:457 - :star:3116
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). - :arrow_down:16 - :star:1965

*Interaction*

* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. - :arrow_down:37 - :star:310
* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. - :arrow_down:31 - :star:255
* [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. - :arrow_down:28 - :star:107
* [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. - :arrow_down:2 - :star:66


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. - :arrow_down:4 - :star:185
* [cameron](https://github.com/aofei/cameron) - An avatar generator for Go.
* [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. - :arrow_down:12 - :star:867
* [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. - :arrow_down:121 - :star:665
* [gift](https://github.com/disintegration/gift) - Package of image processing filters. - :arrow_down:102 - :star:813
* [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. - :arrow_down:33 - :star:54
* [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. - :arrow_down:11 - :star:39
* [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. - :arrow_down:6 - :star:188
* [go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV. - :arrow_down:0 - :star:443
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. - :arrow_down:9 - :star:18
* [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package. - :arrow_down:1 - :star:93
* [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars. - :arrow_down:3 - :star:10
* [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
* [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. - :arrow_down:0 - :star:820
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. - :arrow_down:494 - :star:875
* [img](https://github.com/hawx/img) - Selection of image manipulation tools. - :arrow_down:0 - :star:80
* [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
* [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
* [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. - :arrow_down:1 - :star:3
* [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. - :arrow_down:0 - :star:518
* [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. - :arrow_down:0 - :star:952
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods. - :arrow_down:956 - :star:1150
* [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. - :arrow_down:16 - :star:119
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. - :arrow_down:15 - :star:304
* [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography. - :arrow_down:1 - :star:10
* [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
* [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. - :arrow_down:393 - :star:766
* [tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder. - :arrow_down:4 - :star:13

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. - :arrow_down:70 - :star:383
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go. - :arrow_down:0 - :star:7
* [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
* [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
* [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Job Scheduler

*Libraries for scheduling jobs.*

* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax. - :arrow_down:0 - :star:44
* [clockwork](https://github.com/whiteShtef/clockwork) - Simple and intuitive job scheduling library in Go. - :arrow_down:1 - :star:32
* [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. - :arrow_down:4 - :star:123
* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. - :arrow_down:7 - :star:442
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. - :arrow_down:21 - :star:296
* [jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library. - :arrow_down:9 - :star:353
* [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
* [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. - :arrow_down:26 - :star:103

## JSON

*Libraries for working with JSON.*

* [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code. - :arrow_down:184 - :star:665
* [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses. - :arrow_down:0 - :star:8
* [gojq](https://github.com/elgs/gojq) - JSON query in Golang. - :arrow_down:18 - :star:44
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON. - :arrow_down:18 - :star:1132
* [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go. - :arrow_down:0 - :star:12
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference. - :arrow_down:0 - :star:0
* [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. - :arrow_down:0 - :star:29
* [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. - :arrow_down:0 - :star:51
* [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses. - :arrow_down:17 - :star:1
* [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON. - :arrow_down:0 - :star:14

## Logging

*Libraries for generating and working with log files.*

* [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels). - :arrow_down:12 - :star:0
* [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. - :arrow_down:36 - :star:13
* [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
* [glog](https://github.com/golang/glog) - Leveled execution logs for Go. - :arrow_down:55481 - :star:1073
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. - :arrow_down:0 - :star:9
* [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers. - :arrow_down:3 - :star:4
* [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. - :arrow_down:0 - :star:19
* [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. - :arrow_down:17 - :star:159
* [gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch. - :arrow_down:0 - :star:20
* [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. - :arrow_down:12 - :star:2
* [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging. - :arrow_down:1 - :star:5
* [log](https://github.com/apex/log) - Structured logging package for Go. - :arrow_down:971 - :star:303
* [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. - :arrow_down:93 - :star:193
* [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation. - :arrow_down:3 - :star:17
* [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. - :arrow_down:0 - :star:61
* [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. - :arrow_down:347 - :star:506
* [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. - :arrow_down:0 - :star:5
* [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. - :arrow_down:26 - :star:26
* [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. - :arrow_down:30 - :star:68
* [logmatic](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
* [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. - :arrow_down:3 - :star:2
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. - :arrow_down:50167 - :star:3335
* [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). - :arrow_down:15 - :star:13
* [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. - :arrow_down:805 - :star:139
* [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. - :arrow_down:14 - :star:219
* [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. - :arrow_down:40 - :star:343
* [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. - :arrow_down:9 - :star:5
* [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation. - :arrow_down:3 - :star:292
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). - :arrow_down:1 - :star:59
* [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. - :arrow_down:1487 - :star:732
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. - :arrow_down:94 - :star:37
* [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. - :arrow_down:204 - :star:595
* [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. - :arrow_down:4 - :star:0
* [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. - :arrow_down:63 - :star:92
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. - :arrow_down:258 - :star:1149
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. - :arrow_down:136 - :star:1121

## Machine Learning

*Libraries for Machine Learning.*

* [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. - :arrow_down:35 - :star:367
* [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. - :arrow_down:53 - :star:388
* [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library. - :arrow_down:0 - :star:568
* [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library. - :arrow_down:0 - :star:3
* [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go. - :arrow_down:0 - :star:14
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go. - :arrow_down:2 - :star:171
* [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. - :arrow_down:7 - :star:75
* [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. - :arrow_down:15 - :star:130
* [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. - :arrow_down:0 - :star:42
* [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. - :arrow_down:4 - :star:115
* [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. - :arrow_down:0 - :star:11
* [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. - :arrow_down:2 - :star:43
* [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. - :arrow_down:0 - :star:3201
* [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. - :arrow_down:5 - :star:28
* [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go. - :arrow_down:0 - :star:0
* [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. - :arrow_down:3 - :star:679
* [gorse](https://github.com/zhenghaoz/gorse) - A High Performance Recommender System Package based on Collaborative Filtering for Go.
* [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML. - :arrow_down:0 - :star:13
* [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. - :arrow_down:13 - :star:196
* [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. - :arrow_down:0 - :star:43
* [mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go. - :arrow_down:1 - :star:1
* [neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT). - :arrow_down:0 - :star:39
* [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. - :arrow_down:0 - :star:2
* [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. - :arrow_down:6 - :star:122
* [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. - :arrow_down:1 - :star:83
* [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. - :arrow_down:2 - :star:848
* [Varis](https://github.com/Xamber/Varis) - Golang Neural Network. - :arrow_down:0 - :star:10

## Messaging

*Libraries that implement messaging systems.*

* [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. - :arrow_down:63 - :star:1281
* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. - :arrow_down:0 - :star:1222
* [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. - :arrow_down:1045 - :star:99
* [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. - :arrow_down:0 - :star:48
* [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. - :arrow_down:4 - :star:73
* [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. - :arrow_down:1 - :star:12
* [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. - :arrow_down:28 - :star:168
* [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. - :arrow_down:0 - :star:6
* [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). - :arrow_down:18 - :star:186
* [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. - :arrow_down:7 - :star:13
* [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. - :arrow_down:513 - :star:642
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. - :arrow_down:237 - :star:1397
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. - :arrow_down:0 - :star:0
* [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. - :arrow_down:0 - :star:468
* [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. - :arrow_down:7 - :star:296
* [goose](https://github.com/ian-kent/goose) - Server Sent Events in Go. - :arrow_down:6 - :star:23
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). - :arrow_down:0 - :star:277
* [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. - :arrow_down:0 - :star:34
* [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. - :arrow_down:5 - :star:4
* [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. - :arrow_down:0 - :star:701
* [mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability. - :arrow_down:191 - :star:942
* [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. - :arrow_down:34 - :star:478
* [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
* [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. - :arrow_down:4 - :star:15
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library. - :arrow_down:447 - :star:934
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. - :arrow_down:0 - :star:30
* [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. - :arrow_down:0 - :star:74
* [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go. - :arrow_down:17 - :star:106
* [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues. - :arrow_down:0 - :star:39
* [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. - :arrow_down:1310 - :star:1282
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. - :arrow_down:0 - :star:862
* [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). - :arrow_down:433 - :star:415

## Microsoft Office

### Microsoft Excel
*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files. - :arrow_down:18 - :star:2098
* [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table. - :arrow_down:0 - :star:27
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. - :arrow_down:0 - :star:9
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. - :arrow_down:264 - :star:1261
* [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs. - :arrow_down:0 - :star:10

## Miscellaneous

### Dependency Injection
*Libraries for working with dependency injection.*

* [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. - :arrow_down:0 - :star:16
* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go. - :arrow_down:0 - :star:241
* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig). - :arrow_down:0 - :star:282
* [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang. - :arrow_down:0 - :star:10

### Strings
*Libraries for working with strings.*
* [strutil](https://github.com/ozgio/strutil) - String utilities.
* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. - :arrow_down:37 - :star:342

*These libraries were placed here because none of the other categories seemed to fit.*

* [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. - :arrow_down:0 - :star:3
* [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework. - :arrow_down:1 - :star:81
* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. - :arrow_down:189 - :star:135
* [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. - :arrow_down:32 - :star:11
* [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. - :arrow_down:0 - :star:5
* [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. - :arrow_down:13 - :star:95
* [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. - :arrow_down:0 - :star:338
* [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. - :arrow_down:6 - :star:63
* [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. - :arrow_down:9 - :star:6
* [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/). - :arrow_down:0 - :star:17
* [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation. - :arrow_down:0 - :star:17
* [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. - :arrow_down:4 - :star:251
* [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. - :arrow_down:10 - :star:12
* [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans. - :arrow_down:0 - :star:77
* [ghorg](https://github.com/gabrie30/ghorg) - Clone all repos from a GitHub org into a single directory. - :arrow_down:0 - :star:16
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. - :arrow_down:4 - :star:287
* [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. - :arrow_down:2 - :star:2
* [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. - :arrow_down:2 - :star:10
* [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns. - :arrow_down:0 - :star:48
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). - :arrow_down:5 - :star:1245
* [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method. - :arrow_down:0 - :star:11
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. - :arrow_down:9 - :star:955
* [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. - :arrow_down:8 - :star:103
* [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. - :arrow_down:11 - :star:193
* [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services. - :arrow_down:1 - :star:40
* [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list. - :arrow_down:0 - :star:3
* [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. - :arrow_down:1 - :star:1
* [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang. - :arrow_down:1 - :star:0
* [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
* [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
* [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests. - :arrow_down:0 - :star:0
* [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go. - :arrow_down:0 - :star:9
* [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
* [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. - :arrow_down:0 - :star:1
* [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. - :arrow_down:4 - :star:263
* [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... - :arrow_down:0 - :star:36
* [turtle](https://github.com/hackebrot/turtle) - Emojis for Go. - :arrow_down:1 - :star:42
* [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support. - :arrow_down:0 - :star:10
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
* [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go. - :arrow_down:0 - :star:2
* [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. - :arrow_down:0 - :star:17

## Natural Language Processing

*Libraries for working with human languages.*

* [getlang](https://github.com/rylans/getlang) - Fast natural language detection package. - :arrow_down:0 - :star:11
* [go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. - :arrow_down:1 - :star:2
* [go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter. - :arrow_down:23 - :star:180
* [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. - :arrow_down:18 - :star:39
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. - :arrow_down:5 - :star:5
* [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. - :arrow_down:1 - :star:12
* [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. - :arrow_down:22 - :star:113
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. - :arrow_down:0 - :star:11
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
* [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. - :arrow_down:12 - :star:392
* [icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1. - :arrow_down:1 - :star:13
* [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
* [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. - :arrow_down:1 - :star:8
* [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. - :arrow_down:0 - :star:50
* [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. - :arrow_down:0 - :star:338
* [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). - :arrow_down:0 - :star:132
* [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. - :arrow_down:7 - :star:15
* [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case. - :arrow_down:0 - :star:11
* [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. - :arrow_down:2 - :star:2
* [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. - :arrow_down:7 - :star:26
* [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. - :arrow_down:0 - :star:578
* [RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/) - :arrow_down:17 - :star:18
* [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences. - :arrow_down:3 - :star:145
* [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. - :arrow_down:0 - :star:6
* [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). - :arrow_down:1 - :star:14
* [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. - :arrow_down:4 - :star:31
* [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. - :arrow_down:6 - :star:41
* [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). - :arrow_down:2 - :star:277
* [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. - :arrow_down:7 - :star:853

## Networking

*Libraries for working with various layers of the network.*

* [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. - :arrow_down:14 - :star:49
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). - :arrow_down:18 - :star:38
* [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go. - :arrow_down:1 - :star:273
* [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. - :arrow_down:19 - :star:15
* [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. - :arrow_down:1 - :star:36
* [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. - :arrow_down:26 - :star:15
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. - :arrow_down:840 - :star:3116
* [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
* [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959). - :arrow_down:64 - :star:143
* [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
* [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols. - :arrow_down:0 - :star:49
* [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. - :arrow_down:412 - :star:277
* [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). - :arrow_down:0 - :star:97
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data. - :arrow_down:0 - :star:4
* [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. - :arrow_down:1114 - :star:747
* [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. - :arrow_down:110 - :star:226
* [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. - :arrow_down:3 - :star:1
* [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. - :arrow_down:120 - :star:121
* [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. - :arrow_down:46 - :star:201
* [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. - :arrow_down:28 - :star:56
* [graval](https://github.com/koofr/graval) - Experimental FTP server framework. - :arrow_down:10 - :star:13
* [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses. - :arrow_down:3 - :star:3040
* [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. - :arrow_down:0 - :star:1
* [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. - :arrow_down:90 - :star:231
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. - :arrow_down:1 - :star:232
* [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. - :arrow_down:6 - :star:17
* [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. - :arrow_down:0 - :star:1
* [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. - :arrow_down:33 - :star:271
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
* [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. - :arrow_down:4 - :star:2
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast. - :arrow_down:2 - :star:290
* [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). - :arrow_down:0 - :star:14
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go. - :arrow_down:36 - :star:395
* [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. - :arrow_down:23 - :star:34
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt. - :arrow_down:342 - :star:285
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). - :arrow_down:16 - :star:125
* [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. - :arrow_down:0 - :star:67
* [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. - :arrow_down:9 - :star:54
* [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
* [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. - :arrow_down:44 - :star:58
* [water](https://github.com/songgao/water) - Simple TUN/TAP library. - :arrow_down:34 - :star:156
* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API. - :arrow_down:0 - :star:873
* [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. - :arrow_down:29 - :star:90
* [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol. - :arrow_down:2 - :star:40

### HTTP Clients

*Libraries for making HTTP requests.*

* [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. - :arrow_down:1 - :star:303
* [goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest. - :arrow_down:1 - :star:25
* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library. - :arrow_down:68 - :star:750
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities. - :arrow_down:4 - :star:495
* [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. - :arrow_down:65 - :star:85
* [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client. - :arrow_down:1 - :star:15
* [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests. - :arrow_down:187 - :star:370

## OpenGL

*Libraries for using OpenGL in Go.*

* [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). - :arrow_down:80 - :star:69
* [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. - :arrow_down:65 - :star:29
* [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance. - :arrow_down:58 - :star:495
* [go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM. - :arrow_down:0 - :star:48
* [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database. - :arrow_down:4 - :star:47
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. - :arrow_down:3046 - :star:4358
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. - :arrow_down:326 - :star:2211
* [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). - :arrow_down:6 - :star:10
* [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. - :arrow_down:0 - :star:3
* [Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.
* [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. - :arrow_down:71 - :star:236
* [QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM. - :arrow_down:76 - :star:417
* [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. - :arrow_down:0 - :star:384
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. - :arrow_down:0 - :star:1220
* [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. - :arrow_down:0 - :star:474
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go. - :arrow_down:1425 - :star:1369
* [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. - :arrow_down:19 - :star:142

## Package Management

*Official tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool. - :arrow_down:13 - :star:9154
* [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

* [gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes. - :arrow_down:0 - :star:187
* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. - :arrow_down:0 - :star:2701
* [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. - :arrow_down:0 - :star:3930
* [gom](https://github.com/mattn/gom) - Go Manager - bundle for go. - :arrow_down:0 - :star:1152
* [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler. - :arrow_down:0 - :star:765
* [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH. - :arrow_down:0 - :star:40
* [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. - :arrow_down:0 - :star:1140
* [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. - :arrow_down:0 - :star:1081
* [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
* [nut](https://github.com/jingweno/nut) - Vendor Go dependencies. - :arrow_down:0 - :star:244
* [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. - :arrow_down:0 - :star:89

## Query Language

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data. - :arrow_down:0 - :star:472
* [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. - :arrow_down:27 - :star:39
* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. - :arrow_down:36 - :star:90
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. - :arrow_down:270 - :star:549
* [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. - :arrow_down:2 - :star:63
* [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters. - :arrow_down:1 - :star:11
* [rql](https://github.com/a8m/rql) - Resource Query Language for REST API. - :arrow_down:4 - :star:78

## Resource Embedding

* [esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them. - :arrow_down:0 - :star:153
* [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. - :arrow_down:0 - :star:81
* [go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable. - :arrow_down:0 - :star:3
* [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. - :arrow_down:3 - :star:107
* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy. - :arrow_down:545 - :star:788
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. - :arrow_down:189 - :star:957
* [statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks. - :arrow_down:0 - :star:34
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. - :arrow_down:0 - :star:326
* [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. - :arrow_down:0 - :star:1
* [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. - :arrow_down:11 - :star:97

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. - :arrow_down:98 - :star:353
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for Go for machine-learning and statistics (similar to pandas).
* [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. - :arrow_down:2 - :star:24
* [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. - :arrow_down:74 - :star:159
* [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. - :arrow_down:100 - :star:32
* [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. - :arrow_down:0 - :star:1
* [gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language. - :arrow_down:0 - :star:3
* [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
* [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. - :arrow_down:18 - :star:78
* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. - :arrow_down:209 - :star:343
* [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization). - :arrow_down:7 - :star:246
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. - :arrow_down:0 - :star:6
* [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. - :arrow_down:1 - :star:139
* [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. - :arrow_down:1 - :star:1
* [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. - :arrow_down:35 - :star:0
* [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. - :arrow_down:3 - :star:17
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
* [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. - :arrow_down:1 - :star:3
* [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
* [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. - :arrow_down:5 - :star:31
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. - :arrow_down:165 - :star:626
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. - :arrow_down:0 - :star:9
* [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
* [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison. - :arrow_down:0 - :star:59
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
* [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. - :arrow_down:2 - :star:178
* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras. - :arrow_down:2 - :star:1328
* [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". - :arrow_down:3 - :star:33
* [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. - :arrow_down:1 - :star:7
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords. - :arrow_down:1 - :star:16
* [jwc](https://github.com/khezen/jwc) - JSON Web Cryptography library.
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). - :arrow_down:0 - :star:1486
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. - :arrow_down:18 - :star:771
* [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's. - :arrow_down:17 - :star:354
* [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. - :arrow_down:0 - :star:109
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. - :arrow_down:108 - :star:452
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. - :arrow_down:22 - :star:72
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. - :arrow_down:0 - :star:16

## Serialization

*Libraries and tools for binary serialization.*

* [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. - :arrow_down:2 - :star:5
* [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. - :arrow_down:0 - :star:54
* [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
* [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. - :arrow_down:1 - :star:42
* [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures. - :arrow_down:0 - :star:215
* [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go. - :arrow_down:0 - :star:3
* [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. - :arrow_down:119 - :star:249
* [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". - :arrow_down:250 - :star:2835
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. - :arrow_down:4445 - :star:676
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. - :arrow_down:0 - :star:56
* [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. - :arrow_down:0 - :star:39

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. - :arrow_down:0 - :star:268
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. - :arrow_down:1636 - :star:8166
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers. - :arrow_down:2 - :star:2181
* [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery. - :arrow_down:0 - :star:11011
* [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback. - :arrow_down:0 - :star:317
* [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
* [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
* [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go. - :arrow_down:0 - :star:435
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. - :arrow_down:0 - :star:4239
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager. - :arrow_down:2 - :star:235
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold. - :arrow_down:391 - :star:507
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade. - :arrow_down:431 - :star:644
* [damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others. - :arrow_down:0 - :star:16
* [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. - :arrow_down:1 - :star:274
* [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
* [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/). - :arrow_down:132 - :star:93
* [gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images. - :arrow_down:182 - :star:335
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine. - :arrow_down:5 - :star:966
* [jet](https://github.com/CloudyKit/jet) - Jet template engine. - :arrow_down:33 - :star:310
* [kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation. - :arrow_down:3 - :star:67
* [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates. - :arrow_down:10 - :star:54
* [mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language. - :arrow_down:124 - :star:803
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go. - :arrow_down:297 - :star:795
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. - :arrow_down:27 - :star:533
* [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go. - :arrow_down:93 - :star:109
* [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. - :arrow_down:0 - :star:537
* [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). - :arrow_down:6 - :star:116
* [velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go. - :arrow_down:17 - :star:58

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions. - :arrow_down:0 - :star:6
    * [badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package. - :arrow_down:0 - :star:2
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy. - :arrow_down:0 - :star:222
    * [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible. - :arrow_down:0 - :star:5
    * [bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them. - :arrow_down:0 - :star:11
    * [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests. - :arrow_down:0 - :star:182
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework. - :arrow_down:0 - :star:49
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby. - :arrow_down:0 - :star:29
    * [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files. - :arrow_down:2 - :star:2
    * [endly](https://github.com/viant/endly) - Declarative end to end functional testing. - :arrow_down:32 - :star:31
    * [frisby](https://github.com/verdverm/frisby) - REST API testing framework. - :arrow_down:5 - :star:159
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal. - :arrow_down:0 - :star:147
    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code. - :arrow_down:6 - :star:70
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package. - :arrow_down:0 - :star:26
    * [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go. - :arrow_down:0 - :star:306
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions. - :arrow_down:3 - :star:6
    * [godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go. - :arrow_down:34 - :star:94
    * [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework. - :arrow_down:0 - :star:50
    * [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go. - :arrow_down:1 - :star:6
    * [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. - :arrow_down:0 - :star:0
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns. - :arrow_down:0 - :star:66
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. - :arrow_down:0 - :star:23
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing. - :arrow_down:36 - :star:580
    * [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
    * [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications. - :arrow_down:0 - :star:67
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package. - :arrow_down:1 - :star:2304
    * [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
    * [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools. - :arrow_down:0 - :star:1
    * [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler. - :arrow_down:0 - :star:37

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects. - :arrow_down:0 - :star:100
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions. - :arrow_down:14 - :star:273
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. - :arrow_down:0 - :star:9
    * [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. - :arrow_down:2 - :star:227
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing. - :arrow_down:5 - :star:8
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
    * [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces. - :arrow_down:3 - :star:0
    * [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter. - :arrow_down:0 - :star:19

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values. - :arrow_down:707 - :star:244
    * [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework. - :arrow_down:7 - :star:148

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. - :arrow_down:8 - :star:127
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. - :arrow_down:6 - :star:2026
    * [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs. - :arrow_down:0 - :star:141
    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers. - :arrow_down:0 - :star:624

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text. - :arrow_down:0 - :star:38
    * [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots. - :arrow_down:2 - :star:2
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags. - :arrow_down:1 - :star:0
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go. - :arrow_down:2714 - :star:1984
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer. - :arrow_down:475 - :star:466
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers. - :arrow_down:1 - :star:4991
    * [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go. - :arrow_down:0 - :star:488
    * [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
    * [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
    * [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go. - :arrow_down:0 - :star:0
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/). - :arrow_down:0 - :star:2
    * [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decodersa. - :arrow_down:5 - :star:2
    * [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings. - :arrow_down:0 - :star:36
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection). - :arrow_down:0 - :star:9
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. - :arrow_down:2055 - :star:752
    * [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. - :arrow_down:4 - :star:17
    * [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. - :arrow_down:487 - :star:57
    * [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support. - :arrow_down:3 - :star:5
    * [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard. - :arrow_down:2 - :star:7
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
    * [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go. - :arrow_down:63 - :star:486
    * [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. - :arrow_down:95 - :star:55
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts. - :arrow_down:0 - :star:20
    * [goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery). - :arrow_down:1 - :star:90
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. - :arrow_down:2452 - :star:3162
    * [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions. - :arrow_down:57 - :star:20
    * [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go. - :arrow_down:6 - :star:105
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. - :arrow_down:2 - :star:21
    * [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. - :arrow_down:19 - :star:13
    * [inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector. - :arrow_down:108 - :star:500
    * [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. - :arrow_down:153 - :star:132
    * [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. - :arrow_down:3 - :star:33
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. - :arrow_down:168 - :star:80
    * [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [syndfeed](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0. - :arrow_down:1 - :star:2
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). - :arrow_down:3913 - :star:1016
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. - :arrow_down:19 - :star:127
    * [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. - :arrow_down:7 - :star:1
    * [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes. - :arrow_down:0 - :star:3
    * [parth](https://github.com/codemodus/parth) - URL path segmentation parsing. - :arrow_down:5 - :star:8
    * [radix](https://github.com/yourbasic/radix) - fast string sorting algorithm. - :arrow_down:0 - :star:51
    * [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct. - :arrow_down:2 - :star:9
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text. - :arrow_down:64 - :star:202

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API. - :arrow_down:360 - :star:581
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language. - :arrow_down:0 - :star:2752
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. - :arrow_down:1 - :star:10
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/). - :arrow_down:0 - :star:27
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API. - :arrow_down:5 - :star:9
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2. - :arrow_down:3 - :star:13
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API. - :arrow_down:427 - :star:150
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API. - :arrow_down:0 - :star:82
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API. - :arrow_down:73 - :star:340
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging. - :arrow_down:3 - :star:25
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API. - :arrow_down:25 - :star:20
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. - :arrow_down:5 - :star:17
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging. - :arrow_down:0 - :star:29
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. - :arrow_down:61 - :star:136
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4. - :arrow_down:11 - :star:245
* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler - :arrow_down:1 - :star:1
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API. - :arrow_down:0 - :star:4
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com) - :arrow_down:7 - :star:2
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) - :arrow_down:36 - :star:48
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS. - :arrow_down:270 - :star:106
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. - :arrow_down:4 - :star:74
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API. - :arrow_down:2 - :star:12
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. - :arrow_down:2 - :star:17
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website. - :arrow_down:2 - :star:11
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library. - :arrow_down:8 - :star:19
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting. - :arrow_down:1 - :star:5
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. - :arrow_down:0 - :star:452
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. - :arrow_down:6 - :star:85
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. - :arrow_down:82 - :star:99
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. - :arrow_down:32 - :star:95
* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/). - :arrow_down:0 - :star:15
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API. - :arrow_down:0 - :star:51
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster. - :arrow_down:8 - :star:39
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. - :arrow_down:150 - :star:193
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. - :arrow_down:4 - :star:14
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API. - :arrow_down:0 - :star:11
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API. - :arrow_down:13 - :star:108
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK. - :arrow_down:0 - :star:0
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. - :arrow_down:12 - :star:13
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. - :arrow_down:0 - :star:3
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* [slack](https://github.com/nlopes/slack) - Slack API in Go. - :arrow_down:634 - :star:645
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. - :arrow_down:0 - :star:6
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. - :arrow_down:0 - :star:7
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API. - :arrow_down:1591 - :star:448
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. - :arrow_down:0 - :star:5
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org). - :arrow_down:0 - :star:5
* [translate](https://github.com/poorny/translate) - Go online translation package. - :arrow_down:0 - :star:13
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API. - :arrow_down:3 - :star:4
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. - :arrow_down:0 - :star:1
* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API. - :arrow_down:0 - :star:28
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket. - :arrow_down:0 - :star:29
* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API. - :arrow_down:0 - :star:7
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API. - :arrow_down:0 - :star:2

## Utilities

*General utilities and tools to make your life easier.*

* [abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers. - :arrow_down:0 - :star:9
* [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API. - :arrow_down:0 - :star:54
* [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. - :arrow_down:0 - :star:4
* [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates. - :arrow_down:0 - :star:257
* [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities. - :arrow_down:0 - :star:83
* [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. - :arrow_down:14 - :star:35
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go. - :arrow_down:70 - :star:355
* [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang. - :arrow_down:799 - :star:45
* [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher. - :arrow_down:0 - :star:1
* [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage. - :arrow_down:0 - :star:25
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics. - :arrow_down:0 - :star:7004
* [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
* [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. - :arrow_down:14 - :star:42
* [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. - :arrow_down:13 - :star:86
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls. - :arrow_down:13 - :star:3
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy. - :arrow_down:0 - :star:196
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend. - :arrow_down:0 - :star:7
* [fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang. - :arrow_down:0 - :star:6
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. - :arrow_down:2 - :star:70
* [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag. - :arrow_down:1 - :star:10
* [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go. - :arrow_down:0 - :star:14906
* [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes. - :arrow_down:0 - :star:29
* [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. - :arrow_down:0 - :star:1
* [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
* [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git. - :arrow_down:0 - :star:209
* [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code. - :arrow_down:23 - :star:34
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only). - :arrow_down:0 - :star:84
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
* [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. - :arrow_down:46 - :star:166
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). - :arrow_down:8 - :star:393
* [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services. - :arrow_down:0 - :star:52
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields. - :arrow_down:1 - :star:12
* [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go. - :arrow_down:21 - :star:195
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs. - :arrow_down:0 - :star:1452
* [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. - :arrow_down:2 - :star:51
* [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. - :arrow_down:5 - :star:25
* [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. - :arrow_down:30 - :star:267
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. - :arrow_down:0 - :star:3135
* [gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [golarm](https://github.com/msempere/golarm) - Fire alarms with system events. - :arrow_down:1 - :star:19
* [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. - :arrow_down:0 - :star:22
* [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. - :arrow_down:28 - :star:358
* [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. - :arrow_down:6 - :star:11
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible. - :arrow_down:2 - :star:2843
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report. - :arrow_down:0 - :star:2059
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features. - :arrow_down:0 - :star:10
* [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
* [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go. - :arrow_down:38 - :star:50
* [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection. - :arrow_down:2 - :star:21
* [gubrak](https://gubrak.github.io/) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
* [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
* [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility. - :arrow_down:5 - :star:422
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal. - :arrow_down:0 - :star:9143
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor. - :arrow_down:0 - :star:488
* [intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits. - :arrow_down:0 - :star:87
* [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
* [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go. - :arrow_down:18 - :star:70
* [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. - :arrow_down:0 - :star:341
* [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. - :arrow_down:901 - :star:163
* [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
* [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
* [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers. - :arrow_down:0 - :star:48
* [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. - :arrow_down:143 - :star:665
* [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). - :arrow_down:1 - :star:2
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template. - :arrow_down:0 - :star:119
* [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
* [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. - :arrow_down:0 - :star:43
* [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. - :arrow_down:1 - :star:44
* [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support. - :arrow_down:0 - :star:26
* [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. - :arrow_down:1 - :star:40
* [okrun](https://github.com/xta/okrun) - go run error steamroller. - :arrow_down:0 - :star:11
* [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
* [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). - :arrow_down:5 - :star:74
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. - :arrow_down:0 - :star:1290
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. - :arrow_down:5 - :star:3104
* [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
* [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. - :arrow_down:3 - :star:40
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go. - :arrow_down:213 - :star:323
* [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs. - :arrow_down:4 - :star:19
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths. - :arrow_down:0 - :star:667
* [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating. - :arrow_down:9 - :star:45
* [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. - :arrow_down:10 - :star:148
* [rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go. - :arrow_down:1 - :star:5
* [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. - :arrow_down:0 - :star:111
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. - :arrow_down:61 - :star:320
* [retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful. - :arrow_down:1 - :star:0
* [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go. - :arrow_down:0 - :star:2
* [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go. - :arrow_down:0 - :star:17
* [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done. - :arrow_down:0 - :star:7
* [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang. - :arrow_down:4 - :star:21
* [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. - :arrow_down:4 - :star:107
* [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need.
* [silk](https://github.com/chrispassas/silk) - Read silk netflow files.
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
* [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. - :arrow_down:104 - :star:258
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. - :arrow_down:1987 - :star:2005
* [sslice](https://github.com/yaa110/sslice) - Create a slice which is always sorted.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB. - :arrow_down:140 - :star:255
* [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs. - :arrow_down:0 - :star:5
* [Task](https://github.com/go-task/task) - simple "Make" alternative. - :arrow_down:0 - :star:875
* [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. - :arrow_down:53 - :star:2
* [ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go. - :arrow_down:0 - :star:10
* [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go. - :arrow_down:1 - :star:64
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases. - :arrow_down:0 - :star:2395
* [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...). - :arrow_down:0 - :star:68
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection. - :arrow_down:0 - :star:7408
* [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. - :arrow_down:0 - :star:12

## UUID

*Libraries for working with UUIDs.*

* [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. - :arrow_down:0 - :star:0
* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. - :arrow_down:48 - :star:372
* [wuid](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. - :arrow_down:633 - :star:1270
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. - :arrow_down:2 - :star:403
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. - :arrow_down:77 - :star:23
* [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
* [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications. - :arrow_down:15 - :star:1
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. - :arrow_down:16 - :star:685

## Version Control

*Libraries for version control.*

* [gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks. - :arrow_down:0 - :star:41
* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. - :arrow_down:146 - :star:875
* [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. - :arrow_down:4 - :star:8

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. - :arrow_down:22 - :star:230
* [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). - :arrow_down:23 - :star:104
* [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO. - :arrow_down:24 - :star:204
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - Parser and generator library for Apple m3u8 playlists.
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg. - :arrow_down:0 - :star:205
* [gst](https://github.com/ziutek/gst) - Go bindings for GStreamer. - :arrow_down:24 - :star:117
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). - :arrow_down:2 - :star:3
* [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go. - :arrow_down:3 - :star:0

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [Aero](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse. - :arrow_down:90 - :star:38
* [Air](https://github.com/aofei/air) - An ideally refined web framework for Go.
* [Banjo](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go. - :arrow_down:0 - :star:1
* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language. - :arrow_down:6542 - :star:8099
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework. - :arrow_down:2294 - :star:5237
* [Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework. - :arrow_down:6 - :star:1
* [Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API. - :arrow_down:15 - :star:88
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. - :arrow_down:6648 - :star:7720
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times. - :arrow_down:0 - :star:1506
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go. - :arrow_down:13 - :star:95
* [goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis. - :arrow_down:46 - :star:1346
* [Golax](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more. - :arrow_down:7 - :star:54
* [Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library. - :arrow_down:40 - :star:179
* [Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster. - :arrow_down:0 - :star:298
* [gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection. - :arrow_down:8 - :star:220
* [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go. - :arrow_down:27 - :star:1219
* [mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333. - :arrow_down:82 - :star:304
* [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang. - :arrow_down:0 - :star:41
* [neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API. - :arrow_down:22 - :star:276
* [nio](https://github.com/go-nio/nio) - Modern, minimal and productive Go HTTP framework.
* [Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services. - :arrow_down:2 - :star:25
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language. - :arrow_down:2150 - :star:7262
* [rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`. - :arrow_down:3 - :star:11
* [sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go. - :arrow_down:177 - :star:454
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard. - :arrow_down:162 - :star:943
* [traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go. - :arrow_down:111 - :star:486
* [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang). - :arrow_down:15 - :star:1615
* [vox](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily. - :arrow_down:0 - :star:4
* [WebGo](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc). - :arrow_down:2 - :star:4
* [YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way. - :arrow_down:9 - :star:25
* [Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework. - :arrow_down:10 - :star:136

### Middlewares

#### Actual middlewares

* [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header. - :arrow_down:1 - :star:9
* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. - :arrow_down:814 - :star:361
* [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. - :arrow_down:0 - :star:20
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header. - :arrow_down:4 - :star:690
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. - :arrow_down:20 - :star:226
* [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin)
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. - :arrow_down:48 - :star:410
* [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. - :arrow_down:24 - :star:51

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. - :arrow_down:443 - :star:988
* [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). - :arrow_down:1 - :star:6
* [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). - :arrow_down:5 - :star:61
* [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http. - :arrow_down:1 - :star:52
* [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. - :arrow_down:2 - :star:43
* [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. - :arrow_down:84 - :star:261
* [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. - :arrow_down:5 - :star:197
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang. - :arrow_down:384 - :star:3933
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. - :arrow_down:535 - :star:725
* [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. - :arrow_down:0 - :star:86
* [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. - :arrow_down:7 - :star:77
* [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application. - :arrow_down:172 - :star:363

### Routers

* [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space. - :arrow_down:3 - :star:62
* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. - :arrow_down:159 - :star:924
* [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. - :arrow_down:11 - :star:53
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context. - :arrow_down:293 - :star:3545
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`. - :arrow_down:69 - :star:141
* [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go. - :arrow_down:3 - :star:13
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go. - :arrow_down:275 - :star:1131
* [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. - :arrow_down:0 - :star:303
* [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. - :arrow_down:5 - :star:32
* [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface. - :arrow_down:9 - :star:143
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework. - :arrow_down:3690 - :star:3629
* [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. - :arrow_down:262 - :star:171
* [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. - :arrow_down:61 - :star:306
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang. - :arrow_down:13997 - :star:2741
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. - :arrow_down:71 - :star:108
* [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation. - :arrow_down:14 - :star:8
* [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers. - :arrow_down:10 - :star:337
* [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications. - :arrow_down:35 - :star:68
* [violetear](https://github.com/nbari/violetear) - Go HTTP router. - :arrow_down:42 - :star:15
* [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support. - :arrow_down:13 - :star:62
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go. - :arrow_down:0 - :star:87

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9. - :arrow_down:2 - :star:28
* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. - :arrow_down:61 - :star:230

## XML

*Libraries and tools for manipulating XML.*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module. - :arrow_down:0 - :star:3
* [xpath](https://github.com/antchfx/xpath) - XPath package for Go. - :arrow_down:9 - :star:62
* [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
* [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
# Tools

*Go software and plugins.*

## Code Analysis

* [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes. - :arrow_down:0 - :star:42
* [dupl](https://github.com/mibk/dupl) - Tool for code clone detection. - :arrow_down:0 - :star:61
* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. - :arrow_down:0 - :star:674
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. - :arrow_down:0 - :star:586
* [Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form. - :arrow_down:0 - :star:1174
* [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments. - :arrow_down:6 - :star:30
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. - :arrow_down:0 - :star:210
* [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
* [go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages. - :arrow_down:0 - :star:28
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. - :arrow_down:0 - :star:143
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [GolangCI](https://golangci.com/) - GolangCI is an automated Golang code review service for GitHub pull requests. Service is open source and it's free for open source projects.
* [GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code. - :arrow_down:128 - :star:1467
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages. - :arrow_down:0 - :star:173
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test. - :arrow_down:2 - :star:45
* [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go. - :arrow_down:0 - :star:390
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code. - :arrow_down:0 - :star:8
* [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source. - :arrow_down:0 - :star:152
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. - :arrow_down:3 - :star:57

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language. - :arrow_down:0 - :star:3311
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* [velour](https://github.com/velour/velour) - IRC client for the acme editor. - :arrow_down:0 - :star:13
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. - :arrow_down:0 - :star:114

## Go Generate Tools

* [generic](https://github.com/usk81/generic) - flexible data type for Go. - :arrow_down:0 - :star:0
* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go. - :arrow_down:0 - :star:156
* [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation. - :arrow_down:0 - :star:45
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go. - :arrow_down:0 - :star:85
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code. - :arrow_down:2 - :star:268
* [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates. - :arrow_down:0 - :star:2
* [re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code. - :arrow_down:0 - :star:100

## Go Tools

* [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output. - :arrow_down:0 - :star:69
* [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports. - :arrow_down:2 - :star:227
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](http://yeoman.io) generator to get new Go projects started.
* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format. - :arrow_down:0 - :star:2
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. - :arrow_down:10 - :star:716
* [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations. - :arrow_down:0 - :star:273
* [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses. - :arrow_down:0 - :star:111

## Software Packages

*Software written in Go.*

### DevOps Tools

* [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool. - :arrow_down:0 - :star:1124
* [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console. - :arrow_down:0 - :star:286
* [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile. - :arrow_down:0 - :star:8
* [Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics. - :arrow_down:0 - :star:328
* [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs. - :arrow_down:0 - :star:133
* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool. - :arrow_down:0 - :star:214
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
* [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). - :arrow_down:0 - :star:117
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI. - :arrow_down:0 - :star:13
* [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. - :arrow_down:0 - :star:30
* [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. - :arrow_down:7 - :star:44
* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts. - :arrow_down:0 - :star:1450
* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. - :arrow_down:5 - :star:2533
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven. - :arrow_down:0 - :star:249
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
* [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. - :arrow_down:0 - :star:396
* [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. - :arrow_down:1 - :star:191
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. - :arrow_down:0 - :star:241
* [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries. - :arrow_down:0 - :star:81
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool. - :arrow_down:0 - :star:1794
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging. - :arrow_down:0 - :star:1332
* [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease. - :arrow_down:0 - :star:24
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application. - :arrow_down:0 - :star:261
* [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. - :arrow_down:0 - :star:869
* [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages. - :arrow_down:0 - :star:21
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries. - :arrow_down:0 - :star:191
* [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
* [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily. - :arrow_down:0 - :star:164
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. - :arrow_down:0 - :star:164
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. - :arrow_down:0 - :star:69
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. - :arrow_down:0 - :star:5674
* [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester. - :arrow_down:0 - :star:2
* [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
* [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. - :arrow_down:60 - :star:731
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). - :arrow_down:0 - :star:162
* [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. - :arrow_down:0 - :star:0
* [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! - :arrow_down:1 - :star:403
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. - :arrow_down:0 - :star:619
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends. - :arrow_down:0 - :star:4453
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! - :arrow_down:0 - :star:4239
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. - :arrow_down:0 - :star:493
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets. - :arrow_down:0 - :star:906
* [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine. - :arrow_down:0 - :star:55
* [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. - :arrow_down:0 - :star:3155
* [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. - :arrow_down:0 - :star:44
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH. - :arrow_down:10 - :star:681
* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go. - :arrow_down:0 - :star:3
* [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. - :arrow_down:0 - :star:57
* [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. - :arrow_down:0 - :star:49
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
* [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. - :arrow_down:4 - :star:6206
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO. - :arrow_down:0 - :star:162
* [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together. - :arrow_down:0 - :star:110
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. - :arrow_down:0 - :star:260
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go. - :arrow_down:0 - :star:973
* [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go. - :arrow_down:1 - :star:5
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go. - :arrow_down:0 - :star:2357
* [orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go. - :arrow_down:1 - :star:141
* [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates. - :arrow_down:0 - :star:96
* [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. - :arrow_down:0 - :star:311
* [Pipe](https://github.com/b3log/pipe) - A small and beautiful blogging platform. - :arrow_down:0 - :star:1021
* [restic](https://github.com/restic/restic) - De-duplicating backup program. - :arrow_down:11 - :star:677
* [rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. - :arrow_down:0 - :star:581
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). - :arrow_down:0 - :star:53
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework. - :arrow_down:0 - :star:978
* [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru. - :arrow_down:0 - :star:14
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. - :arrow_down:0 - :star:1256
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [term-quiz](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal. - :arrow_down:0 - :star:11
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). - :arrow_down:5 - :star:200

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. - :arrow_down:0 - :star:13
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. - :arrow_down:0 - :star:36
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. - :arrow_down:0 - :star:759
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark. - :arrow_down:0 - :star:177
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. - :arrow_down:0 - :star:375
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. - :arrow_down:0 - :star:47
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others. - :arrow_down:0 - :star:5
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. - :arrow_down:0 - :star:11
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. - :arrow_down:0 - :star:81

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
* [dotGo](http://www.dotgo.eu) - Paris, France.
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan.
* [GoDays](https://www.godays.io/) - Berlin, Germany.
* [GoLab](http://golab.io/) - Florence, Italy.
* [GolangUK](http://golanguk.com/) - London, UK.
* [GopherChina](http://gopherchina.org) - Shanghai, China.
* [GopherCon](http://www.gophercon.com/) - Denver, USA.
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR.
* [GopherCon Europe](https://gophercon.is/) - Reykjavik, Iceland.
* [GopherCon India](https://www.gophercon.in/) - Pune, India.
* [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
* [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
* [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
* [GothamGo](http://gothamgo.com/) - New York City, USA.
* [GoWayFest](https://goway.io/) - Minsk, Belarus.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg].
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
* [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara. - :arrow_down:0 - :star:1274
* [gophers](https://github.com/egonelbre/gophers) - Free gophers. - :arrow_down:0 - :star:275
* [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics.
* [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers. - :arrow_down:0 - :star:551
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.




## Other Useful Links
* [golang/go](https://github.com/golang/go) - The Go programming language
* [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) - Production-Grade Container Scheduling and Management
* [avelino/awesome-go](https://github.com/avelino/awesome-go) - A curated list of awesome Go frameworks, libraries and software
* [moby/moby](https://github.com/moby/moby) - Moby Project - a collaborative project for the container ecosystem to assemble container-based systems
* [gohugoio/hugo](https://github.com/gohugoio/hugo) - The world’s fastest framework for building websites.
* [gin-gonic/gin](https://github.com/gin-gonic/gin) - Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin.
* [fatedier/frp](https://github.com/fatedier/frp) - A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.
* [syncthing/syncthing](https://github.com/syncthing/syncthing) - Open Source Continuous File Synchronization
* [junegunn/fzf](https://github.com/junegunn/fzf) - :cherry_blossom: A command-line fuzzy finder
* [astaxie/build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) - A golang ebook intro how to build a web with golang
* [etcd-io/etcd](https://github.com/etcd-io/etcd) - Distributed reliable key-value store for the most critical data of a distributed system
* [gogs/gogs](https://github.com/gogs/gogs) - Gogs is a painless self-hosted Git service
* [traefik/traefik](https://github.com/traefik/traefik) - The Cloud Native Application Proxy
* [caddyserver/caddy](https://github.com/caddyserver/caddy) - Fast, multi-platform web server with automatic HTTPS
* [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol
* [minio/minio](https://github.com/minio/minio) - High Performance, Kubernetes Native Object Storage
* [rclone/rclone](https://github.com/rclone/rclone) - "rsync for cloud storage" - Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files
* [pingcap/tidb](https://github.com/pingcap/tidb) - TiDB is an open source distributed HTAP database compatible with the MySQL protocol
* [unknwon/the-way-to-go_ZH_CN](https://github.com/unknwon/the-way-to-go_ZH_CN) - 《The Way to Go》中文译本，中文正式名《Go 入门指南》
* [go-gitea/gitea](https://github.com/go-gitea/gitea) - Git with a cup of tea, painless self-hosted git service
* [beego/beego](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [go-gorm/gorm](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly
* [spf13/cobra](https://github.com/spf13/cobra) - A Commander for modern Go CLI interactions
* [docker/compose](https://github.com/docker/compose) - Define and run multi-container applications with Docker
* [harness/drone](https://github.com/harness/drone) - Drone is a Container-Native, Continuous Delivery Platform
* [kubernetes/minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally
* [cockroachdb/cockroach](https://github.com/cockroachdb/cockroach) - CockroachDB - the open source, cloud-native distributed SQL database.
* [halfrost/LeetCode-Go](https://github.com/halfrost/LeetCode-Go) - ✅ Solutions to LeetCode by Go, 100% test coverage, runtime beats 100% / LeetCode 题解
* [influxdata/influxdb](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics
* [hashicorp/vault](https://github.com/hashicorp/vault) - A tool for secrets management, encryption as a service, and privileged access management
* [Dreamacro/clash](https://github.com/Dreamacro/clash) - A rule-based tunnel in Go.
* [go-kit/kit](https://github.com/go-kit/kit) - A standard library for microservices.
* [kataras/iris](https://github.com/kataras/iris) - The fastest HTTP/2 Go Web Framework. AWS Lambda, gRPC, MVC, Unique Router, Websockets, Sessions, Test suite, Dependency Injection and more. A true successor of expressjs and laravel | 谢谢 https://github.com/kataras/iris/issues/1329 |
* [github/hub](https://github.com/github/hub) - A command-line tool that makes git easier to use with GitHub.
* [labstack/echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework
* [nsqio/nsq](https://github.com/nsqio/nsq) - A realtime distributed messaging platform
* [ehang-io/nps](https://github.com/ehang-io/nps) - 一款轻量级、高性能、功能强大的内网穿透代理服务器。支持tcp、udp、socks5、http等几乎所有流量转发，可用来访问内网网站、本地支付接口调试、ssh访问、远程桌面，内网dns解析、内网socks5代理等等……，并带有功能强大的web管理端。a lightweight, high-performance, powerful intranet penetration proxy server, with a powerful web management terminal.
* [sirupsen/logrus](https://github.com/sirupsen/logrus) - Structured, pluggable logging for Go.
* [coreybutler/nvm-windows](https://github.com/coreybutler/nvm-windows) - A node.js version management utility for Windows. Ironically written in Go.
* [tsenart/vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [zyedidia/micro](https://github.com/zyedidia/micro) - A modern and intuitive terminal-based text editor
* [photoprism/photoprism](https://github.com/photoprism/photoprism) - Photos App powered by Go and Google TensorFlow 🌈 🎄
* [tmrts/go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms
* [spf13/viper](https://github.com/spf13/viper) - Go configuration with fangs
* [go-delve/delve](https://github.com/go-delve/delve) - Delve is a debugger for the Go programming language.
* [gofiber/fiber](https://github.com/gofiber/fiber) - ⚡️ Express inspired web framework written in Go
* [asim/go-micro](https://github.com/asim/go-micro) - A framework for distributed systems development
* [dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) - Native GraphQL Database with graph backend
* [urfave/cli](https://github.com/urfave/cli) - A simple, fast, and fun package for building command line apps in Go
* [valyala/fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http
* [iawia002/annie](https://github.com/iawia002/annie) - 👾 Fast and simple video download library and CLI tool written in Go
* [chai2010/advanced-go-programming-book](https://github.com/chai2010/advanced-go-programming-book) - :books: 《Go语言高级编程》开源图书，涵盖CGO、Go汇编语言、RPC实现、Protobuf插件实现、Web框架实现、分布式系统等高阶主题(完稿)
* [quii/learn-go-with-tests](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development
* [gorilla/websocket](https://github.com/gorilla/websocket) - A fast, well-tested and widely used WebSocket implementation for Go.
* [yudai/gotty](https://github.com/yudai/gotty) - Share your terminal as a web application
* [go-kratos/kratos](https://github.com/go-kratos/kratos) - A modular-designed and easy-to-use microservices framework in Go.
* [gorilla/mux](https://github.com/gorilla/mux) - A powerful HTTP router and URL matcher for building Go web servers with 🦍
* [gocolly/colly](https://github.com/gocolly/colly) - Elegant Scraper and Crawler Framework for Golang
* [fyne-io/fyne](https://github.com/fyne-io/fyne) - Cross platform GUI in Go inspired by Material Design
* [restic/restic](https://github.com/restic/restic) - Fast, secure, efficient backup program
* [grpc/grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC
* [stretchr/testify](https://github.com/stretchr/testify) - A toolkit with common assertions and mocks that plays nicely with the standard library
* [buger/goreplay](https://github.com/buger/goreplay) - GoReplay is an open-source tool for capturing and replaying live HTTP traffic into a test environment in order to continuously test your system with real data. It can be used to increase confidence in code deployments, configuration changes and infrastructure changes.
* [grafana/k6](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript - https://k6.io
* [derailed/k9s](https://github.com/derailed/k9s) - 🐶 Kubernetes CLI To Manage Your Clusters In Style!
* [hoanhan101/ultimate-go](https://github.com/hoanhan101/ultimate-go) - The Ultimate Go Study Guide
* [uber-go/zap](https://github.com/uber-go/zap) - Blazing fast, structured, leveled logging in Go.
* [cayleygraph/cayley](https://github.com/cayleygraph/cayley) - An open-source graph database
* [zeromicro/go-zero](https://github.com/zeromicro/go-zero) - go-zero is a web and rpc framework written in Go. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
* [kubernetes/kops](https://github.com/kubernetes/kops) - Kubernetes Operations (kops) - Production Grade K8s Installation, Upgrades, and Management
* [julienschmidt/httprouter](https://github.com/julienschmidt/httprouter) - A high performance HTTP request router that scales well
* [go-redis/redis](https://github.com/go-redis/redis) - Type-safe Redis client for Golang
* [golang/dep](https://github.com/golang/dep) - Go dependency management tool experiment (deprecated)
* [wtfutil/wtf](https://github.com/wtfutil/wtf) - The personal information dashboard for your terminal
* [ipfs/go-ipfs](https://github.com/ipfs/go-ipfs) - IPFS implementation in Go
* [revel/revel](https://github.com/revel/revel) - A high productivity, full-stack web framework for the Go language.
* [boltdb/bolt](https://github.com/boltdb/bolt) - An embedded key/value database for Go.
* [grpc-ecosystem/grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway) - gRPC to JSON proxy generator following the gRPC HTTP spec
* [CodisLabs/codis](https://github.com/CodisLabs/codis) - Proxy based Redis cluster solution supporting pipeline and scaling dynamically
* [inancgumus/learngo](https://github.com/inancgumus/learngo) - 1000+ Hand-Crafted Go Examples, Exercises, and Quizzes
* [ory/hydra](https://github.com/ory/hydra) - OpenID Certified™ OpenID Connect and OAuth Provider written in Go - cloud native, security-first, open source API security for your infrastructure. SDKs for any language. Compatible with MITREid.
* [docker-slim/docker-slim](https://github.com/docker-slim/docker-slim) - DockerSlim (docker-slim): Don't change anything in your Docker container image and minify it by up to 30x (and for compiled languages even more) making it secure too! (free and open source)
* [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - Go MySQL Driver is a MySQL driver for Go's (golang) database/sql package
* [fogleman/primitive](https://github.com/fogleman/primitive) - Reproducing images with geometric primitives.
* [snail007/goproxy](https://github.com/snail007/goproxy) - 🔥  Proxy is a high performance HTTP(S) proxies, SOCKS5 proxies,WEBSOCKET, TCP, UDP proxy server implemented by golang. Now, it supports chain-style proxies,nat forwarding in different lan,TCP/UDP port forwarding, SSH forwarding.Proxy是golang实现的高性能http,https,websocket,tcp,socks5代理服务器,支持内网穿透,链式代理,通讯加密,智能HTTP,SOCKS5代理,黑白名单,限速,限流量,限连接数,跨平台,KCP支持,认证API。
* [go-martini/martini](https://github.com/go-martini/martini) - Classy web framework for Go
* [casbin/casbin](https://github.com/casbin/casbin) - An authorization library that supports access control models like ACL, RBAC, ABAC in Golang
* [pulumi/pulumi](https://github.com/pulumi/pulumi) - Pulumi - Developer-First Infrastructure as Code. Your Cloud, Your Language, Your Way 🚀
* [PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) - A little like that j-thing, only in Go.
* [emirpasic/gods](https://github.com/emirpasic/gods) - GoDS (Go Data Structures). Containers (Sets, Lists, Stacks, Maps, Trees), Sets (HashSet, TreeSet, LinkedHashSet), Lists (ArrayList, SinglyLinkedList, DoublyLinkedList), Stacks (LinkedListStack, ArrayStack), Maps (HashMap, TreeMap, HashBidiMap, TreeBidiMap, LinkedHashMap), Trees (RedBlackTree, AVLTree, BTree, BinaryHeap), Comparators, Iterators, Enumerables, Sort, JSON
* [flipped-aurora/gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin) - 基于vite+vue3+gin搭建的开发基础平台（已完成setup语法糖版本），集成jwt鉴权，权限管理，动态路由，分页封装，多点登录拦截，资源权限，上传下载，代码生成器，表单生成器等开发必备功能，五分钟一套CURD前后端代码。
* [gopherjs/gopherjs](https://github.com/gopherjs/gopherjs) - A compiler from Go to JavaScript for running Go code in a browser
* [gravitational/teleport](https://github.com/gravitational/teleport) - Certificate authority and access plane for SSH, Kubernetes, web apps, databases and desktops
* [go-chi/chi](https://github.com/go-chi/chi) - lightweight, idiomatic and composable router for building Go HTTP services
* [halfrost/Halfrost-Field](https://github.com/halfrost/Halfrost-Field) - ✍🏻 这里是写博客的地方 —— Halfrost-Field 冰霜之地
* [qax-os/excelize](https://github.com/qax-os/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [google/grumpy](https://github.com/google/grumpy) - Grumpy is a Python to Go source code transcompiler and runtime.
* [json-iterator/go](https://github.com/json-iterator/go) - A high-performance 100% compatible drop-in replacement of "encoding/json"
* [nats-io/nats-server](https://github.com/nats-io/nats-server) - High-Performance server for NATS.io, the cloud and edge native messaging system.
* [dgraph-io/badger](https://github.com/dgraph-io/badger) - Fast key-value DB in Go.
* [talkgo/night](https://github.com/talkgo/night) - Weekly Go Online Meetup via Bilibili｜Go 夜读｜通过 bilibili 在线直播的方式分享 Go 相关的技术话题，每天大家在微信/telegram/Slack 上及时沟通交流编程技术话题。
* [dgrijalva/jwt-go](https://github.com/dgrijalva/jwt-go) - ARCHIVE - Golang implementation of JSON Web Tokens (JWT). This project is now maintained at:
* [ardanlabs/gotraining](https://github.com/ardanlabs/gotraining) - Go Training Class Material :
* [OpenDiablo2/OpenDiablo2](https://github.com/OpenDiablo2/OpenDiablo2) - An open source re-implementation of Diablo 2
* [git-lfs/git-lfs](https://github.com/git-lfs/git-lfs) - Git extension for versioning large files
* [aquasecurity/trivy](https://github.com/aquasecurity/trivy) - Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues
* [asciimoo/wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection
* [FiloSottile/age](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
* [ent/ent](https://github.com/ent/ent) - An entity framework for Go
* [tidwall/gjson](https://github.com/tidwall/gjson) - Get JSON values quickly - JSON parser for Go
* [geektutu/7days-golang](https://github.com/geektutu/7days-golang) - 7 days golang programs from scratch (web framework Gee, distributed cache GeeCache, object relational mapping ORM framework GeeORM, rpc framework GeeRPC etc)  7天用Go动手写/从零实现系列
* [goreleaser/goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible
* [go-playground/validator](https://github.com/go-playground/validator) - :100:Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving
* [rqlite/rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed relational database built on SQLite
* [golangci/golangci-lint](https://github.com/golangci/golangci-lint) - Fast linters Runner for Go
* [tinygo-org/tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly (WASM/WASI), and command-line tools. Based on LLVM.
* [robfig/cron](https://github.com/robfig/cron) - a cron library for go
* [therecipe/qt](https://github.com/therecipe/qt) - Qt binding for Go (Golang) with support for Windows / macOS / Linux / FreeBSD / Android / iOS / Sailfish OS / Raspberry Pi / AsteroidOS / Ubuntu Touch / JavaScript / WebAssembly
* [future-architect/vuls](https://github.com/future-architect/vuls) - Agent-less vulnerability scanner for Linux, FreeBSD, Container, WordPress, Programming language libraries, Network devices
* [rkt/rkt](https://github.com/rkt/rkt) - [Project ended] rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards.
* [gomodule/redigo](https://github.com/gomodule/redigo) - Go client for Redis
* [zricethezav/gitleaks](https://github.com/zricethezav/gitleaks) - Scan git repos (or files) for secrets using regex and entropy 🔑
* [coredns/coredns](https://github.com/coredns/coredns) - CoreDNS is a DNS server that chains plugins
* [crawlab-team/crawlab](https://github.com/crawlab-team/crawlab) - Distributed web crawler admin platform for spiders management regardless of languages and frameworks. 分布式爬虫管理平台，支持任何语言和框架
* [pion/webrtc](https://github.com/pion/webrtc) - Pure Go implementation of the WebRTC API
* [quay/clair](https://github.com/quay/clair) - Vulnerability Static Analysis for Containers
* [tinode/chat](https://github.com/tinode/chat) - Instant messaging platform. Backend in Go. Clients: Swift iOS, Java Android, JS webapp, scriptable command line; chatbots
* [polaris1119/The-Golang-Standard-Library-by-Example](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) - Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。
* [cyfdecyf/cow](https://github.com/cyfdecyf/cow) - HTTP proxy written in Go. COW can automatically identify blocked sites and use parent proxies to access.
* [graphql-go/graphql](https://github.com/graphql-go/graphql) - An implementation of GraphQL for Go / Golang
* [google/go-cloud](https://github.com/google/go-cloud) - The Go Cloud Development Kit (Go CDK): A library and tools for open cloud development in Go.
* [golang/protobuf](https://github.com/golang/protobuf) - Go support for Google's protocol buffers
* [sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) - Machine Learning for Go
* [Masterminds/glide](https://github.com/Masterminds/glide) - Package Management for Golang
* [blevesearch/bleve](https://github.com/blevesearch/bleve) - A modern text indexing library for go
* [ginuerzh/gost](https://github.com/ginuerzh/gost) - GO Simple Tunnel - a simple tunnel written in golang
* [unknwon/go-fundamental-programming](https://github.com/unknwon/go-fundamental-programming) - 《Go 编程基础》是一套针对 Google 出品的 Go 语言的视频语音教程，主要面向新手级别的学习者。
* [openshift/origin](https://github.com/openshift/origin) - Conformance test suite for OpenShift
* [andlabs/ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go.
* [google/go-github](https://github.com/google/go-github) - Go library for accessing the GitHub API
* [Shopify/sarama](https://github.com/Shopify/sarama) - Sarama is a Go library for Apache Kafka 0.8, and up.
* [keybase/client](https://github.com/keybase/client) - Keybase Go Library, Client, Service, OS X, iOS, Android, Electron
* [goplus/gop](https://github.com/goplus/gop) - GoPlus - The Go+ language for engineering, STEM education, and data science
* [GoesToEleven/GolangTraining](https://github.com/GoesToEleven/GolangTraining) - Training for Golang (go language)
* [golang-migrate/migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* [jroimartin/gocui](https://github.com/jroimartin/gocui) - Minimalist Go package aimed at creating Console User Interfaces.
* [tylertreat/comcast](https://github.com/tylertreat/comcast) - Simulating shitty network connections so you can build better systems.
* [Shopify/toxiproxy](https://github.com/Shopify/toxiproxy) - :alarm_clock: :fire: A TCP proxy to simulate network and system conditions for chaos and resiliency testing
* [hybridgroup/gobot](https://github.com/hybridgroup/gobot) - Golang framework for robotics, drones, and the Internet of Things (IoT)
* [TheAlgorithms/Go](https://github.com/TheAlgorithms/Go) - Algorithms Implemented in GoLang
* [kubernetes/kompose](https://github.com/kubernetes/kompose) - Go from Docker Compose to Kubernetes
* [panjf2000/ants](https://github.com/panjf2000/ants) - 🐜🐜🐜 ants is a high-performance and low-cost goroutine pool in Go, inspired by fasthttp./ ants 是一个高性能且低损耗的 goroutine 池。
* [aws/aws-sdk-go](https://github.com/aws/aws-sdk-go) - AWS SDK for the Go programming language.
* [adnanh/webhook](https://github.com/adnanh/webhook) - webhook is a lightweight incoming webhook server to run shell commands
* [google/wire](https://github.com/google/wire) - Compile-time Dependency Injection for Go
* [shirou/gopsutil](https://github.com/shirou/gopsutil) - psutil for golang
* [Jguer/yay](https://github.com/Jguer/yay) - Yet another Yogurt - An AUR Helper written in Go
* [cjbassi/gotop](https://github.com/cjbassi/gotop) - A terminal based graphical activity monitor inspired by gtop and vtop
* [go-swagger/go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go
* [TykTechnologies/tyk](https://github.com/TykTechnologies/tyk) - Tyk Open Source API Gateway written in Go, supporting REST, GraphQL, TCP and gRPC protocols
* [lib/pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql
* [zserge/lorca](https://github.com/zserge/lorca) - Build cross-platform modern desktop apps in Go + HTML5
* [flannel-io/flannel](https://github.com/flannel-io/flannel) - flannel is a network fabric for containers, designed for Kubernetes
* [schachmat/wego](https://github.com/schachmat/wego) - weather app for the terminal
* [99designs/gqlgen](https://github.com/99designs/gqlgen) - go generate based graphql server library
* [smartystreets/goconvey](https://github.com/smartystreets/goconvey) - Go testing in the browser. Integrates with `go test`. Write behavioral tests in Go.
* [gcla/termshark](https://github.com/gcla/termshark) - A terminal UI for tshark, inspired by Wireshark
* [fabiolb/fabio](https://github.com/fabiolb/fabio) - Consul Load-Balancing made simple
* [charmbracelet/bubbletea](https://github.com/charmbracelet/bubbletea) - A powerful little TUI framework 🏗
* [teh-cmc/go-internals](https://github.com/teh-cmc/go-internals) - A book about the internals of the Go programming language.
* [shadowsocks/shadowsocks-go](https://github.com/shadowsocks/shadowsocks-go) - go port of shadowsocks (Deprecated)
* [fission/fission](https://github.com/fission/fission) - Fast and Simple Serverless Functions for Kubernetes
* [golang/mock](https://github.com/golang/mock) - GoMock is a mocking framework for the Go programming language.
* [codenotary/immudb](https://github.com/codenotary/immudb) - immudb - world’s fastest immutable database, built on a zero trust model
* [smallnest/rpcx](https://github.com/smallnest/rpcx) - Best microservices framework in Go, like alibaba Dubbo, but with more features, Scale easily. Try it. Test it. If you feel it's better, use it! 𝐉𝐚𝐯𝐚有𝐝𝐮𝐛𝐛𝐨, 𝐆𝐨𝐥𝐚𝐧𝐠有𝐫𝐩𝐜𝐱!
* [gobuffalo/buffalo](https://github.com/gobuffalo/buffalo) - Rapid Web Development w/ Go
* [gophish/gophish](https://github.com/gophish/gophish) - Open-Source Phishing Toolkit
* [go-xorm/xorm](https://github.com/go-xorm/xorm) - Simple and Powerful ORM for Go, support mysql,postgres,tidb,sqlite3,mssql,oracle, Moved to https://gitea.com/xorm/xorm
* [olivere/elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
* [robertkrimen/otto](https://github.com/robertkrimen/otto) - A JavaScript interpreter in Go (golang)
* [mongodb/mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - The Go driver for MongoDB
* [OWASP/Amass](https://github.com/OWASP/Amass) - In-depth Attack Surface Mapping and Asset Discovery
* [fsnotify/fsnotify](https://github.com/fsnotify/fsnotify) - Cross-platform file system notifications for Go.
* [Workiva/go-datastructures](https://github.com/Workiva/go-datastructures) - A collection of useful, performant, and threadsafe Go datastructures.
* [weaveworks/weave](https://github.com/weaveworks/weave) - Simple, resilient multi-host containers networking and more.
* [simeji/jid](https://github.com/simeji/jid) - json incremental digger
* [lucas-clemente/quic-go](https://github.com/lucas-clemente/quic-go) - A QUIC implementation in pure go
* [concourse/concourse](https://github.com/concourse/concourse) - Concourse is a container-based continuous thing-doer written in Go.
* [OpenIMSDK/Open-IM-Server](https://github.com/OpenIMSDK/Open-IM-Server) - OpenIM: Instant messaging open source project based on go built by former WeChat technology experts. Backend in Go.（由前微信技术专家打造的基于 Go 实现的即时通讯（IM）项目，从服务端到客户端SDK开源即时通讯（IM）整体解决方案，可以轻松替代第三方IM云服务，打造具备聊天、社交功能的app。）
* [Terry-Mao/goim](https://github.com/Terry-Mao/goim) - goim
* [go-ego/riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine; Warning: This is V1 and beta version, because of big memory consume, and the V2 will be rewrite all code.
* [cookieY/Yearning](https://github.com/cookieY/Yearning) - 🐳 A most popular sql audit platform for mysql
* [erroneousboat/slack-term](https://github.com/erroneousboat/slack-term) - Slack client for your terminal
* [appleboy/gorush](https://github.com/appleboy/gorush) - A push notification server written in Go (Golang).
* [miekg/dns](https://github.com/miekg/dns) - DNS library in Go
* [panjf2000/gnet](https://github.com/panjf2000/gnet) - 🚀 gnet is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go./ gnet 是一个高性能、轻量级、非阻塞的事件驱动 Go 网络框架。
* [RichardKnop/machinery](https://github.com/RichardKnop/machinery) - Machinery is an asynchronous task queue/job queue based on distributed message passing.
* [senghoo/golang-design-pattern](https://github.com/senghoo/golang-design-pattern) - 设计模式 Golang实现－《研磨设计模式》读书笔记
* [lxn/walk](https://github.com/lxn/walk) - A Windows GUI toolkit for the Go Programming Language
* [filhodanuvem/gitql](https://github.com/filhodanuvem/gitql) - 💊 A git query language
* [gruntwork-io/terratest](https://github.com/gruntwork-io/terratest) -  Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.
* [golang/tools](https://github.com/golang/tools) - [mirror] Go Tools
* [adonovan/gopl.io](https://github.com/adonovan/gopl.io) - Example programs from "The Go Programming Language"
* [maxence-charriere/go-app](https://github.com/maxence-charriere/go-app) - A package to build progressive web apps with Go programming language and WebAssembly.
* [ffuf/ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go
* [hajimehoshi/ebiten](https://github.com/hajimehoshi/ebiten) - A dead simple 2D game library for Go
* [securego/gosec](https://github.com/securego/gosec) - Golang security checker
* [patrickmn/go-cache](https://github.com/patrickmn/go-cache) - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [vmware-tanzu/octant](https://github.com/vmware-tanzu/octant) - Highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
* [GoAdminGroup/go-admin](https://github.com/GoAdminGroup/go-admin) - A golang framework helps gopher to build a data visualization and admin panel in ten minutes
* [tools/godep](https://github.com/tools/godep) - dependency tool for go
* [go-admin-team/go-admin](https://github.com/go-admin-team/go-admin) - 基于Gin + Vue + Element UI的前后端分离权限管理系统脚手架（包含了：多租户的支持，基础用户管理功能，jwt鉴权，代码生成器，RBAC资源控制，表单构建，定时任务等）3分钟构建自己的中后台项目；文档：https://doc.go-admin.dev   Demo： https://www.go-admin.dev Antd beta版本：https://preview.go-admin.dev
* [kubernetes/client-go](https://github.com/kubernetes/client-go) - Go client for Kubernetes.
* [cosmtrek/air](https://github.com/cosmtrek/air) - ☁️ Live reload for Go apps
* [wailsapp/wails](https://github.com/wailsapp/wails) - Create desktop apps using Go and Web Technologies.
* [go-resty/resty](https://github.com/go-resty/resty) - Simple HTTP and REST client library for Go
* [google/gops](https://github.com/google/gops) - A tool to list and diagnose Go processes currently running on your system
* [twitchtv/twirp](https://github.com/twitchtv/twirp) - A simple RPC framework with protobuf service definitions
* [gonum/gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more
* [mindoc-org/mindoc](https://github.com/mindoc-org/mindoc) - Golang实现的基于beego框架的接口在线文档管理系统
* [OJ/gobuster](https://github.com/OJ/gobuster) - Directory/File, DNS and VHost busting tool written in Go
* [onsi/ginkgo](https://github.com/onsi/ginkgo) - A Modern Testing Framework for Go
* [ponzu-cms/ponzu](https://github.com/ponzu-cms/ponzu) - Headless CMS with automatic JSON API. Featuring auto-HTTPS from Let's Encrypt, HTTP/2 Server Push, and flexible server framework written in Go.
* [allegro/bigcache](https://github.com/allegro/bigcache) - Efficient cache for gigabytes of data written in Go.
* [go-yaml/yaml](https://github.com/go-yaml/yaml) - YAML support for the Go language.
* [pachyderm/pachyderm](https://github.com/pachyderm/pachyderm) - Reproducible Data Science at Scale!
* [mmcgrana/gobyexample](https://github.com/mmcgrana/gobyexample) - Go by Example
* [mitchellh/mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures and vice versa.
* [swaggo/swag](https://github.com/swaggo/swag) - Automatically generate RESTful API documentation with Swagger 2.0 for Go.
* [tealeg/xlsx](https://github.com/tealeg/xlsx) - Go (golang) library for reading and writing XLSX files.
* [EasyDarwin/EasyDarwin](https://github.com/EasyDarwin/EasyDarwin) - open source、high performance、industrial rtsp streaming server,a lot of optimization on streaming relay,KeyFrame cache,RESTful,and web management,also EasyDarwin support distributed load balancing,a simple streaming media cloud platform architecture.高性能开源RTSP流媒体服务器，基于go语言研发，维护和优化：RTSP推模式转发、RTSP拉模式转发、录像、检索、回放、关键帧缓存、秒开画面、RESTful接口、WEB后台管理、分布式负载均衡，基于EasyDarwin构建出了一套基础的流媒体云视频平台架构！
* [asaskevich/govalidator](https://github.com/asaskevich/govalidator) - [Go] Package of validators and sanitizers for strings, numerics, slices and structs
* [tidwall/evio](https://github.com/tidwall/evio) - Fast event-loop networking for Go
* [bxcodec/go-clean-arch](https://github.com/bxcodec/go-clean-arch) - Go (Golang) Clean Architecture based on Reading Uncle Bob's Clean Architecture
* [go-flutter-desktop/go-flutter](https://github.com/go-flutter-desktop/go-flutter) - Flutter on Windows, MacOS and Linux - based on Flutter Embedding, Go and GLFW.
* [goproxyio/goproxy](https://github.com/goproxyio/goproxy) - A global proxy for Go modules.
* [zhenghaoz/gorse](https://github.com/zhenghaoz/gorse) - An open source recommender system service written in Go
* [eddycjy/go-gin-example](https://github.com/eddycjy/go-gin-example) - An example of gin
* [gogo/protobuf](https://github.com/gogo/protobuf) - [Looking for new ownership] Protocol Buffers for Go with Gadgets
* [go-acme/lego](https://github.com/go-acme/lego) - Let's Encrypt client and ACME library written in Go
* [kardianos/govendor](https://github.com/kardianos/govendor) - Use Go Modules.
* [src-d/go-git](https://github.com/src-d/go-git) - Project has been moved to: https://github.com/go-git/go-git
* [fogleman/nes](https://github.com/fogleman/nes) - NES emulator written in Go.
* [eranyanay/1m-go-websockets](https://github.com/eranyanay/1m-go-websockets) - handling 1M websockets connections in Go
* [go-pg/pg](https://github.com/go-pg/pg) - Golang ORM with focus on PostgreSQL features and performance
* [fatih/color](https://github.com/fatih/color) - Color package for Go (golang)
* [nsf/gocode](https://github.com/nsf/gocode) - An autocompletion daemon for the Go programming language
* [qor/qor](https://github.com/qor/qor) - QOR is a set of libraries written in Go that abstracts common features needed for business applications, CMSs, and E-commerce systems.
* [jackc/pgx](https://github.com/jackc/pgx) - PostgreSQL driver and toolkit for Go
* [russross/blackfriday](https://github.com/russross/blackfriday) - Blackfriday: a markdown processor for Go
* [MontFerret/ferret](https://github.com/MontFerret/ferret) - Declarative web scraping
* [syndtr/goleveldb](https://github.com/syndtr/goleveldb) - LevelDB key/value database in Go.
* [fiorix/freegeoip](https://github.com/fiorix/freegeoip) - IP geolocation web server
* [golang/mobile](https://github.com/golang/mobile) - [mirror] Go on Mobile
* [davecgh/go-spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging
* [facebookarchive/grace](https://github.com/facebookarchive/grace) - Graceful restart & zero downtime deploy for Go servers.
* [rakyll/boom](https://github.com/rakyll/boom) - HTTP(S) load generator, ApacheBench (ab) replacement, written in Go
* [kyleconroy/sqlc](https://github.com/kyleconroy/sqlc) - Generate type-safe code from SQL
* [reviewdog/reviewdog](https://github.com/reviewdog/reviewdog) - 🐶 Automated code review tool integrated with any code analysis tools regardless of programming language
* [btcsuite/btcd](https://github.com/btcsuite/btcd) - An alternative full node bitcoin implementation written in Go (golang)
* [elves/elvish](https://github.com/elves/elvish) - Elvish = Expressive Programming Language + Versatile Interactive Shell
* [google/gopacket](https://github.com/google/gopacket) - Provides packet processing capabilities for Go
* [moby/buildkit](https://github.com/moby/buildkit) - concurrent, cache-efficient, and Dockerfile-agnostic builder toolkit
* [aelsabbahy/goss](https://github.com/aelsabbahy/goss) - Quick and Easy server testing/validation
* [gaia-pipeline/gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
* [elazarl/goproxy](https://github.com/elazarl/goproxy) - An HTTP proxy library for Go
* [hybridgroup/gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 4 and beyond.
* [volatiletech/sqlboiler](https://github.com/volatiletech/sqlboiler) - Generate a Go ORM tailored to your database schema.
* [tendermint/tendermint](https://github.com/tendermint/tendermint) - ⟁ Tendermint Core (BFT Consensus) in Go
* [goadesign/goa](https://github.com/goadesign/goa) - Design-based APIs and microservices in Go
* [yuin/gopher-lua](https://github.com/yuin/gopher-lua) - GopherLua: VM and compiler for Lua in Go
* [alibaba/pouch](https://github.com/alibaba/pouch) - An Efficient Enterprise-class Container Engine
* [travisjeffery/jocko](https://github.com/travisjeffery/jocko) - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native)
* [satori/go.uuid](https://github.com/satori/go.uuid) - UUID package for Go
* [google/gxui](https://github.com/google/gxui) - An experimental Go cross platform UI library.
* [googollee/go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [joho/godotenv](https://github.com/joho/godotenv) - A Go port of Ruby's dotenv library (Loads environment variables from `.env`.)
* [dtm-labs/dtm](https://github.com/dtm-labs/dtm) - 🔥A cross-language distributed transaction manager. Support xa, tcc, saga, transactional messages.  跨语言分布式事务管理器
* [gopasspw/gopass](https://github.com/gopasspw/gopass) - The slightly more awesome standard unix password manager for teams
* [go-task/task](https://github.com/go-task/task) - A task runner / simpler Make alternative written in Go
* [mvdan/sh](https://github.com/mvdan/sh) - A shell parser, formatter, and interpreter with bash support; includes shfmt
* [buger/jsonparser](https://github.com/buger/jsonparser) - One of the fastest alternative JSON parser for Go that does not require schema
* [x-motemen/gore](https://github.com/x-motemen/gore) -   Yet another Go REPL that works nicely. Featured with line editing, code completion, and more.
* [tophubs/TopList](https://github.com/tophubs/TopList) - 今日热榜，一个获取各大热门网站热门头条的聚合网站，使用Go语言编写，多协程异步快速抓取信息，预览:https://mo.fish
* [dominikh/go-tools](https://github.com/dominikh/go-tools) - Staticcheck - The advanced Go linter
* [emicklei/go-restful](https://github.com/emicklei/go-restful) - package for building REST-style Web Services using Go
* [gorgonia/gorgonia](https://github.com/gorgonia/gorgonia) - Gorgonia is a library that helps facilitate machine learning in Go.
* [gobwas/ws](https://github.com/gobwas/ws) - Tiny WebSocket library for Go.
* [go-echarts/go-echarts](https://github.com/go-echarts/go-echarts) - 🎨 The adorable charts library for Golang
* [coyove/goflyway](https://github.com/coyove/goflyway) - An encrypted HTTP server
* [googleforgames/agones](https://github.com/googleforgames/agones) - Dedicated Game Server Hosting and Scaling for Multiplayer Games on Kubernetes
* [runatlantis/atlantis](https://github.com/runatlantis/atlantis) - Terraform Pull Request Automation
* [c-bata/go-prompt](https://github.com/c-bata/go-prompt) - Building powerful interactive prompts in Go, inspired by python-prompt-toolkit.
* [vugu/vugu](https://github.com/vugu/vugu) - Vugu: A modern UI library for Go+WebAssembly (experimental)
* [aceld/zinx](https://github.com/aceld/zinx) - 基于Golang轻量级TCP并发服务器框架
* [name5566/leaf](https://github.com/name5566/leaf) - A game server framework in Go (golang)
* [segmentio/kafka-go](https://github.com/segmentio/kafka-go) - Kafka library in Go
* [nuclio/nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform
* [dvyukov/go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing for Go
* [ouqiang/gocron](https://github.com/ouqiang/gocron) - 定时任务管理系统
* [jwilder/dockerize](https://github.com/jwilder/dockerize) - Utility to simplify running applications in docker containers
* [nsf/termbox-go](https://github.com/nsf/termbox-go) - Pure Go termbox implementation
* [grpc-ecosystem/go-grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware) - Golang gRPC Middlewares: interceptor chaining, auth, logging, retries and more.
* [streadway/amqp](https://github.com/streadway/amqp) - Go client for AMQP 0.9.1
* [oxequa/realize](https://github.com/oxequa/realize) - Realize is the #1 Golang Task Runner which enhance your workflow by automating the most common tasks and using the best performing Golang live reloading.
* [asticode/go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron)
* [mitchellh/gox](https://github.com/mitchellh/gox) - A dead simple, no frills Go cross compile tool
* [megaease/easegress](https://github.com/megaease/easegress) - A Cloud Native traffic orchestration system
* [anacrolix/torrent](https://github.com/anacrolix/torrent) - Full-featured BitTorrent client package and utilities
* [ffhelicopter/Go42](https://github.com/ffhelicopter/Go42) - 《Go语言四十二章经》详细讲述Go语言规范与语法细节及开发中常见的误区，通过研读标准库等经典代码设计模式，启发读者深刻理解Go语言的核心思维，进入Go语言开发的更高阶段。
* [libp2p/go-libp2p](https://github.com/libp2p/go-libp2p) - libp2p implementation in Go
* [spf13/afero](https://github.com/spf13/afero) - A FileSystem Abstraction System for Go
* [letsencrypt/boulder](https://github.com/letsencrypt/boulder) - An ACME-based certificate authority, written in Go.
* [p4gefau1t/trojan-go](https://github.com/p4gefau1t/trojan-go) - Go实现的Trojan代理，支持多路复用/路由功能/CDN中转/Shadowsocks混淆插件，多平台，无依赖。A Trojan proxy written in Go. An unidentifiable mechanism that helps you bypass GFW. https://p4gefau1t.github.io/trojan-go/
* [chai2010/go-ast-book](https://github.com/chai2010/go-ast-book) - :books: 《Go语法树入门——开启自制编程语言和编译器之旅》(开源免费图书/Go语言进阶/掌握抽象语法树/Go语言AST/凹语言)
* [alexellis/k3sup](https://github.com/alexellis/k3sup) - bootstrap Kubernetes with k3s over SSH < 1 min 🚀
* [traefik/yaegi](https://github.com/traefik/yaegi) - Yaegi is Another Elegant Go Interpreter
* [ConsenSys/quorum](https://github.com/ConsenSys/quorum) - A permissioned implementation of Ethereum supporting data privacy
* [DATA-DOG/go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Sql mock driver for golang to test database interactions
* [disintegration/imaging](https://github.com/disintegration/imaging) - Imaging is a simple image processing package for Go
* [OWASP/Go-SCP](https://github.com/OWASP/Go-SCP) - Go programming language secure coding practices guide
* [lni/dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* [graph-gophers/graphql-go](https://github.com/graph-gophers/graphql-go) - GraphQL server with a focus on ease of use
* [dropbox/godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications.
* [golang/oauth2](https://github.com/golang/oauth2) - Go OAuth2
* [asynkron/protoactor-go](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin
* [kahing/goofys](https://github.com/kahing/goofys) - a high-performance, POSIX-ish Amazon S3 file system written in Go
* [nginx-proxy/docker-gen](https://github.com/nginx-proxy/docker-gen) - Generate files from docker container meta-data
* [ReactiveX/RxGo](https://github.com/ReactiveX/RxGo) - Reactive Extensions for the Go language.
* [golang/lint](https://github.com/golang/lint) - [mirror] This is a linter for Go source code. (deprecated)
* [jung-kurt/gofpdf](https://github.com/jung-kurt/gofpdf) - A PDF document generator with high level support for text, drawing and images
* [tianon/gosu](https://github.com/tianon/gosu) - Simple Go-based setuid+setgid+setgroups+exec
* [uber-archive/go-torch](https://github.com/uber-archive/go-torch) - Stochastic flame graph profiler for Go programs
* [caddyserver/certmagic](https://github.com/caddyserver/certmagic) - Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal
* [Jeffail/benthos](https://github.com/Jeffail/benthos) - Fancy stream processing made operationally mundane
* [elastic/go-elasticsearch](https://github.com/elastic/go-elasticsearch) - The official Go client for Elasticsearch
* [google/ko](https://github.com/google/ko) - Build and deploy Go applications on Kubernetes
* [rgburke/grv](https://github.com/rgburke/grv) - GRV is a terminal interface for viewing git repositories
* [codegangsta/gin](https://github.com/codegangsta/gin) - Live reload utility for Go web servers
* [apache/dubbo-go](https://github.com/apache/dubbo-go) - Go Implementation For Apache Dubbo
* [ledisdb/ledisdb](https://github.com/ledisdb/ledisdb) - A high performance NoSQL Database Server powered by Go
* [variadico/noti](https://github.com/variadico/noti) - Monitor a process and trigger a notification.
* [tsuru/tsuru](https://github.com/tsuru/tsuru) - Open source and extensible Platform as a Service (PaaS).
* [faiface/pixel](https://github.com/faiface/pixel) - A hand-crafted 2D game library in Go
* [slack-go/slack](https://github.com/slack-go/slack) - Slack API in Go - community-maintained fork created by the original author, @nlopes
* [gomods/athens](https://github.com/gomods/athens) - A Go module datastore and proxy
* [smallstep/certificates](https://github.com/smallstep/certificates) - 🛡️ A private certificate authority (X.509 & SSH) & ACME server for secure automated certificate management, so you can use TLS everywhere & SSO for SSH.
* [ofabry/go-callvis](https://github.com/ofabry/go-callvis) - Visualize call graph of a Go program using Graphviz
* [nats-io/nats.go](https://github.com/nats-io/nats.go) - Golang client for NATS, the cloud native messaging system.
* [alexflint/gallium](https://github.com/alexflint/gallium) - Build desktop applications in Go and HTML.
* [go-mysql-org/go-mysql-elasticsearch](https://github.com/go-mysql-org/go-mysql-elasticsearch) - Sync MySQL data into elasticsearch
* [RH12503/triangula](https://github.com/RH12503/triangula) - Generate high-quality triangulated and polygonal art from images.
* [shopspring/decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers in go
* [coocood/freecache](https://github.com/coocood/freecache) - A cache library for Go with zero GC overhead.
* [zenazn/goji](https://github.com/zenazn/goji) - Goji is a minimalistic web framework for Golang that's high in antioxidants.
* [dgraph-io/ristretto](https://github.com/dgraph-io/ristretto) - A high performance memory-bound Go cache
* [cweill/gotests](https://github.com/cweill/gotests) - Automatically generate Go test boilerplate from your source code.
* [tidwall/buntdb](https://github.com/tidwall/buntdb) - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support
* [drakkan/sftpgo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional HTTP, FTP/S and WebDAV support - S3, Google Cloud Storage, Azure Blob
* [shomali11/go-interview](https://github.com/shomali11/go-interview) - Collection of Technical Interview Questions solved with Go
* [ThreeDotsLabs/watermill](https://github.com/ThreeDotsLabs/watermill) - Building event-driven applications the easy way in Go.
* [progrium/macdriver](https://github.com/progrium/macdriver) - Native Mac APIs for Go
* [nytimes/gizmo](https://github.com/nytimes/gizmo) - A Microservice Toolkit from The New York Times
* [prometheus/client_golang](https://github.com/prometheus/client_golang) - Prometheus instrumentation library for Go applications
* [Mrs4s/go-cqhttp](https://github.com/Mrs4s/go-cqhttp) - cqhttp的golang实现，轻量、原生跨平台.
* [hoisie/web](https://github.com/hoisie/web) - The easiest way to create web applications with Go
* [esimov/pigo](https://github.com/esimov/pigo) - Fast face detection, pupil/eyes localization and facial landmark points detection library in pure Go.
* [alecthomas/gometalinter](https://github.com/alecthomas/gometalinter) - DEPRECATED: Use https://github.com/golangci/golangci-lint
* [go-gorp/gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence - an ORM-ish library for Go
* [nginxinc/kubernetes-ingress](https://github.com/nginxinc/kubernetes-ingress) - NGINX and  NGINX Plus Ingress Controllers for Kubernetes
* [bitly/go-simplejson](https://github.com/bitly/go-simplejson) - a Go package to interact with arbitrary JSON
* [overnote/over-golang](https://github.com/overnote/over-golang) - Golang相关：[审稿进度80%]Go语法、Go并发思想、Go与web开发、Go微服务设施等
* [jinzhu/now](https://github.com/jinzhu/now) - Now is a time toolkit for golang
* [goinaction/code](https://github.com/goinaction/code) - Source Code for Go In Action examples
* [afex/hystrix-go](https://github.com/afex/hystrix-go) - Netflix's Hystrix latency and fault tolerance library, for Go
* [ant0ine/go-json-rest](https://github.com/ant0ine/go-json-rest) - A quick and easy way to setup a RESTful JSON API
* [douyu/jupiter](https://github.com/douyu/jupiter) - Jupiter是斗鱼开源的面向服务治理的Golang微服务框架
* [gomatcha/matcha](https://github.com/gomatcha/matcha) - Build native mobile apps in Go.
* [charmbracelet/lipgloss](https://github.com/charmbracelet/lipgloss) - Style definitions for nice terminal layouts 👄
* [markbates/goth](https://github.com/markbates/goth) - Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications.
* [anthonynsimon/bild](https://github.com/anthonynsimon/bild) - Image processing algorithms in pure Go
* [go-gomail/gomail](https://github.com/go-gomail/gomail) - The best way to send emails in Go.
* [golang-design/under-the-hood](https://github.com/golang-design/under-the-hood) - 📚 Go: Under The Hood | Go 语言原本 | https://golang.design/under-the-hood
* [fatih/structs](https://github.com/fatih/structs) - Utilities for Go structs
* [golang-design/Go-Questions](https://github.com/golang-design/Go-Questions) - 📖 从问题切入，串连  Go 语言相关的所有知识，融会贯通。 https://golang.design/go-questions
* [ksimka/go-is-not-good](https://github.com/ksimka/go-is-not-good) - A curated list of articles complaining that go (golang) isn't good enough
* [DisposaBoy/GoSublime](https://github.com/DisposaBoy/GoSublime) - A Golang plugin collection for SublimeText 3, providing code completion and other IDE-like features.
* [go-mysql-org/go-mysql](https://github.com/go-mysql-org/go-mysql) - a powerful mysql toolset with Go
* [astaxie/go-best-practice](https://github.com/astaxie/go-best-practice) - Trying to complete over 100 projects in various categories in golang.
* [zxh0/jvm.go](https://github.com/zxh0/jvm.go) - A toy JVM written in Go
* [fvbock/endless](https://github.com/fvbock/endless) - Zero downtime restarts for go servers (Drop in replacement for http.ListenAndServe)
* [rakyll/statik](https://github.com/rakyll/statik) - Embed files into a Go executable
* [knqyf263/pet](https://github.com/knqyf263/pet) - Simple command-line snippet manager, written in Go.
* [gotenberg/gotenberg](https://github.com/gotenberg/gotenberg) - A Docker-powered stateless API for PDF files.
* [gobuffalo/packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* [pion/ion](https://github.com/pion/ion) - Real-Distributed  RTC System by pure Go and Flutter
* [goby-lang/goby](https://github.com/goby-lang/goby) - Goby - Yet another programming language written in Go
* [blushft/go-diagrams](https://github.com/blushft/go-diagrams) - Create beautiful system diagrams with Go
* [mpolden/echoip](https://github.com/mpolden/echoip) - IP address lookup service
* [google/uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
* [opentracing/opentracing-go](https://github.com/opentracing/opentracing-go) - OpenTracing API for Go
* [wcharczuk/go-chart](https://github.com/wcharczuk/go-chart) - go chart is a basic charting library in go.
* [miniflux/v2](https://github.com/miniflux/v2) - Minimalist and opinionated feed reader
* [gravityblast/fresh](https://github.com/gravityblast/fresh) - Build and (re)start go web apps after saving/creating/deleting source files.
* [go-macaron/macaron](https://github.com/go-macaron/macaron) - Package macaron is a high productive and modular web framework in Go.
* [derailed/popeye](https://github.com/derailed/popeye) - 👀 A Kubernetes cluster resource sanitizer
* [bosun-monitor/bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework
* [kylesliu/awesome-golang-algorithm](https://github.com/kylesliu/awesome-golang-algorithm) - :memo: LeetCode of algorithms with golang solution(updating).
* [segmentio/ksuid](https://github.com/segmentio/ksuid) - K-Sortable Globally Unique IDs
* [hashicorp/go-plugin](https://github.com/hashicorp/go-plugin) - Golang plugin system over RPC.
* [ddosify/ddosify](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang.
* [fogleman/gg](https://github.com/fogleman/gg) - Go Graphics - 2D rendering in Go with a simple API.
* [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) - :chains: A Framework for Building High Value Public Blockchains :sparkles:
* [kardianos/service](https://github.com/kardianos/service) - Run go programs as a service on major platforms.
* [xtaci/kcp-go](https://github.com/xtaci/kcp-go) -  A Crypto-Secure, Production-Grade Reliable-UDP Library for golang with FEC
* [alecthomas/kingpin](https://github.com/alecthomas/kingpin) - CONTRIBUTIONS ONLY: A Go (golang) command line and flag parser
* [Jeiwan/blockchain_go](https://github.com/Jeiwan/blockchain_go) - A simplified blockchain implementation in Golang
* [silenceper/wechat](https://github.com/silenceper/wechat) - WeChat SDK for Go （微信SDK：简单、易用）
* [mgechev/revive](https://github.com/mgechev/revive) - 🔥 ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for golint
* [vektra/mockery](https://github.com/vektra/mockery) - A mock code autogenerator for Golang
* [rcrowley/go-metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library
* [GoogleCloudPlatform/golang-samples](https://github.com/GoogleCloudPlatform/golang-samples) - Sample apps and code written for Google Cloud in the Go programming language.
* [hoanhan101/algo](https://github.com/hoanhan101/algo) - 101+ coding interview problems in Go
* [lxc/lxd](https://github.com/lxc/lxd) - Powerful system container and virtual machine manager
* [emitter-io/emitter](https://github.com/emitter-io/emitter) - High performance, distributed and low latency publish-subscribe platform.
* [unidoc/unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents
* [olivia-ai/olivia](https://github.com/olivia-ai/olivia) - 💁‍♀️Your new best friend powered by an artificial neural network
* [rancher/k3d](https://github.com/rancher/k3d) - Little helper to run Rancher Lab's k3s in Docker
* [gopherdata/gophernotes](https://github.com/gopherdata/gophernotes) - The Go kernel for Jupyter notebooks and nteract.
* [thoas/go-funk](https://github.com/thoas/go-funk) - A modern Go utility library which provides helpers (map, find, contains, filter, ...)
* [XIU2/CloudflareSpeedTest](https://github.com/XIU2/CloudflareSpeedTest) - 🌩「自选优选 IP / 过滤假墙」测试 Cloudflare CDN 延迟和速度，获取最快 IP (IPv4+IPv6)！
* [koding/kite](https://github.com/koding/kite) - Micro-service framework in Go
* [wader/fq](https://github.com/wader/fq) - jq for binary formats
* [cheggaaa/pb](https://github.com/cheggaaa/pb) - Console progress bar for Golang
* [golang/glog](https://github.com/golang/glog) - Leveled execution logs for Go
* [confluentinc/confluent-kafka-go](https://github.com/confluentinc/confluent-kafka-go) - Confluent's Apache Kafka Golang client
* [nakabonne/ali](https://github.com/nakabonne/ali) - Generate HTTP load and plot the results in real-time
* [parnurzeal/gorequest](https://github.com/parnurzeal/gorequest) - GoRequest -- Simplified HTTP client ( inspired by nodejs SuperAgent )
* [prest/prest](https://github.com/prest/prest) - PostgreSQL ➕ REST, low-code, simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new
* [google/mtail](https://github.com/google/mtail) - extract internal monitoring data from application logs for collection in a timeseries database
* [alecthomas/chroma](https://github.com/alecthomas/chroma) - A general purpose syntax highlighter in pure Go
* [chrislusf/glow](https://github.com/chrislusf/glow) - Glow is an easy-to-use distributed computation system written in Go, similar to Hadoop Map Reduce, Spark, Flink, Storm, etc. I am also working on another similar pure Go system, https://github.com/chrislusf/gleam , which is more flexible and more performant.
* [fagongzi/manba](https://github.com/fagongzi/manba) - HTTP API Gateway
* [natefinch/lumberjack](https://github.com/natefinch/lumberjack) - lumberjack is a log rolling package for Go
* [dustin/go-humanize](https://github.com/dustin/go-humanize) - Go Humans! (formatters for units to human friendly sizes)
* [ory/keto](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
* [boyter/scc](https://github.com/boyter/scc) - Sloc, Cloc and Code: scc is a very fast accurate code counter with complexity calculations and COCOMO estimates written in pure Go
* [xo/xo](https://github.com/xo/xo) - Command line tool to generate idiomatic Go code for SQL databases supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server
* [maruel/panicparse](https://github.com/maruel/panicparse) - Crash your app in style (Golang)
* [codesenberg/bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in Go
* [cointop-sh/cointop](https://github.com/cointop-sh/cointop) - A fast and lightweight interactive terminal based UI application for tracking cryptocurrencies 🚀
* [chrislusf/gleam](https://github.com/chrislusf/gleam) - Fast, efficient, and scalable distributed map/reduce system, DAG execution, in memory or on disk, written in pure Go, runs standalone or distributedly.
* [qax-os/goreporter](https://github.com/qax-os/goreporter) - A Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [sjqzhang/go-fastdfs](https://github.com/sjqzhang/go-fastdfs) - go-fastdfs 是一个简单的分布式文件系统(私有云存储)，具有无中心、高性能，高可靠，免维护等优点，支持断点续传，分块上传，小文件合并，自动同步，自动修复。Go-fastdfs is a simple distributed file system (private cloud storage), with no center, high performance, high reliability, maintenance free and other advantages, support breakpoint continuation, block upload, small file merge, automatic synchronization, automatic repair.(similar fastdfs).
* [TarsCloud/TarsGo](https://github.com/TarsCloud/TarsGo) - A  high performance microservice  framework  in golang. A linux foundation project.
* [thewhitetulip/web-dev-golang-anti-textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook) - Learn how to write webapps without a framework in Go.
* [go-git/go-git](https://github.com/go-git/go-git) - A highly extensible Git implementation in pure Go.
* [hantmac/Mastering_Go_ZH_CN](https://github.com/hantmac/Mastering_Go_ZH_CN) - 《Mastering GO》中文译本，《玩转 GO》。
* [pdfcpu/pdfcpu](https://github.com/pdfcpu/pdfcpu) - A PDF processor written in Go.
* [rudderlabs/rudder-server](https://github.com/rudderlabs/rudder-server) - Privacy and Security focused Segment-alternative, in Golang and React
* [pomerium/pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
* [googleapis/google-api-go-client](https://github.com/googleapis/google-api-go-client) - Auto-generated Google APIs for Go.
* [werf/werf](https://github.com/werf/werf) - The CLI tool gluing Git, Docker, Helm, and Kubernetes with any CI system to implement CI/CD and Giterminism
* [upper/db](https://github.com/upper/db) - Data access layer for PostgreSQL, CockroachDB, MySQL, SQLite and MongoDB with ORM-like features.
* [olebedev/go-starter-kit](https://github.com/olebedev/go-starter-kit) - [abandoned] Golang isomorphic react/hot reloadable/redux/css-modules/SSR  starter kit
* [buzzfeed/sso](https://github.com/buzzfeed/sso) - sso, aka S.S.Octopus, aka octoboi, is a single sign-on solution for securing internal services
* [aws/aws-lambda-go](https://github.com/aws/aws-lambda-go) - Libraries, samples and tools to help Go developers develop AWS Lambda functions.
* [tdewolff/minify](https://github.com/tdewolff/minify) - Go minifiers for web formats
* [xinliangnote/go-gin-api](https://github.com/xinliangnote/go-gin-api) - 基于 Gin 进行模块化设计的 API 框架，封装了常用功能，使用简单，致力于进行快速的业务研发。比如，支持 cors 跨域、jwt 签名验证、zap 日志收集、panic 异常捕获、trace 链路追踪、prometheus 监控指标、swagger 文档生成、viper 配置文件解析、gorm 数据库组件、gormgen 代码生成工具、graphql 查询语言、errno 统一定义错误码、gRPC 的使用、cron 定时任务 等等。
* [aQuaYi/LeetCode-in-Go](https://github.com/aQuaYi/LeetCode-in-Go) - Go Solution for LeetCode algorithms problems, 100% coverage.
* [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron) - A Golang Job Scheduling Package.
* [gopl-zh/gopl-zh.github.com](https://github.com/gopl-zh/gopl-zh.github.com) - Go语言圣经中文版(只接收PR, Issue请提交到golang-china/gopl-zh)
* [ahmetb/go-linq](https://github.com/ahmetb/go-linq) - .NET LINQ capabilities in Go
* [pquerna/ffjson](https://github.com/pquerna/ffjson) - faster JSON serialization for Go
* [go-ini/ini](https://github.com/go-ini/ini) - Package ini provides INI file read and write functionality in Go
* [matrix-org/dendrite](https://github.com/matrix-org/dendrite) - Dendrite is a second-generation Matrix homeserver written in Go!
* [mmatczuk/go-http-tunnel](https://github.com/mmatczuk/go-http-tunnel) - Fast and secure tunnels over HTTP/2
* [magefile/mage](https://github.com/magefile/mage) - a Make/rake-like dev tool using Go
* [Jeffail/tunny](https://github.com/Jeffail/tunny) - A goroutine pool for Go
* [eolinker/goku_lite](https://github.com/eolinker/goku_lite) - A Powerful HTTP API Gateway in pure golang！Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang开发的微服务网关，能够实现高性能 HTTP API 转发、服务编排、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。
* [d4l3k/go-pry](https://github.com/d4l3k/go-pry) - An interactive REPL for Go that allows you to drop into your code at any point.
* [nfnt/resize](https://github.com/nfnt/resize) - Pure golang image resizing
* [golang/proposal](https://github.com/golang/proposal) - Go Project Design Documents
* [miguelmota/golang-for-nodejs-developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning
* [Masterminds/sprig](https://github.com/Masterminds/sprig) - Useful template functions for Go templates.
* [googleapis/google-cloud-go](https://github.com/googleapis/google-cloud-go) - Google Cloud Client Libraries for Go.
* [bouk/monkey](https://github.com/bouk/monkey) - Monkey patching in Go
* [purpleidea/mgmt](https://github.com/purpleidea/mgmt) - Next generation distributed, event-driven, parallel config management!
* [mergestat/mergestat](https://github.com/mergestat/mergestat) - Query git repositories with SQL. Generate reports, perform status checks, analyze codebases. 🔍 📊
* [campoy/go-tooling-workshop](https://github.com/campoy/go-tooling-workshop) - A workshop covering all the tools gophers use in their day to day life
* [willnorris/imageproxy](https://github.com/willnorris/imageproxy) - A caching, resizing image proxy written in Go
* [go-mgo/mgo](https://github.com/go-mgo/mgo) - The MongoDB driver for Go. UNMAINTAINED - SEE BELOW
* [orcaman/concurrent-map](https://github.com/orcaman/concurrent-map) - a thread-safe concurrent map for go
* [HouzuoGuo/tiedot](https://github.com/HouzuoGuo/tiedot) - A rudimentary implementation of a basic document (NoSQL) database in Go
* [geektutu/high-performance-go](https://github.com/geektutu/high-performance-go) - high performance coding with golang（Go 语言高性能编程，Go 语言陷阱，Gotchas，Traps）
* [unknwon/go-web-foundation](https://github.com/unknwon/go-web-foundation) - 《Go Web 基础》是一套针对 Google 出品的 Go 语言的视频语音教程，主要面向完成《Go 编程基础》教程后希望进一步了解有关 Go Web 开发的学习者。
* [google/go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests
* [benmanns/goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker that runs 10 to 100,000* times faster than Ruby-based workers.
* [zalando/skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress
* [bwmarrin/discordgo](https://github.com/bwmarrin/discordgo) -  (Golang) Go bindings for Discord
* [0xDkd/auxpi](https://github.com/0xDkd/auxpi) - 🍭 集合多家 API 的新一代图床
* [hashicorp/golang-lru](https://github.com/hashicorp/golang-lru) - Golang LRU cache
* [monkeyWie/gopeed-core](https://github.com/monkeyWie/gopeed-core) - A fast download client,support HTTP&P2P.
* [dop251/goja](https://github.com/dop251/goja) - ECMAScript/JavaScript engine in pure Go
* [google/google-ctf](https://github.com/google/google-ctf) - Google CTF
* [Jeffail/gabs](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go
* [jinzhu/copier](https://github.com/jinzhu/copier) - Copier for golang, copy value from struct to struct and more
* [cube2222/octosql](https://github.com/cube2222/octosql) - OctoSQL is a query tool that allows you to join, analyse and transform data from multiple databases and file formats using SQL.
* [sideshow/apns2](https://github.com/sideshow/apns2) - ⚡ HTTP/2 Apple Push Notification Service (APNs) push provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps, using the APNs HTTP/2 protocol.
* [egonelbre/gophers](https://github.com/egonelbre/gophers) - Free gophers
* [d5/tengo](https://github.com/d5/tengo) - A fast script language for Go
* [mikespook/Learning-Go-zh-cn](https://github.com/mikespook/Learning-Go-zh-cn) - 一本学习 Go 语言的免费电子书。
* [ashleymcnamara/gophers](https://github.com/ashleymcnamara/gophers) - Gopher Artwork by Ashley McNamara
* [ochinchina/supervisord](https://github.com/ochinchina/supervisord) - a go-lang supervisor implementation
* [wxbool/video-srt-windows](https://github.com/wxbool/video-srt-windows) - 这是一个可以识别视频语音自动生成字幕SRT文件的开源 Windows-GUI 软件工具。
* [mailgun/godebug](https://github.com/mailgun/godebug) - DEPRECATED! https://github.com/derekparker/delve
* [lifei6671/interview-go](https://github.com/lifei6671/interview-go) - golang面试题集合
* [netlify/gotrue](https://github.com/netlify/gotrue) - An SWT based API for managing users and issuing SWT tokens
* [anchore/grype](https://github.com/anchore/grype) - A vulnerability scanner for container images and filesystems
* [writefreely/writefreely](https://github.com/writefreely/writefreely) - A clean, Markdown-based publishing platform made for writers. Write together, and build a community.
* [go-ozzo/ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - An idiomatic Go (golang) validation package. Supports configurable and extensible validation rules (validators) using normal language constructs instead of error-prone struct tags.
* [shunfei/cronsun](https://github.com/shunfei/cronsun) - A Distributed, Fault-Tolerant Cron-Style Job System.
* [gpmgo/gopm](https://github.com/gpmgo/gopm) - Go Package Manager (gopm) is a package manager and build tool for Go.
* [encoredev/encore](https://github.com/encoredev/encore) - The Backend Development Engine built for Go
* [lbryio/chainquery](https://github.com/lbryio/chainquery) - Chainquery parses and syncs the LBRY blockchain data into structured SQL
* [klauspost/compress](https://github.com/klauspost/compress) - Optimized Go Compression Packages
* [google/btree](https://github.com/google/btree) - BTree provides a simple, ordered, in-memory data structure for Go programs.
* [oklog/ulid](https://github.com/oklog/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID) in Go
* [golang/net](https://github.com/golang/net) - [mirror] Go supplementary network libraries
* [shiyanhui/dht](https://github.com/shiyanhui/dht) - BitTorrent DHT Protocol && DHT Spider.
* [darjun/go-daily-lib](https://github.com/darjun/go-daily-lib) - Go 每日一库
* [ory/oathkeeper](https://github.com/ory/oathkeeper) - A cloud native Identity & Access Proxy / API (IAP) and Access Control Decision API that authenticates, authorizes, and mutates incoming HTTP(s) requests. Inspired by the BeyondCorp / Zero Trust white paper. Written in Go.
* [cockroachdb/pebble](https://github.com/cockroachdb/pebble) - RocksDB/LevelDB inspired key-value database in Go
* [ChimeraCoder/gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON
* [pksunkara/alpaca](https://github.com/pksunkara/alpaca) - Given a web API, Generate client libraries in node, php, python, ruby
* [docker/libchan](https://github.com/docker/libchan) - Like Go channels over the network
* [justinas/alice](https://github.com/justinas/alice) - Painless middleware chaining for Go
* [go-chassis/go-chassis](https://github.com/go-chassis/go-chassis) - a microservice framework for rapid development of micro services in Go with rich eco-system
* [astaxie/bat](https://github.com/astaxie/bat) - Go implement CLI, cURL-like tool for humans
* [talos-systems/talos](https://github.com/talos-systems/talos) - Talos is a modern OS for Kubernetes.
* [googleforgames/open-match](https://github.com/googleforgames/open-match) - Flexible, extensible, and scalable video game matchmaking.
* [go-jira/jira](https://github.com/go-jira/jira) - simple jira command line client in Go
* [uber-go/fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go.
* [mingrammer/go-web-framework-stars](https://github.com/mingrammer/go-web-framework-stars) - :star: Web frameworks for Go, most starred on GitHub
* [Humpheh/goboy](https://github.com/Humpheh/goboy) - Multi-platform Nintendo Game Boy Color emulator written in Go
* [MariaLetta/free-gophers-pack](https://github.com/MariaLetta/free-gophers-pack) - ✨ This pack of 100+ gopher pictures and elements will help you to build own design of almost anything related to Go Programming Language: presentations, posts in blogs or social media, courses, videos and many, many more.
* [osrg/gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language
* [hibiken/asynq](https://github.com/hibiken/asynq) - Asynq: simple, reliable, and efficient distributed task queue in Go
* [rubenv/sql-migrate](https://github.com/rubenv/sql-migrate) - SQL schema migration tool for Go.
* [prysmaticlabs/prysm](https://github.com/prysmaticlabs/prysm) - Go implementation of Ethereum proof of stake
* [gopher-os/gopher-os](https://github.com/gopher-os/gopher-os) - A proof of concept OS kernel written in Go
* [chanxuehong/wechat](https://github.com/chanxuehong/wechat) - weixin/wechat/微信公众平台/微信企业号/微信商户平台/微信支付 go/golang sdk
* [uber-go/goleak](https://github.com/uber-go/goleak) - Goroutine leak detector
* [rtr7/router7](https://github.com/rtr7/router7) - a small home internet router completely written in Go
* [Shpota/goxygen](https://github.com/Shpota/goxygen) - Generate a modern Web project with Go and Angular, React or Vue in seconds 🚀
* [alecthomas/participle](https://github.com/alecthomas/participle) - A parser library for Go
* [olahol/melody](https://github.com/olahol/melody) - :notes: Minimalist websocket framework for Go
* [golang/crypto](https://github.com/golang/crypto) - [mirror] Go supplementary cryptography libraries
* [mattes/migrate](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library.
* [pterm/pterm](https://github.com/pterm/pterm) - ✨ #PTerm is a modern Go module to beautify console output. Featuring charts, progressbars, tables, trees, and much more 🚀 It's completely configurable and 100% cross-platform compatible.
* [goraft/raft](https://github.com/goraft/raft) - UNMAINTAINED: A Go implementation of the Raft distributed consensus protocol.
* [hashicorp/go-memdb](https://github.com/hashicorp/go-memdb) - Golang in-memory database built on immutable radix trees
* [justjanne/powerline-go](https://github.com/justjanne/powerline-go) -  A beautiful and useful low-latency prompt for your shell, written in go
* [valyala/quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine for Go. Optimized for speed, zero memory allocations in hot paths. Up to 20x faster than html/template
* [arp242/goatcounter](https://github.com/arp242/goatcounter) - Easy web analytics. No tracking of personal data.
* [sciter-sdk/go-sciter](https://github.com/sciter-sdk/go-sciter) - Golang bindings of Sciter: the Embeddable HTML/CSS/script engine for modern UI development
* [floyernick/Data-Structures-and-Algorithms](https://github.com/floyernick/Data-Structures-and-Algorithms) - Data Structures and Algorithms implementation in Go
* [uber-go/dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* [ory/dockertest](https://github.com/ory/dockertest) - Write better integration tests! Dockertest helps you boot up ephermal docker images for your Go tests with minimal work.
* [henrylee2cn/erpc](https://github.com/henrylee2cn/erpc) - An efficient, extensible and easy-to-use RPC framework.
* [dave/jennifer](https://github.com/dave/jennifer) - Jennifer is a code generator for Go
* [GeertJohan/go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images,templates, etc very easy.
* [cenkalti/backoff](https://github.com/cenkalti/backoff) - ⏱ The exponential backoff algorithm in Go
* [motiv-labs/janus](https://github.com/motiv-labs/janus) - An API Gateway written in Go
* [tucnak/telebot](https://github.com/tucnak/telebot) - Telebot is a Telegram bot framework in Go.
* [studygolang/studygolang](https://github.com/studygolang/studygolang) - Go 语言中文网 | Golang中文社区 | Go语言学习园地 源码
* [minishift/minishift](https://github.com/minishift/minishift) - Run OpenShift 3.x locally
* [hpcloud/tail](https://github.com/hpcloud/tail) - Go package for reading from continously updated files (tail -f)
* [asobti/kube-monkey](https://github.com/asobti/kube-monkey) - An implementation of Netflix's Chaos Monkey for Kubernetes clusters
* [cristaloleg/go-advice](https://github.com/cristaloleg/go-advice) - List of advice and tricks for Go  ʕ◔ϖ◔ʔ
* [schollz/progressbar](https://github.com/schollz/progressbar) - A really basic thread-safe progress bar for Golang applications
* [pilosa/pilosa](https://github.com/pilosa/pilosa) - Pilosa is an open source, distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.
* [yunabe/lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter
* [thrasher-corp/gocryptotrader](https://github.com/thrasher-corp/gocryptotrader) - A cryptocurrency trading bot and framework supporting multiple exchanges written in Golang.
* [antonmedv/expr](https://github.com/antonmedv/expr) - Expression language for Go
* [Shopify/go-lua](https://github.com/Shopify/go-lua) - A Lua VM in Go
* [aler9/rtsp-simple-server](https://github.com/aler9/rtsp-simple-server) - ready-to-use RTSP / RTMP / HLS server and proxy that allows to read, publish and proxy video and audio streams
* [fortio/fortio](https://github.com/fortio/fortio) - Fortio load testing library, command line tool, advanced echo server and web UI in go (golang). Allows to specify a set query-per-second load and record latency histograms and other useful stats.
* [brianvoe/gofakeit](https://github.com/brianvoe/gofakeit) - Random fake data generator written in go
* [montanaflynn/stats](https://github.com/montanaflynn/stats) - A well tested and comprehensive Golang statistics library package with no dependencies.
* [gernest/utron](https://github.com/gernest/utron) - A lightweight MVC framework for Go(Golang)
* [deckarep/golang-set](https://github.com/deckarep/golang-set) - A simple set type for the Go language. Trusted by Docker, 1Password, Ethereum and Hashicorp.
* [go-oauth2/oauth2](https://github.com/go-oauth2/oauth2) - OAuth 2.0 server library for the Go programming language.
* [flashmob/go-guerrilla](https://github.com/flashmob/go-guerrilla) - Mini SMTP server written in golang
* [caarlos0/env](https://github.com/caarlos0/env) - A simple and zero-dependencies library to parse environment variables into structs.
* [liftbridge-io/liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams.
* [gocql/gocql](https://github.com/gocql/gocql) - Package gocql implements a fast and robust Cassandra client for the Go programming language.
* [open-telemetry/opentelemetry-go](https://github.com/open-telemetry/opentelemetry-go) - OpenTelemetry Go API and SDK
* [hexops/vecty](https://github.com/hexops/vecty) - Vecty lets you build responsive and dynamic web frontends in Go using WebAssembly, competing with modern web frameworks like React & VueJS.
* [constabulary/gb](https://github.com/constabulary/gb) - gb, the project based build tool for Go
* [flower-corp/rosedb](https://github.com/flower-corp/rosedb) - 🚀A fast, stable and embedded k-v storage in pure Golang, supports string, list, hash, set, sorted set. 一个 Go 语言实现的快速、稳定、内嵌的 k-v 存储引擎。
* [arachnys/athenapdf](https://github.com/arachnys/athenapdf) - Drop-in replacement for wkhtmltopdf built on Go, Electron and Docker
* [gorilla/sessions](https://github.com/gorilla/sessions) - Package gorilla/sessions provides cookie and filesystem sessions and infrastructure for custom session backends.
* [tus/tusd](https://github.com/tus/tusd) - Reference server implementation in Go of tus: the open protocol for resumable file uploads
* [Knetic/govaluate](https://github.com/Knetic/govaluate) - Arbitrary expression evaluation for golang
* [microcosm-cc/bluemonday](https://github.com/microcosm-cc/bluemonday) - bluemonday: a fast golang HTML sanitizer (inspired by the OWASP Java HTML Sanitizer) to scrub user generated content of XSS
* [gojek/heimdall](https://github.com/gojek/heimdall) - An enhanced HTTP client for Go
* [shen100/wemall](https://github.com/shen100/wemall) - 基于react, node.js, go开发的微商城（含微信小程序）
* [pressly/goose](https://github.com/pressly/goose) - A database migration tool. Supports SQL migrations and Go functions.
* [marcusolsson/goddd](https://github.com/marcusolsson/goddd) - Exploring DDD in Go
* [hyper0x/Golang_Puzzlers](https://github.com/hyper0x/Golang_Puzzlers) - An example project, for my column named "Core Golang - 36 lessons"
* [erda-project/erda](https://github.com/erda-project/erda) - An enterprise-grade Cloud-Native application platform for Kubernetes.
* [flosch/pongo2](https://github.com/flosch/pongo2) - Django-syntax like template-engine for Go
* [lindb/lindb](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database.
* [jessevdk/go-flags](https://github.com/jessevdk/go-flags) - go command line option parser
* [rfjakob/gocryptfs](https://github.com/rfjakob/gocryptfs) - Encrypted overlay filesystem written in Go
* [ardanlabs/service](https://github.com/ardanlabs/service) - Starter code for writing web services in Go using Kubernetes.
* [StackExchange/dnscontrol](https://github.com/StackExchange/dnscontrol) - Synchronize your DNS to multiple providers from a simple DSL
* [oliver006/redis_exporter](https://github.com/oliver006/redis_exporter) - Prometheus Exporter for Redis Metrics. Supports Redis 2.x, 3.x, 4.x, 5.x and 6.x
* [getlantern/systray](https://github.com/getlantern/systray) - a cross platfrom Go library to place an icon and menu in the notification area
* [cilium/ebpf](https://github.com/cilium/ebpf) - eBPF Library for Go
* [buraksezer/olric](https://github.com/buraksezer/olric) - Distributed cache and in-memory key/value data store. It can be used both as an embedded Go library and as a language-independent service.
* [golang/example](https://github.com/golang/example) - Go example projects
* [treeverse/lakeFS](https://github.com/treeverse/lakeFS) - Git-like capabilities for your object storage
* [dreamans/syncd](https://github.com/dreamans/syncd) - syncd是一款开源的代码部署工具，它具有简单、高效、易用等特点，可以提高团队的工作效率.
* [TwiN/gatus](https://github.com/TwiN/gatus) - ⛑ Gatus - Automated service health dashboard
* [aptly-dev/aptly](https://github.com/aptly-dev/aptly) - aptly - Debian repository management tool
* [nsqio/go-nsq](https://github.com/nsqio/go-nsq) - The official Go package for NSQ
* [awnumar/memguard](https://github.com/awnumar/memguard) - Secure software enclave for storage of sensitive information in memory.
* [nhooyr/websocket](https://github.com/nhooyr/websocket) - Minimal and idiomatic WebSocket library for Go
* [go-rod/rod](https://github.com/go-rod/rod) - A Devtools driver for web automation and scraping
* [rcrowley/goagain](https://github.com/rcrowley/goagain) - Zero-downtime restarts in Go
* [livekit/livekit-server](https://github.com/livekit/livekit-server) - Scalable, production-grade WebRTC infrastructure. SDKs in JS, React, Flutter, Swift, Kotlin, Go and Node.
* [cloudutil/AutoSpotting](https://github.com/cloudutil/AutoSpotting) - Saves up to 90% of AWS EC2 costs by automating the use of spot instances on existing AutoScaling groups. Installs in minutes using CloudFormation or Terraform. Convenient to deploy at scale using StackSets. Uses tagging to avoid launch configuration changes. Automated spot termination handling. Reliable fallback to on-demand instances.
* [Terry-Mao/gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - Golang push server cluster
* [marcusolsson/tui-go](https://github.com/marcusolsson/tui-go) - A UI library for terminal applications.
* [xiaonanln/goworld](https://github.com/xiaonanln/goworld) - Scalable Distributed Game Server Engine with Hot Swapping in Golang
* [ThreeDotsLabs/wild-workouts-go-ddd-example](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) - Go DDD example application. Complete project to show how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
* [xinliangnote/Go](https://github.com/xinliangnote/Go) - 【Go 从入门到实战】学习笔记，从零开始学 Go、Gin 框架，基本语法包括 26 个Demo，Gin 框架包括：Gin 自定义路由配置、Gin 使用 Logrus 进行日志记录、Gin 数据绑定和验证、Gin 自定义错误处理、Go gRPC Hello World... 持续更新中...
* [francoispqt/gojay](https://github.com/francoispqt/gojay) - fastest JSON encoder/decoder with powerful stream API for Golang
* [ory/ladon](https://github.com/ory/ladon) - A SDK for access control policies: authorization for the microservice and IoT age. Inspired by AWS IAM policies. Written for Go.
* [wal-g/wal-g](https://github.com/wal-g/wal-g) - Archival and Restoration for Postgres
* [howeyc/fsnotify](https://github.com/howeyc/fsnotify) - File system notification for Go
* [cloudflare/tableflip](https://github.com/cloudflare/tableflip) - Graceful process restarts in Go
* [alicebob/miniredis](https://github.com/alicebob/miniredis) - Pure Go Redis server for Go unittests
* [rexray/rexray](https://github.com/rexray/rexray) - REX-Ray is a container storage orchestration engine enabling persistence for cloud native workloads
* [skynetservices/skynet-archive](https://github.com/skynetservices/skynet-archive) - Skynet is a framework for distributed services in Go.
* [filecoin-project/lotus](https://github.com/filecoin-project/lotus) - Implementation of the Filecoin protocol, written in Go
* [rs/cors](https://github.com/rs/cors) - Go net/http configurable handler to handle CORS requests
* [kkdai/youtube](https://github.com/kkdai/youtube) - Download Youtube Video in Golang
* [fogleman/pt](https://github.com/fogleman/pt) - A path tracer written in Go.
* [minio/mc](https://github.com/minio/mc) - MinIO Client is a replacement for ls, cp, mkdir, diff and rsync commands for filesystems and object storage.
* [felixge/fgprof](https://github.com/felixge/fgprof) - 🚀 fgprof is a sampling Go profiler that allows you to analyze On-CPU as well as Off-CPU (e.g. I/O) time together.
* [src-d/gitbase](https://github.com/src-d/gitbase) - SQL interface to git repositories, written in Go. https://docs.sourced.tech/gitbase
* [xeipuuv/gojsonschema](https://github.com/xeipuuv/gojsonschema) - An implementation of JSON Schema, draft v4 v6 & v7 - Go language
* [PuerkitoBio/gocrawl](https://github.com/PuerkitoBio/gocrawl) - Polite, slim and concurrent web crawler.
* [bitfield/script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go
* [go-qml/qml](https://github.com/go-qml/qml) - QML support for the Go language
* [cdarwin/go-koans](https://github.com/cdarwin/go-koans) - koans for go
* [spf13/cast](https://github.com/spf13/cast) - safe and easy casting from one type to another in Go
* [pierrre/imageserver](https://github.com/pierrre/imageserver) - Image server toolkit in Go
* [gokrazy/gokrazy](https://github.com/gokrazy/gokrazy) - a native Go userland for your Raspberry Pi 3 or 4 appliances (or amd64 PCs!)
* [go-pay/gopay](https://github.com/go-pay/gopay) - 微信、支付宝、PayPal 的Go版本SDK。【极简、易用的聚合支付SDK】
* [kabukky/journey](https://github.com/kabukky/journey) - A blog engine written in Go, compatible with Ghost themes.
* [go-gota/gota](https://github.com/go-gota/gota) - Gota: DataFrames and data wrangling in Go (Golang)
* [zachlatta/sshtron](https://github.com/zachlatta/sshtron) - $ ssh sshtron.zachlatta.com
* [git-chglog/git-chglog](https://github.com/git-chglog/git-chglog) - CHANGELOG generator implemented in Go (Golang).
* [fsouza/go-dockerclient](https://github.com/fsouza/go-dockerclient) - Go client for the Docker Engine API.
* [filecoin-project/venus](https://github.com/filecoin-project/venus) - Filecoin Full Node Implementation in Go
* [jordan-wright/email](https://github.com/jordan-wright/email) - Robust and flexible email library for Go
* [census-instrumentation/opencensus-go](https://github.com/census-instrumentation/opencensus-go) - A stats collection and distributed tracing framework
* [bilibili/overlord](https://github.com/bilibili/overlord) - Overlord是哔哩哔哩基于Go语言编写的memcache和redis&cluster的代理及集群管理功能，致力于提供自动化高可用的缓存服务解决方案。
* [praetorian-inc/gokart](https://github.com/praetorian-inc/gokart) - A static analysis tool for securing Go code
* [xyproto/algernon](https://github.com/xyproto/algernon) - :tophat: Small self-contained pure-Go web server with Lua, Markdown, HTTP/2, QUIC, Redis and PostgreSQL support
* [sony/gobreaker](https://github.com/sony/gobreaker) - Circuit Breaker implemented in Go
* [goadapp/goad](https://github.com/goadapp/goad) - Goad is an AWS Lambda powered, highly distributed, load testing tool
* [gosuri/uiprogress](https://github.com/gosuri/uiprogress) - A go library to render progress bars in terminal applications
* [gin-gonic/examples](https://github.com/gin-gonic/examples) - A repository to host examples and tutorials for Gin.
* [yggdrasil-network/yggdrasil-go](https://github.com/yggdrasil-network/yggdrasil-go) - An experiment in scalable routing as an encrypted IPv6 overlay network
* [lovoo/goka](https://github.com/lovoo/goka) - Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go.
* [aws/amazon-ecs-agent](https://github.com/aws/amazon-ecs-agent) - Amazon Elastic Container Service Agent
* [mmcloughlin/avo](https://github.com/mmcloughlin/avo) - Generate x86 Assembly with Go
* [evilmartians/lefthook](https://github.com/evilmartians/lefthook) - Fast and powerful Git hooks manager for any type of projects.
* [mattn/goreman](https://github.com/mattn/goreman) - foreman clone written in go language
* [8treenet/freedom](https://github.com/8treenet/freedom) - Freedom是一个基于六边形架构的框架，可以支撑充血的领域模型范式。
* [unrolled/secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [galeone/tfgo](https://github.com/galeone/tfgo) - Tensorflow + Go, the gopher way
* [raviqqe/muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go
* [sipt/shuttle](https://github.com/sipt/shuttle) - A web proxy in Golang with amazing features.
* [gocelery/gocelery](https://github.com/gocelery/gocelery) - Celery Distributed Task Queue in Go
* [rendora/rendora](https://github.com/rendora/rendora) - dynamic server-side rendering using headless Chrome to effortlessly solve the SEO problem for modern javascript websites
* [gocraft/work](https://github.com/gocraft/work) - Process background jobs in Go
* [levigross/grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library
* [RichardKnop/go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - A standalone, specification-compliant,  OAuth2 server written in Golang.
* [Azure/golua](https://github.com/Azure/golua) - A Lua 5.3 engine implemented in Go
* [nicksnyder/go-i18n](https://github.com/nicksnyder/go-i18n) - Translate your Go program into multiple languages.
* [xujiajun/nutsdb](https://github.com/xujiajun/nutsdb) - A simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.
* [gavv/httpexpect](https://github.com/gavv/httpexpect) - End-to-end HTTP and REST API testing for Go.
* [mattn/go-gtk](https://github.com/mattn/go-gtk) - Go binding for GTK
* [divan/expvarmon](https://github.com/divan/expvarmon) - TermUI based monitor for Go apps using expvars (/debug/vars). Quickest way to monitor your Go app(s).
* [alibaba/sentinel-golang](https://github.com/alibaba/sentinel-golang) - Sentinel Go version (Reliability & Resilience)
* [inconshreveable/go-update](https://github.com/inconshreveable/go-update) - Build self-updating Golang programs
* [yuin/goldmark](https://github.com/yuin/goldmark) - :trophy: A markdown parser written in Go. Easy to extend, standard(CommonMark) compliant, well structured.
* [u-root/u-root](https://github.com/u-root/u-root) - A fully Go userland with Linux bootloaders! u-root can create a one-binary root file system (initramfs) containing a busybox-like set of tools written in Go.
* [jpillora/overseer](https://github.com/jpillora/overseer) - Monitorable, gracefully restarting, self-upgrading binaries in Go (golang)
* [imdario/mergo](https://github.com/imdario/mergo) - Mergo: merging Go structs and maps since 2013.
* [guptarohit/asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [SpectoLabs/hoverfly](https://github.com/SpectoLabs/hoverfly) - Lightweight service virtualization/API simulation tool for developers and testers
* [thedevsaddam/gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON/YAML/XML/CSV Data
* [pseudomuto/protoc-gen-doc](https://github.com/pseudomuto/protoc-gen-doc) - Documentation generator plugin for Google Protocol Buffers
* [bluele/gcache](https://github.com/bluele/gcache) - An in-memory cache library for golang. It supports multiple eviction policies: LRU, LFU, ARC
* [skip2/go-qrcode](https://github.com/skip2/go-qrcode) - :sparkles: QR Code encoder (Go)
* [astaxie/gopkg](https://github.com/astaxie/gopkg) - example for the go pkg's function
* [vmware/govmomi](https://github.com/vmware/govmomi) - Go library for the VMware vSphere API
* [vishvananda/netlink](https://github.com/vishvananda/netlink) - Simple netlink library for go.
* [gothinkster/golang-gin-realworld-example-app](https://github.com/gothinkster/golang-gin-realworld-example-app) - Exemplary real world application built with Golang + Gin
* [cosmos72/gomacro](https://github.com/cosmos72/gomacro) - Interactive Go interpreter and debugger with REPL, Eval, generics and Lisp-like macros
* [ajstarks/svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation
* [vulcand/oxy](https://github.com/vulcand/oxy) - Go middlewares for HTTP servers & proxies
* [g3n/engine](https://github.com/g3n/engine) - Go 3D Game Engine (http://g3n.rocks)
* [giorgisio/goav](https://github.com/giorgisio/goav) - Golang bindings for FFmpeg
* [stefanprodan/podinfo](https://github.com/stefanprodan/podinfo) - Go microservice template for Kubernetes
* [kisielk/errcheck](https://github.com/kisielk/errcheck) - errcheck checks that you checked errors.
* [stianeikeland/go-rpio](https://github.com/stianeikeland/go-rpio) - :electric_plug: Raspberry Pi GPIO library for go-lang
* [mmcdole/gofeed](https://github.com/mmcdole/gofeed) - Parse RSS, Atom and JSON feeds in Go
* [link1st/go-stress-testing](https://github.com/link1st/go-stress-testing) - go 实现的压测工具，ab、locust、Jmeter压测工具介绍【单台机器100w连接压测实战】
* [arnauddri/algorithms](https://github.com/arnauddri/algorithms) - Algorithms & Data Structures in Go
* [icexin/eggos](https://github.com/icexin/eggos) - A Go unikernel running on x86 bare metal
* [coreos/go-systemd](https://github.com/coreos/go-systemd) - Go bindings to systemd socket activation, journal, D-Bus, and unit files
* [uber-go/automaxprocs](https://github.com/uber-go/automaxprocs) - Automatically set GOMAXPROCS to match Linux container CPU quota.
* [wasmerio/wasmer-go](https://github.com/wasmerio/wasmer-go) - 🐹🕸️ WebAssembly runtime for Go
* [yanyiwu/gojieba](https://github.com/yanyiwu/gojieba) - "结巴"中文分词的Golang版本
* [arl/statsviz](https://github.com/arl/statsviz) - :rocket: Instant live visualization of your Go application runtime statistics (GC, MemStats, etc.) in the browser
* [h2non/bimg](https://github.com/h2non/bimg) - Go package for fast high-level image processing powered by libvips C library
* [hu17889/go_spider](https://github.com/hu17889/go_spider) - [爬虫框架 (golang)] An awesome Go concurrent Crawler(spider) framework. The crawler is flexible and modular. It can be expanded to an Individualized crawler easily or you can use the default crawl components only.
* [op/go-logging](https://github.com/op/go-logging) - Golang logging library
* [ory/fosite](https://github.com/ory/fosite) - Extensible security first OAuth 2.0 and OpenID Connect SDK for Go.
* [ajvb/kala](https://github.com/ajvb/kala) - Modern Job Scheduler
* [mkchoi212/fac](https://github.com/mkchoi212/fac) - Easy-to-use CUI for fixing git conflicts
* [TomWright/dasel](https://github.com/TomWright/dasel) - Select, put and delete data from JSON, TOML, YAML, XML and CSV files with a single tool. Supports conversion between formats and can be used as a Go package.
* [elliotchance/c2go](https://github.com/elliotchance/c2go) - ⚖️ A tool for transpiling C to Go.
* [katzien/go-structure-examples](https://github.com/katzien/go-structure-examples) - Examples for my talk on structuring go apps
* [takama/daemon](https://github.com/takama/daemon) - A daemon package for use with Go (golang) services
* [goodwithtech/dockle](https://github.com/goodwithtech/dockle) - Container Image Linter for Security, Helping build the Best-Practice Docker Image, Easy to start
* [elastic/cloud-on-k8s](https://github.com/elastic/cloud-on-k8s) - Elastic Cloud on Kubernetes
* [sourcegraph/appdash](https://github.com/sourcegraph/appdash) - Application tracing system for Go, based on Google's Dapper.
* [nadoo/glider](https://github.com/nadoo/glider) - glider is a forward proxy with multiple protocols support, and also a dns/dhcp server with ipset management features(like dnsmasq).
* [go-ego/gse](https://github.com/go-ego/gse) - Go efficient multilingual NLP and text segmentation; support english, chinese, japanese and other. Go 高性能多语言 NLP 和分词
* [openacid/slim](https://github.com/openacid/slim) - Surprisingly space efficient trie in Golang(11 bits/key; 100 ns/get).
* [bxcodec/faker](https://github.com/bxcodec/faker) - Go (Golang)  Fake Data  Generator for Struct
* [bradfitz/http2](https://github.com/bradfitz/http2) - old repo for HTTP/2 support for Go (see README for new home)
* [xiaobaiTech/golangFamily](https://github.com/xiaobaiTech/golangFamily) - 【超全golang面试题合集+golang学习指南+golang知识图谱+入门成长路线】 一份涵盖大部分golang程序员所需要掌握的核心知识。常用第三方库(mysql,mq,es,redis等)+机器学习库+算法库+游戏库+开源框架+自然语言处理nlp库+网络库+视频库+微服务框架+视频教程+音频音乐库+图形图片库+物联网库+地理位置信息+嵌入式脚本库+编译器库+数据库+金融库+电子邮件库+电子书籍+分词+数据结构+设计模式+去html tag标签等+go学习+go面试+计算机网络基础+图解网络+操作系统面试题+数据库面试题+面试题合集
* [bcicen/grmon](https://github.com/bcicen/grmon) - Command line monitoring for goroutines
* [google/periph](https://github.com/google/periph) - Go·Hardware·Lean
* [bwmarrin/snowflake](https://github.com/bwmarrin/snowflake) - A simple to use Go (golang) package to generate or parse Twitter snowflake IDs
* [authzed/spicedb](https://github.com/authzed/spicedb) - Inspired by Google's Zanzibar paper, SpiceDB is a database system for managing security-critical application permissions.
* [icexin/gocraft](https://github.com/icexin/gocraft) - A Minecraft like game written in go
* [chzyer/readline](https://github.com/chzyer/readline) - Readline is a pure go(golang) implementation for GNU-Readline kind library
* [GoBelieveIO/im_service](https://github.com/GoBelieveIO/im_service) - golang   im   server
* [chai2010/go2-book](https://github.com/chai2010/go2-book) - :books: 《Go2编程指南》开源图书，重点讲解Go2新特性，以及Go1教程中较少涉及的特性
* [tidwall/redcon](https://github.com/tidwall/redcon) - Redis compatible server framework for Go
* [perlin-network/noise](https://github.com/perlin-network/noise) - A decentralized P2P networking stack written in Go.
* [caffix/amass](https://github.com/caffix/amass) - In-depth Attack Surface Mapping and Asset Discovery
* [anaskhan96/soup](https://github.com/anaskhan96/soup) - Web Scraper in Go, similar to BeautifulSoup
* [libgit2/git2go](https://github.com/libgit2/git2go) - Git to Go; bindings for libgit2. Like McDonald's but tastier.
* [austingebauer/go-leetcode](https://github.com/austingebauer/go-leetcode) - A collection of 100+ popular LeetCode problems solved in Go.
* [ClickHouse/clickhouse-go](https://github.com/ClickHouse/clickhouse-go) - Golang driver for ClickHouse
* [rogchap/v8go](https://github.com/rogchap/v8go) - Execute JavaScript from Go
* [laher/goxc](https://github.com/laher/goxc) - a build tool for Go, with a focus on cross-compiling, packaging and deployment
* [fatih/gomodifytags](https://github.com/fatih/gomodifytags) - Go tool to modify struct field tags
* [tebeka/selenium](https://github.com/tebeka/selenium) - Selenium/Webdriver client for Go
* [gotk3/gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3
* [gocraft/dbr](https://github.com/gocraft/dbr) - Additions to Go's database/sql for super fast performance and convenience.
* [muesli/cache2go](https://github.com/muesli/cache2go) - Concurrency-safe Go caching library with expiration capabilities and access counters
* [brutella/hc](https://github.com/brutella/hc) - hc is a lightweight framework to develop HomeKit accessories in Go.
* [giongto35/cloud-game](https://github.com/giongto35/cloud-game) - Web-based Cloud Gaming service for Retro Game
* [projectdiscovery/naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests
* [microhq/go-plugins](https://github.com/microhq/go-plugins) - Go Micro Plugins. Moved to go-micro/plugins.
* [briandowns/spinner](https://github.com/briandowns/spinner) - Go (golang) package with 90 configurable terminal spinner/progress indicators.
* [Rhymen/go-whatsapp](https://github.com/Rhymen/go-whatsapp) - WhatsApp Web API
* [kjk/notionapi](https://github.com/kjk/notionapi) - Unofficial Go API for Notion.so
* [pkg/profile](https://github.com/pkg/profile) - Simple profiling for Go
* [profclems/glab](https://github.com/profclems/glab) - A GitLab CLI tool bringing GitLab to your command line
* [golang-jwt/jwt](https://github.com/golang-jwt/jwt) - Community maintained clone of https://github.com/dgrijalva/jwt-go
* [yyyar/gobetween](https://github.com/yyyar/gobetween) - :cloud: Modern & minimalistic load balancer for the Сloud era
* [otiai10/gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library
* [cpmech/gosl](https://github.com/cpmech/gosl) - Linear algebra, eigenvalues, FFT, Bessel, elliptic, orthogonal polys, geometry, NURBS, numerical quadrature, 3D transfinite interpolation, random numbers, Mersenne twister, probability distributions, optimisation, differential equations.
* [markphelps/flipt](https://github.com/markphelps/flipt) - An open-source, on-prem feature flag solution
* [google/novm](https://github.com/google/novm) - Experimental KVM-based VMM for containers, written in Go.
* [samuel/go-zookeeper](https://github.com/samuel/go-zookeeper) - Native ZooKeeper client for Go. This project is no longer maintained. Please use https://github.com/go-zookeeper/zk instead.
* [cheekybits/genny](https://github.com/cheekybits/genny) - Elegant generics for Go
* [looplab/fsm](https://github.com/looplab/fsm) - Finite State Machine for Go
* [ugorji/go](https://github.com/ugorji/go) - idiomatic codec and rpc lib for msgpack, cbor, json, etc. msgpack.org[Go]
* [openscrm/api-server](https://github.com/openscrm/api-server) - OpenSCRM是一套基于Go和React的超高质量企业微信私域流量管理系统 。遵守Apache2.0协议，全网唯一免费商用。企业微信、私域流量、SCRM。
* [gojp/goreportcard](https://github.com/gojp/goreportcard) - A report card for your Go application
* [xxjwxc/gormt](https://github.com/xxjwxc/gormt) - database to golang struct
* [eBay/akutan](https://github.com/eBay/akutan) - A distributed knowledge graph store
* [smallnest/go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - :zap: Go web framework benchmark
* [rodrigo-brito/gocity](https://github.com/rodrigo-brito/gocity) - :bar_chart: Code City metaphor for visualizing Go source code in 3D
* [geziyor/geziyor](https://github.com/geziyor/geziyor) - Geziyor, a fast web crawling & scraping framework for Go. Supports JS rendering.
* [HDT3213/godis](https://github.com/HDT3213/godis) - A Golang implemented Redis Server and Cluster. Go 语言实现的 Redis 服务器和分布式集群
* [vmihailenco/msgpack](https://github.com/vmihailenco/msgpack) - msgpack.org[Go] MessagePack encoding for Golang
* [anchore/syft](https://github.com/anchore/syft) - CLI tool and library for generating a Software Bill of Materials from container images and filesystems
* [thoas/picfit](https://github.com/thoas/picfit) - An image resizing server written in Go
* [tenta-browser/tenta-dns](https://github.com/tenta-browser/tenta-dns) - Recursive and authoritative DNS server in go, including DNSSEC and DNS-over-TLS
* [adammck/terraform-inventory](https://github.com/adammck/terraform-inventory) - Terraform State → Ansible Dynamic Inventory
* [unknwon/go-rock-libraries-showcases](https://github.com/unknwon/go-rock-libraries-showcases) - 《Go名库讲解》是一套针对 Google 出品的 Go 语言的第三方库进行评测讲解的集博客、示例与语音视频为一体的综合教程，适合完成学习完成《Go编程基础》教程的学习者。
* [oniony/TMSU](https://github.com/oniony/TMSU) - TMSU lets you tags your files and then access them through a nifty virtual filesystem from any other application.
* [LockGit/gochat](https://github.com/LockGit/gochat) - goim server write by golang !🚀
* [radondb/radon](https://github.com/radondb/radon) - RadonDB is an open source, cloud-native MySQL database for building global, scalable cloud services
* [rethinkdb/rethinkdb-go](https://github.com/rethinkdb/rethinkdb-go) - Go language driver for RethinkDB
* [go-bootstrap/go-bootstrap](https://github.com/go-bootstrap/go-bootstrap) - Generates a lean and mean Go web project.
* [cihub/seelog](https://github.com/cihub/seelog) - Seelog is a native Go logging library that provides flexible asynchronous dispatching, filtering, and formatting.
* [hairyhenderson/gomplate](https://github.com/hairyhenderson/gomplate) - A flexible commandline tool for template rendering. Supports lots of local and remote datasources.
* [unrolled/render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, binary data, and HTML templates responses.
* [huichen/sego](https://github.com/huichen/sego) - Go中文分词
* [henrylee2cn/faygo](https://github.com/henrylee2cn/faygo) - Faygo is a fast and concise Go Web framework that can be used to develop high-performance web app(especially API) with fewer codes. Just define a struct handler, faygo will automatically bind/verify the request parameters and generate the online API doc.
* [tharsis/ethermint](https://github.com/tharsis/ethermint) - Ethermint is a scalable and interoperable Ethereum library, built on Proof-of-Stake with fast-finality using the Cosmos SDK.
* [hashicorp/terraform-provider-google](https://github.com/hashicorp/terraform-provider-google) - Terraform Google Cloud Platform provider
* [sevlyar/go-daemon](https://github.com/sevlyar/go-daemon) - A library for writing system daemons in golang.
* [yangwenmai/learning-golang](https://github.com/yangwenmai/learning-golang) - Go 学习之路：Go 开发者博客、Go 微信公众号、Go 学习资料（文档、书籍、视频）
* [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults) - A Vault swiss-army knife: a K8s operator, Go client with automatic token renewal, automatic configuration, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). Direct secret injection into Pods.
* [deepmap/oapi-codegen](https://github.com/deepmap/oapi-codegen) - Generate Go client and server boilerplate from OpenAPI 3 specifications
* [iamduo/workq](https://github.com/iamduo/workq) - Job server in Go
* [mop-tracker/mop](https://github.com/mop-tracker/mop) - Stock market tracker for hackers.
* [julienschmidt/go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router and web framework benchmark
* [h2non/gock](https://github.com/h2non/gock) - HTTP traffic mocking and testing made easy in Go ༼ʘ̚ل͜ʘ̚༽
* [lastbackend/lastbackend](https://github.com/lastbackend/lastbackend) - System for containerized apps management. From build to scaling.
* [hwholiday/learning_tools](https://github.com/hwholiday/learning_tools) - Go 学习、Go 进阶、Go 实用工具类、Go DDD 项目落地、Go-kit 、Go-Micro 、Go 推送平台、微服务实践
* [golang/vgo](https://github.com/golang/vgo) - [mirror] Versioned Go Prototype
* [40t/go-sniffer](https://github.com/40t/go-sniffer) - 🔎Sniffing and parsing mysql,redis,http,mongodb etc protocol. 抓包截取项目中的数据库请求并解析成相应的语句。
* [xanzy/go-gitlab](https://github.com/xanzy/go-gitlab) - GitLab Go SDK
* [0xAX/go-algorithms](https://github.com/0xAX/go-algorithms) - Algorithms and data structures for golang
* [onsi/gomega](https://github.com/onsi/gomega) - Ginkgo's Preferred Matcher Library
* [betty200744/ultimate-go](https://github.com/betty200744/ultimate-go) - This repo contains my notes on working with Go and computer systems.
* [sandglass/sandglass](https://github.com/sandglass/sandglass) - Sandglass is a distributed, horizontally scalable, persistent, time sorted message queue.
* [go-ldap/ldap](https://github.com/go-ldap/ldap) - Basic LDAP v3 functionality for the GO programming language.
* [cucumber/godog](https://github.com/cucumber/godog) - Cucumber for golang
* [go-redsync/redsync](https://github.com/go-redsync/redsync) - Distributed mutual exclusion lock using Redis for Go
* [vbauerster/mpb](https://github.com/vbauerster/mpb) - multi progress bar for Go cli applications
* [bemasher/rtlamr](https://github.com/bemasher/rtlamr) - An rtl-sdr receiver for Itron ERT compatible smart meters operating in the 900MHz ISM band.
* [tidwall/sjson](https://github.com/tidwall/sjson) - Set JSON values very quickly in Go
* [pibigstar/go-demo](https://github.com/pibigstar/go-demo) - Go语言实例教程从入门到进阶，包括基础库使用、设计模式、面试易错点、工具类、对接第三方等
* [netgusto/nodebook](https://github.com/netgusto/nodebook) - Nodebook - Multi-Lang Web REPL + CLI Code runner
* [google/starlark-go](https://github.com/google/starlark-go) - Starlark in Go: the Starlark configuration language, implemented in Go
* [birdayz/kaf](https://github.com/birdayz/kaf) - Modern CLI for Apache Kafka, written in Go.
* [dchest/captcha](https://github.com/dchest/captcha) - Go package captcha implements generation and verification of image and audio CAPTCHAs.
* [kitabisa/teler](https://github.com/kitabisa/teler) - Real-time HTTP Intrusion Detection
* [rs/curlie](https://github.com/rs/curlie) - The power of curl, the ease of use of httpie.
* [StephenGrider/GoCasts](https://github.com/StephenGrider/GoCasts) - Companion Repo to https://www.udemy.com/go-the-complete-developers-guide/
* [google/go-containerregistry](https://github.com/google/go-containerregistry) - Go library and CLIs for working with container registries
* [funny/link](https://github.com/funny/link) - Go语言网络层脚手架
* [denisenkom/go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft SQL server driver written in go language
* [disintegration/gift](https://github.com/disintegration/gift) - Go Image Filtering Toolkit
* [RainbowMango/GoExpertProgramming](https://github.com/RainbowMango/GoExpertProgramming) - 《Go专家编程》Go语言快速入门，轻松进阶！
* [shiyanhui/hero](https://github.com/shiyanhui/hero) - A handy, fast and powerful go template engine.
* [visualfc/goqt](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework.
* [stashapp/stash](https://github.com/stashapp/stash) - An organizer for your porn, written in Go
* [ghostunnel/ghostunnel](https://github.com/ghostunnel/ghostunnel) - A simple SSL/TLS proxy with mutual authentication for securing non-TLS services
* [xormplus/xorm](https://github.com/xormplus/xorm) - xorm是一个简单而强大的Go语言ORM库，通过它可以使数据库操作非常简便。本库是基于原版xorm的定制增强版本，为xorm提供类似ibatis的配置文件及动态SQL支持，支持AcitveRecord操作
* [stripe/stripe-go](https://github.com/stripe/stripe-go) - Go library for the Stripe API.
* [minio/minio-go](https://github.com/minio/minio-go) - MinIO Client SDK for Go
* [go-bindata/go-bindata](https://github.com/go-bindata/go-bindata) - Turn data file into go code.
* [dreddsa5dies/goHackTools](https://github.com/dreddsa5dies/goHackTools) - Hacker tools on Go (Golang)
* [dundee/gdu](https://github.com/dundee/gdu) - Fast disk usage analyzer with console interface written in Go
* [zegl/kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security
* [songtianyi/wechat-go](https://github.com/songtianyi/wechat-go) - go version wechat web api and message framework for building wechat robot
* [sorenisanerd/gotty](https://github.com/sorenisanerd/gotty) - Share your terminal as a web application
* [signintech/gopdf](https://github.com/signintech/gopdf) - A simple library for generating PDF written in Go lang
* [yhat/scrape](https://github.com/yhat/scrape) - A simple, higher level interface for Go web scraping.
* [owenthereal/godzilla](https://github.com/owenthereal/godzilla) - Godzilla is a ES2015 to Go source code transpiler and runtime
* [hashicorp/go-multierror](https://github.com/hashicorp/go-multierror) - A Go (golang) package for representing a list of errors as a single error.
* [target/goalert](https://github.com/target/goalert) - Open source on-call scheduling, automated escalations, and notifications so you never miss a critical alert
* [ulule/limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [h2non/filetype](https://github.com/h2non/filetype) - Fast, dependency-free Go package to infer binary file types based on the magic numbers header signature
* [dghubble/gologin](https://github.com/dghubble/gologin) - Go login handlers for authentication providers (OAuth1, OAuth2)
* [EngoEngine/engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go.
* [go-co-op/gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go cron scheduling. This is a fork from https://github.com/jasonlvhit/gocron
* [projectdiscovery/proxify](https://github.com/projectdiscovery/proxify) - Swiss Army knife Proxy tool for HTTP/HTTPS traffic capture, manipulation, and replay on the go.
* [gocraft/web](https://github.com/gocraft/web) - Go Router + Middleware. Your Contexts.
* [utahta/pythonbrew](https://github.com/utahta/pythonbrew) - Python Environment manager
* [hanwen/go-fuse](https://github.com/hanwen/go-fuse) - FUSE bindings for Go
* [camptocamp/terraboard](https://github.com/camptocamp/terraboard) - :earth_africa: :clipboard:  A web dashboard to inspect Terraform States
* [mitchellh/cli](https://github.com/mitchellh/cli) - A Go library for implementing command-line interfaces.
* [RoaringBitmap/roaring](https://github.com/RoaringBitmap/roaring) - Roaring bitmaps in Go (golang)
* [tinylib/msgp](https://github.com/tinylib/msgp) - A Go code generator for MessagePack / msgpack.org[Go]
* [unidoc/unipdf](https://github.com/unidoc/unipdf) - Golang PDF library for creating and processing PDF files (pure go)
* [smallnest/1m-go-tcp-server](https://github.com/smallnest/1m-go-tcp-server) - benchmarks for implementation of servers which support 1 million connections
* [faiface/beep](https://github.com/faiface/beep) - A little package that brings sound to any Go application. Suitable for playback and audio-processing.
* [nntaoli-project/goex](https://github.com/nntaoli-project/goex) - Exchange Rest And WebSocket API For Golang  Wrapper support okcoin,okex,huobi,hbdm,bitmex,coinex,poloniex,bitfinex,bitstamp,binance,kraken,bithumb,zb,hitbtc,fcoin, coinbene
* [emersion/go-imap](https://github.com/emersion/go-imap) -  :inbox_tray: An IMAP library for clients and servers
* [DataDog/datadog-agent](https://github.com/DataDog/datadog-agent) - Datadog Agent
* [bradfitz/gomemcache](https://github.com/bradfitz/gomemcache) - Go Memcached client library #golang
* [tmrts/boilr](https://github.com/tmrts/boilr) - :zap: boilerplate template manager that generates files or directories from template repositories
* [glycerine/zygomys](https://github.com/glycerine/zygomys) - Zygo is a Lisp interpreter written in 100% Go. Central use case: dynamically compose Go struct trees in a zygo script, then invoke compiled Go functions on those trees. Makes Go reflection easy.
* [prometheus-community/elasticsearch_exporter](https://github.com/prometheus-community/elasticsearch_exporter) - Elasticsearch stats exporter for Prometheus
* [golang/tour](https://github.com/golang/tour) - [mirror] A Tour of Go
* [yedf/dtm](https://github.com/yedf/dtm) - 🔥A cross-language distributed transaction manager. Support xa, tcc, saga, transactional messages.  跨语言分布式事务管理器
* [cch123/golang-notes](https://github.com/cch123/golang-notes) - Go source code analysis(zh-cn)
* [roseduan/rosedb](https://github.com/roseduan/rosedb) - 🚀A fast, stable and embedded k-v storage in pure Golang, supports string, list, hash, set, sorted set. 一个 Go 语言实现的快速、稳定、内嵌的 k-v 存储引擎。
* [mlogclub/bbs-go](https://github.com/mlogclub/bbs-go) - 基于Golang的开源社区系统。
* [monochromegane/go_design_pattern](https://github.com/monochromegane/go_design_pattern) - Design patterns in Golang.
* [jondot/goweight](https://github.com/jondot/goweight) - A tool to analyze and troubleshoot a Go binary size.
* [slackhq/go-audit](https://github.com/slackhq/go-audit) - go-audit is an alternative to the auditd daemon that ships with many distros
* [mattn/gom](https://github.com/mattn/gom) - Go Manager - bundle for go
* [drone/drone](https://github.com/drone/drone) - Drone is a Container-Native, Continuous Delivery Platform
* [mattermost/mattermost-server](https://github.com/mattermost/mattermost-server) - Mattermost is an open source platform for secure collaboration across the entire software development lifecycle.
* [askgitdev/askgit](https://github.com/askgitdev/askgit) - Query git repositories with SQL. Generate reports, perform status checks, analyze codebases. 🔍 📊
* [zgoat/goatcounter](https://github.com/zgoat/goatcounter) - Easy web analytics. No tracking of personal data.
* [tylertreat/BoomFilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [dghubble/sling](https://github.com/dghubble/sling) - A Go HTTP client library for creating and sending API requests
* [lileio/lile](https://github.com/lileio/lile) - Easily generate gRPC services in Go ⚡️
* [google/go-querystring](https://github.com/google/go-querystring) - go-querystring is Go library for encoding structs into URL query strings.
* [ddollar/forego](https://github.com/ddollar/forego) - Foreman in Go
* [gographics/imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API
* [GoogleContainerTools/skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development
* [devfeel/dotweb](https://github.com/devfeel/dotweb) - Simple and easy go web micro framework
* [ergochat/ergo](https://github.com/ergochat/ergo) - A modern IRC server (daemon/ircd) written in Go.
* [haxpax/gosms](https://github.com/haxpax/gosms) - :mailbox_closed: Your own local SMS gateway in Go
* [miguelmota/cointop](https://github.com/miguelmota/cointop) - A fast and lightweight interactive terminal based UI application for tracking cryptocurrencies 🚀
* [AutoSpotting/AutoSpotting](https://github.com/AutoSpotting/AutoSpotting) - Saves up to 90% of AWS EC2 costs by automating the use of spot instances on existing AutoScaling groups. Installs in minutes using CloudFormation or Terraform. Convenient to deploy at scale using StackSets. Uses tagging to avoid launch configuration changes. Automated spot termination handling. Reliable fallback to on-demand instances.
* [TwinProduction/gatus](https://github.com/TwinProduction/gatus) - ⛑ Gatus - Automated service health dashboard
* [gosuri/uilive](https://github.com/gosuri/uilive) - uilive is a go library for updating terminal output in realtime
* [matryer/vice](https://github.com/matryer/vice) - Go channels at horizontal scale (powered by message queues)
* [linclin/gopub](https://github.com/linclin/gopub) - vue.js(element框架)+golang(beego框架)开发的运维发布系统,支持git,jenkins版本发布,go ssh,BT两种文件传输方式选择,支持部署前准备任务和部署后任务钩子函数
* [haccer/subjack](https://github.com/haccer/subjack) - Subdomain Takeover tool written in Go
* [matthewmueller/joy](https://github.com/matthewmueller/joy) - A delightful Go to Javascript compiler (ON HOLD)
* [valyala/fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection
* [jiujuan/go-collection](https://github.com/jiujuan/go-collection) - :tulip: awesome awesome go, study golang from basic to proficient
* [trustmaster/goflow](https://github.com/trustmaster/goflow) - Flow-based and dataflow programming library for Go (golang)
* [clipperhouse/gen](https://github.com/clipperhouse/gen) - Type-driven code generation for Go
* [tal-tech/go-zero](https://github.com/tal-tech/go-zero) - go-zero is a web and rpc framework written in Go. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
* [AsynkronIT/protoactor-go](https://github.com/AsynkronIT/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin
* [docopt/docopt.go](https://github.com/docopt/docopt.go) - A command-line arguments parser that will make you smile.
* [microhq/examples](https://github.com/microhq/examples) - Go Micro examples. Moved to go-micro/examples.
* [cloudflare/redoctober](https://github.com/cloudflare/redoctober) - Go server for two-man rule style file encryption and decryption.
* [dghubble/go-twitter](https://github.com/dghubble/go-twitter) - Go Twitter REST and Streaming API v1.1
* [thecodingmachine/gotenberg](https://github.com/thecodingmachine/gotenberg) - A Docker-powered stateless API for converting HTML, Markdown and Office documents to PDF
* [eolinker/goku](https://github.com/eolinker/goku) - A Powerful HTTP API Gateway in pure golang！Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang开发的微服务网关，能够实现高性能 HTTP API 转发、服务编排、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。
* [sourcegraph/webloop](https://github.com/sourcegraph/webloop) - WebLoop: Scriptable, headless WebKit with a Go API. Like PhantomJS, but for Go.
* [sbinet/go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython2 C-API
* [rakyll/gom](https://github.com/rakyll/gom) - A visual interface to work with runtime profiling data for Go
* [songgao/water](https://github.com/songgao/water) - A simple TUN/TAP library written in native Go.
* [k6io/k6](https://github.com/k6io/k6) - A modern load testing tool, using Go and JavaScript - https://k6.io
* [360EntSecGroup-Skylar/excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [motemen/gore](https://github.com/motemen/gore) -   Yet another Go REPL that works nicely. Featured with line editing, code completion, and more.
* [360EntSecGroup-Skylar/goreporter](https://github.com/360EntSecGroup-Skylar/goreporter) - A Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [liamg/aminal](https://github.com/liamg/aminal) - A modern cross-platform terminal emulator in Go
* [go-zoo/bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer
* [uniqush/uniqush-push](https://github.com/uniqush/uniqush-push) - Uniqush is a free and open source software system which provides a unified push service for server side notification to apps on mobile devices.
* [nwidger/nintengo](https://github.com/nwidger/nintengo) - An NES emulator written in Go
* [tylerstillwater/graceful](https://github.com/tylerstillwater/graceful) - Graceful is a Go package enabling graceful shutdown of an http.Handler server.
* [klauspost/reedsolomon](https://github.com/klauspost/reedsolomon) - Reed-Solomon Erasure Coding in Go
* [kidoman/embd](https://github.com/kidoman/embd) - Embedded Programming Framework in Go
* [ryboe/q](https://github.com/ryboe/q) - Quick and dirty debugging output for tired Go programmers
* [jrallison/go-workers](https://github.com/jrallison/go-workers) - Sidekiq compatible background workers in golang
* [dshearer/jobber](https://github.com/dshearer/jobber) - An alternative to cron, with sophisticated status-reporting and error-handling
* [go-opencv/go-opencv](https://github.com/go-opencv/go-opencv) - Go bindings for OpenCV / 2.x API in gocv / 1.x API in opencv
* [envoyproxy/ratelimit](https://github.com/envoyproxy/ratelimit) - Go/gRPC service designed to enable generic rate limit scenarios from different types of applications.
* [golang/geo](https://github.com/golang/geo) - S2 geometry library in Go
* [justwatchcom/elasticsearch_exporter](https://github.com/justwatchcom/elasticsearch_exporter) - Elasticsearch stats exporter for Prometheus
* [rakyll/coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go
* [GetStream/vg](https://github.com/GetStream/vg) - Virtualgo: Easy and powerful workspace based development for go
* [keybase/kbfs](https://github.com/keybase/kbfs) - Keybase Filesystem (KBFS)
* [netlify/gocommerce](https://github.com/netlify/gocommerce) - A headless e-commerce for JAMstack sites
* [gorilla/handlers](https://github.com/gorilla/handlers) - A collection of useful middleware for Go HTTP services & web applications 🛃
* [JoelOtter/termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox
* [bradleyjkemp/memviz](https://github.com/bradleyjkemp/memviz) - Visualize your Go data structures using graphviz
* [mbrt/gmailctl](https://github.com/mbrt/gmailctl) - Declarative configuration for Gmail filters
* [micro/micro](https://github.com/micro/micro) - Distributed OS built for the Cloud
* [jwilder/docker-gen](https://github.com/jwilder/docker-gen) - Generate files from docker container meta-data
* [eolinker/Goku-api-gateway-1.x](https://github.com/eolinker/Goku-api-gateway-1.x) - A Powerful HTTP API Gateway in pure golang！Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang开发的微服务网关，能够实现高性能 HTTP API 转发、服务编排、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。
* [augmentable-dev/askgit](https://github.com/augmentable-dev/askgit) - Query git repositories with SQL. Generate reports, perform status checks, analyze codebases. 🔍 📊
* [tobyhede/go-underscore](https://github.com/tobyhede/go-underscore) -  Helpfully Functional Go -  A useful collection of Go utilities. Designed for programmer happiness.
* [siddontang/go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync MySQL data into elasticsearch
* [siddontang/go-mysql](https://github.com/siddontang/go-mysql) - a powerful mysql toolset with Go
* [eolinker/goku-api-gateway](https://github.com/eolinker/goku-api-gateway) - A Powerful HTTP API Gateway in pure golang！Goku API Gateway （中文名：悟空 API 网关）是一个基于 Golang开发的微服务网关，能够实现高性能 HTTP API 转发、服务编排、多租户管理、API 访问权限控制等目的，拥有强大的自定义插件系统可以自行扩展，并且提供友好的图形化配置界面，能够快速帮助企业进行 API 服务治理、提高 API 服务的稳定性和安全性。
* [writeas/writefreely](https://github.com/writeas/writefreely) - Build a digital writing community.
* [Arkweid/lefthook](https://github.com/Arkweid/lefthook) - Fast and powerful Git hooks manager for any type of projects.
* [fatih/pool](https://github.com/fatih/pool) - Connection pool for Go's net.Conn interface
* [compose/transporter](https://github.com/compose/transporter) - Sync data between persistence engines, like ETL only not stodgy
* [oragono/oragono](https://github.com/oragono/oragono) - A modern IRC server (daemon/ircd) written in Go.
* [cdipaolo/goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go (and so much more)
* [beego/bee](https://github.com/beego/bee) - Bee is a tool for helping develop with beego app framework.
* [peachdocs/peach](https://github.com/peachdocs/peach) - Peach is a web server for multi-language, real-time synchronization and searchable documentation.
* [Bytom/bytom](https://github.com/Bytom/bytom) - Official Go implementation of the Bytom protocol
* [eapache/go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang
* [loadimpact/k6](https://github.com/loadimpact/k6) - A modern load testing tool, using Go and JavaScript - https://k6.io
* [rivo/tview](https://github.com/rivo/tview) - Rich interactive widgets for your terminal UI, written in Go
* [lifei6671/mindoc](https://github.com/lifei6671/mindoc) - Golang实现的基于beego框架的接口在线文档管理系统
* [mikespook/gorbac](https://github.com/mikespook/gorbac) - goRBAC provides a lightweight role-based access control (RBAC) implementation in Golang.
* [nosequeldeebee/blockchain-tutorial](https://github.com/nosequeldeebee/blockchain-tutorial) - Write and publish your own blockchain in less than 200 lines of Go
* [guregu/null](https://github.com/guregu/null) - reasonable handling of nullable values
* [coreos/flannel](https://github.com/coreos/flannel) - flannel is a network fabric for containers, designed for Kubernetes
* [knadh/listmonk](https://github.com/knadh/listmonk) - High performance, self-hosted newsletter and mailing list manager with a modern dashboard. Go + VueJS.
* [loklak/loklak_go_api](https://github.com/loklak/loklak_go_api) - Go library client for using the Loklak API
* [hprose/hprose-golang](https://github.com/hprose/hprose-golang) - Hprose is a cross-language RPC. This project is Hprose for Golang.
* [rakyll/go-hardware](https://github.com/rakyll/go-hardware) - A directory of hardware related libs, tools, and tutorials for Go
* [laurent22/massren](https://github.com/laurent22/massren) - massren - easily rename multiple files using your text editor
* [xtaci/gonet](https://github.com/xtaci/gonet) - A Game Server Skeleton in golang.
* [abiosoft/ishell](https://github.com/abiosoft/ishell) - Library for creating interactive cli applications.
* [justinas/nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
* [jinzhu/configor](https://github.com/jinzhu/configor) - Golang Configuration tool that support YAML, JSON, TOML, Shell Environment
* [facebook/ent](https://github.com/facebook/ent) - An entity framework for Go
* [gogf/gf](https://github.com/gogf/gf) - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang.
* [qcrao/Go-Questions](https://github.com/qcrao/Go-Questions) - 从问题切入，串连  Go 语言相关的所有知识，融会贯通。
* [samsarahq/thunder](https://github.com/samsarahq/thunder) - ⚡️ A Go framework for rapidly building powerful graphql services
* [antonholmquist/jason](https://github.com/antonholmquist/jason) - Easy-to-use JSON Library for Go
* [adrianco/spigo](https://github.com/adrianco/spigo) - Simulate Protocol Interactions in Go
* [bazil/fuse](https://github.com/bazil/fuse) - FUSE library for Go.   go get bazil.org/fuse    
* [asim/go-plugins](https://github.com/asim/go-plugins) - Go Micro Plugins
* [shawn1m/overture](https://github.com/shawn1m/overture) - A customized DNS forwarder written in Go
* [asim/examples](https://github.com/asim/examples) - Go Micro examples
* [pravj/geopattern](https://github.com/pravj/geopattern) - :triangular_ruler: Create beautiful generative image patterns from a string in golang.
* [go-llvm/llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go
* [chihaya/chihaya](https://github.com/chihaya/chihaya) - A customizable, multi-protocol BitTorrent Tracker
* [justone/dockviz](https://github.com/justone/dockviz) - Visualizing Docker data
* [golang/gddo](https://github.com/golang/gddo) - Go Doc Dot Org
* [headzoo/surf](https://github.com/headzoo/surf) - Stateful programmatic web browsing in Go.
* [karldoenitz/Tigo](https://github.com/karldoenitz/Tigo) - Tigo is an HTTP web framework written in Go (Golang).It features a Tornado-like API with better performance.  Tigo是一款用Go语言开发的web应用框架，API特性类似于Tornado并且拥有比Tornado更好的性能。
* [sanity-io/litter](https://github.com/sanity-io/litter) - Litter is a pretty printer library for Go data structures to aid in debugging and testing.
* [astaxie/beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [gonitro/nitro](https://github.com/gonitro/nitro) - Nitro is a futuristic blazingly fast embeddable framework for distributed app development, IoT, edge and p2p.
* [ory/kratos](https://github.com/ory/kratos) - Never build user login, user registration, 2fa, profile management ever again! Works on any operating system, cloud, with any programming language, user interface, and user experience! Written in Go.
* [stack-labs/stack-rpc-tutorials](https://github.com/stack-labs/stack-rpc-tutorials) - Micro/Go-Micro 中文示例、教程、资料，源码解读
* [mattn/anko](https://github.com/mattn/anko) - Scriptable interpreter written in golang
* [rlmcpherson/s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Fast, concurrent, streaming access to Amazon S3, including gof3r, a CLI. http://godoc.org/github.com/rlmcpherson/s3gof3r
* [go-python/gopy](https://github.com/go-python/gopy) - gopy generates a CPython extension module from a go package.
* [asim/nitro](https://github.com/asim/nitro) - Nitro (formerly known as Go Micro) is a blazingly fast framework for distributed app development.
* [asim/nitro-plugins](https://github.com/asim/nitro-plugins) - Plugins for Nitro (formerly Go Micro)
* [asim/nitro-examples](https://github.com/asim/nitro-examples) - Learn Nitro by Example (formerly Go Micro)
* [sourcegraph/go-langserver](https://github.com/sourcegraph/go-langserver) - Go language server to add Go support to editors and other tools that use the Language Server Protocol (LSP)
* [ChimeraCoder/anaconda](https://github.com/ChimeraCoder/anaconda) - A Go client library for the Twitter 1.1 API
* [hunterloftis/pbr](https://github.com/hunterloftis/pbr) - a Physically Based Renderer (PBR) in Go
* [digitalocean/godo](https://github.com/digitalocean/godo) - DigitalOcean Go API client
* [micro/go-micro](https://github.com/micro/go-micro) - A Go standard library for microservices
* [miniflux/miniflux](https://github.com/miniflux/miniflux) - Minimalist and opinionated feed reader
* [filecoin-project/go-filecoin](https://github.com/filecoin-project/go-filecoin) - Filecoin Full Node Implementation in Go
* [micro-in-cn/tutorials](https://github.com/micro-in-cn/tutorials) - Micro/Go-Micro 中文示例、教程、资料，源码解读
* [square/go-jose](https://github.com/square/go-jose) - An implementation of JOSE standards (JWE, JWS, JWT) in Go
* [micro/go-plugins](https://github.com/micro/go-plugins) - Plugins for external infrastructure dependencies
* [henson/proxypool](https://github.com/henson/proxypool) - Golang实现的IP代理池
* [matryer/goblueprints](https://github.com/matryer/goblueprints) - Source code for Go Programming Blueprints
* [alecthomas/go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods
* [containous/traefik](https://github.com/containous/traefik) - The Cloud Native Edge Router
* [containous/yaegi](https://github.com/containous/yaegi) - Yaegi is Another Elegant Go Interpreter
* [kylesliu/awesome-golang-leetcode](https://github.com/kylesliu/awesome-golang-leetcode) - :memo: LeetCode of algorithms with golang solution(updating).
* [wenjianzhang/go-admin](https://github.com/wenjianzhang/go-admin) - 基于Gin + Vue + Element UI的前后端分离权限管理系统脚手架（包含了：基础用户管理功能，jwt鉴权，代码生成器，RBAC资源控制，表单构建等）文档：http://doc.zhangwj.com/go-admin-site/    Demo： http://www.zhangwj.com/#/login
* [hellofresh/janus](https://github.com/hellofresh/janus) - An API Gateway written in Go
* [jingweno/godzilla](https://github.com/jingweno/godzilla) - Godzilla is a ES2015 to Go source code transpiler and runtime
* [jaksi/sshesame](https://github.com/jaksi/sshesame) - A fake SSH server that lets everyone in and logs their activity
* [rs/rest-layer](https://github.com/rs/rest-layer) - REST Layer, Go (golang) REST API framework
* [qiniu/logkit](https://github.com/qiniu/logkit) - Very powerful server agent for collecting & sending logs & metrics with an easy-to-use web console.
* [jpmorganchase/quorum](https://github.com/jpmorganchase/quorum) - A permissioned implementation of Ethereum supporting data privacy
* [changkun/go-under-the-hood](https://github.com/changkun/go-under-the-hood) - 📚 Go Under The Hood: A Source Code Study of Go (1.14, WIP)
* [go-reform/reform](https://github.com/go-reform/reform) - A better ORM for Go, based on non-empty interfaces and code generation.
* [rcrowley/go-tigertonic](https://github.com/rcrowley/go-tigertonic) - A Go framework for building JSON web services inspired by Dropwizard
* [facebookincubator/ent](https://github.com/facebookincubator/ent) - An entity framework for Go
* [gopherjs/vecty](https://github.com/gopherjs/vecty) - Vecty: your frontend, in Go
* [augmentable-dev/gitqlite](https://github.com/augmentable-dev/gitqlite) - Query git repositories with SQL. Generate reports, perform status checks, analyze codebases. 🔍 📊
* [terraform-providers/terraform-provider-google](https://github.com/terraform-providers/terraform-provider-google) - Terraform Google Cloud Platform provider
* [hoisie/mustache](https://github.com/hoisie/mustache) - The mustache template language in Go
* [davecheney/gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time
* [smartystreets-prototypes/go-disruptor](https://github.com/smartystreets-prototypes/go-disruptor) - A port of the LMAX Disruptor to the Go language.
* [src-d/go-mysql-server](https://github.com/src-d/go-mysql-server) - An extensible MySQL server implementation in Go.
* [inconshreveable/log15](https://github.com/inconshreveable/log15) - Structured, composable logging for Go
* [qiniu/goplus](https://github.com/qiniu/goplus) - GoPlus - The Go+ language for data science
* [square/ghostunnel](https://github.com/square/ghostunnel) - A simple SSL/TLS proxy with mutual authentication for securing non-TLS services
* [bradfitz/goimports](https://github.com/bradfitz/goimports) - (old repo) Tool to fix (add, remove) your Go imports automatically.
* [itchyny/bed](https://github.com/itchyny/bed) - Binary editor written in Go
* [golang/snappy](https://github.com/golang/snappy) - The Snappy compression format in the Go programming language.
* [rsms/gotalk](https://github.com/rsms/gotalk) - Async peer communication protocol & library
* [apex/log](https://github.com/apex/log) - Structured logging package for Go.
* [mattbaird/elastigo](https://github.com/mattbaird/elastigo) - A Go (golang) based Elasticsearch client library.
* [talk-go/night](https://github.com/talk-go/night) - Weekly Go Online Meetup via Zoom and Bilibili｜Go 夜读｜由 SIG 成员维护｜通过 zoom 在线直播的方式分享 Go 相关的技术话题，每天大家在微信/telegram/Slack 上及时沟通交流编程技术话题。
* [sourcegraph/srclib](https://github.com/sourcegraph/srclib) - srclib is a polyglot code analysis library, built for hackability. It consists of language analysis toolchains (currently for Go and Java, with Python, JavaScript, and Ruby in beta) with a common output format, and a CLI tool for running the analysis.
* [SimonWaldherr/golang-examples](https://github.com/SimonWaldherr/golang-examples) - Go(lang) examples - (explain the basics of #golang)
* [benhoyt/goawk](https://github.com/benhoyt/goawk) - GoAWK: an AWK interpreter written in Go
* [sensu/uchiwa](https://github.com/sensu/uchiwa) - Uchiwa is a simple yet effective open-source dashboard for the Sensu monitoring framework.
* [braintree/manners](https://github.com/braintree/manners) - A polite Go HTTP server that shuts down gracefully.
* [jinzhu/gorm](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly (v2 is under development, PR based on master branch won't be accepted)
* [cloudson/gitql](https://github.com/cloudson/gitql) - 💊 A git query language
* [inlets/inlets](https://github.com/inlets/inlets) - Cloud Native Tunnel written in Go
* [siddontang/ledisdb](https://github.com/siddontang/ledisdb) - a high performance NoSQL powered by Go
* [bilibili/kratos](https://github.com/bilibili/kratos) - Kratos是bilibili开源的一套Go微服务框架，包含大量微服务相关框架及工具。
* [developer-learning/night-reading-go](https://github.com/developer-learning/night-reading-go) - Night-Reading-Go《Go 夜读》 > Share the related technical topics of Go every week through zoom online live broadcast, every day on the WeChat/Slack to communicate programming technology topics.      由 Go 夜读 SIG 成员维护，并通过 zoom 在线直播的方式分享 Go 相关的技术话题，每天大家在微信/Slack 上及时沟通交流编程技术话题。
* [goproxy/goproxy.cn](https://github.com/goproxy/goproxy.cn) - The most trusted Go module proxy in China.
* [maxence-charriere/app](https://github.com/maxence-charriere/app) - A WebAssembly framework to build GUI with Go, HTML and CSS.
* [mholt/certmagic](https://github.com/mholt/certmagic) - Automatic HTTPS for any Go program: fully-managed TLS certificate issuance and renewal
* [nlopes/slack](https://github.com/nlopes/slack) - Slack API in Go
* [gwuhaolin/livego](https://github.com/gwuhaolin/livego) - 纯 Go 写的直播服务器
* [colinmarc/hdfs](https://github.com/colinmarc/hdfs) - A native go client for HDFS
* [steve0hh/midas](https://github.com/steve0hh/midas) - Go implementation of MIDAS: Microcluster-Based Detector of Anomalies in Edge Streams
* [gookit/color](https://github.com/gookit/color) - A command-line color library with true color support, universal API methods and Windows support.


## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Veilair](https://github.com/veilair/) has waived all copyright and related or neighboring rights to this work.

[Back to top](#table-of-contents)
