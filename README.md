# MediaConch website

## Installation

### Debian 8

```
apt-get install ruby ruby-dev nodejs git gcc make zlib1g-dev
gem install github-pages
jekyll build
```

### Windows

```
http://rubyinstaller.org/downloads/
rubyinstaller
DevKit
gem install github-pages
```

### Mac

Ruby is required. Please use Ruby version >= `ruby-2.3.0` Using the `rvm` package manager is recommended.  

1. Clone repository
2. Navigate to repository
3. If you don't already have it, `gem install bundler`
4. Run `bundle`
5. Run `jekyll serve --baseurl='/MediaConch'`
6. Navigate browser to http://localhost:4000/MediaConch/

## Table of Repositories

#### [MediaConch](https://github.com/MediaArea/MediaConch)
The original repository for the MediaConch project, this repository holds all public documentation related to Phase I of the project (the design phase) and some metadata-related work.

#### [MediaConch_SourceCode](https://github.com/MediaArea/MediaConch_SourceCode)
This repository hosts the source code for MediaConch, the GUI.

#### [MediaConchOnline](https://github.com/MediaArea/MediaConchOnline)
This is the source code for MediaConchOnline, the online version of the MediaConch shell.

#### [MediaConch-Website](https://github.com/MediaArea/MediaConch-Website)
This is the repository for content hosted on [https://mediaarea.net/MediaConch/](https://mediaarea.net/MediaConch/).

#### [MediaAreaXml](https://github.com/MediaArea/MediaAreaXml)
This repository holds XSD (XML Schema Definitions) for MediaConch, MediaInfo, and MediaTrace.

#### [MediaConch_SampleFiles](https://github.com/MediaArea/MediaConch_SampleFiles)
This repository contains sample files used to test MediaConch.

#### [MediaConch_MKVSurvey](https://github.com/MediaArea/MediaConch_MKVSurvey)
This repository holds a research corpus used in the development of the MediaConch.
