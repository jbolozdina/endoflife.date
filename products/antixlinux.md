---
permalink: /antix
alternate_urls:
-   /antixlinux
-   /antix-linux
title: antiX
category: os
releasePolicyLink: https://www.antixforum.com/forums/topic/when-is-end-of-support-for-stable-antix-versions-17-19/#post-26424
activeSupportColumn: true
versionCommand: cat /etc/os-release
releaseColumn: true
releaseDateColumn: true
iconSlug: NA
releaseLabel: "__RELEASE_CYCLE__ (__CODENAME__)"
purls:
-   purl: pkg:os/antix
auto:
-   distrowatch: antix
    regex: '^Distribution Release: antiX (?P<major>\d)\.(?P<minor>\d)$'
releases:
-   releaseCycle: "21"
    codename: "Grup Yorum"
    releaseDate: 2021-10-31
    latest: "22"
    latestRelaseDate: 2022-10-19
    support: 2024-06-30
    eol: 2026-06-30
    link: https://antixlinux.com/antix-22-released/
-   releaseCycle: "19"
    codename: "Grup Yorum"
    releaseDate: 2019-10-17
    latest: "19.5"
    latestRelaseDate: 2022-01-25
    support: 2022-09-10
    eol: 2024-06-30
    link: https://antixlinux.com/antix-19-5-point-release-update/
-   releaseCycle: "17"
    codename: "Helen Keller"
    releaseDate: 2017-10-24
    latest: "17.4.1"
    latestRelaseDate: 2019-03-28
    support: 2020-06-05
    eol: 2022-06-30
    link: https://antixlinux.com/antix-17-4-1-now-out/
-   releaseCycle: "16"
    codename: "Berta Cáceres"
    releaseDate: 2016-06-27
    latest: "16.3"
    latestRelaseDate: 2017-12-21
    support: 2018-06-23
    eol: 2020-06-30
    link: https://antixlinux.com/antix-16-3-full-iso-files-available/
-   releaseCycle: "15"
    codename: "Berta Cáceres"
    releaseDate: 2015-06-30
    latest: "15"
    latestRelaseDate: 2015-06-30
    support: 2018-06-23
    eol: 2020-06-30
    link: https://antixlinux.com/forum-archive/antix-15-released-t5697.html

---

> [antiX](https://antixlinux.com/) is a lightweight desktop-oriented systemd-free GNU/Linux distribution based on Debian's stable branch releases. AntiX Linux uses the lightweight "antiX Magic" IceWM-based desktop which allows for antiX to run smoothly on old and new hardware.

There are several releases of antiX supported concurrently.  These typically follow Debian's periods of active development and extended long-term support, which provides security patches to a limited set of packages.  Often this equates to ~2 years of active support and 2 years of long-term security patch support.

AntiX officially supports 32-bit non-PAE (i586-compatible), 32-bit PAE (i686-compatible) and 64-bit x86 processors.
