---
permalink: /freebsd
title: FreeBSD
category: os
releasePolicyLink: https://www.freebsd.org/security/#sup
activeSupportColumn: false
releaseDateColumn: false
releaseColumn: false
versionCommand: freebsd-version
releases:
-   releaseCycle: "releng/13.1"
    eol: false
    # 13.2-RELEASE + 3 months
    link: https://www.freebsd.org/releases/13.1R/announce/
    releaseDate: 2022-05-16
-   releaseCycle: "releng/13.0"
    eol: 2022-08-16
    releaseDate: 2021-04-13
-   releaseCycle: "stable/13"
    eol: 2026-01-31
-   releaseCycle: "releng/12.3"
    eol: false
    # EOL will be 12.4-RELEASE + 3 months
    releaseDate: 2021-12-07
-   releaseCycle: "releng/12.2"
    eol: 2022-03-31
    releaseDate: 2020-10-27
-   releaseCycle: "releng/12.1"
    eol: 2021-01-31
    releaseDate: 2019-11-04
-   releaseCycle: "stable/12"
    eol: 2023-12-31
-   releaseCycle: "releng/11.4"
    eol: 2021-09-30
    releaseDate: 2020-06-16
-   releaseCycle: "stable/11"
    eol: 2021-09-30
-   releaseCycle: "releng/10.4"
    eol: 2018-10-31
    releaseDate: 2017-10-03
-   releaseCycle: "releng/10.3"
    eol: 2018-04-30
    releaseDate: 2016-04-04
-   releaseCycle: "releng/10.2"
    eol: 2016-12-31
    releaseDate: 2015-08-13
-   releaseCycle: "releng/10.1"
    eol: 2016-12-31
    releaseDate: 2014-11-14
-   releaseCycle: "releng/10.0"
    eol: 2015-02-28
    releaseDate: 2014-01-20
-   releaseCycle: "releng/9.3"
    eol: 2016-12-31
    releaseDate: 2014-07-16
-   releaseCycle: "releng/9.2"
    eol: 2014-12-31
    releaseDate: 2013-09-30
-   releaseCycle: "releng/9.1"
    eol: 2014-12-31
    releaseDate: 2012-12-30
-   releaseCycle: "releng/9.0"
    eol: 2013-03-31
    releaseDate: 2012-01-10
-   releaseCycle: "stable/9"
    eol: 2016-12-31
-   releaseCycle: "releng/8.4"
    eol: 2015-08-01
    releaseDate: 2013-06-09
-   releaseCycle: "releng/8.3"
    eol: 2014-04-30
    releaseDate: 2012-04-18
-   releaseCycle: "releng/8.2"
    eol: 2012-07-31
    releaseDate: 2011-02-24
-   releaseCycle: "releng/8.1"
    eol: 2012-07-31
    releaseDate: 2010-07-23
-   releaseCycle: "releng/8.0"
    eol: 2010-11-30
    releaseDate: 2009-11-25
-   releaseCycle: "stable/8"
    eol: 2015-08-01
-   releaseCycle: "releng/7.4"
    eol: 2013-02-28
    releaseDate: 2011-02-24
-   releaseCycle: "releng/7.3"
    eol: 2012-03-31
    releaseDate: 2010-03-23
-   releaseCycle: "releng/7.2"
    eol: 2010-06-30
    releaseDate: 2009-03-04
-   releaseCycle: "releng/7.1"
    eol: 2011-02-28
    releaseDate: 2009-01-04
-   releaseCycle: "releng/7.0"
    eol: 2009-04-30
    releaseDate: 2008-02-27
-   releaseCycle: "stable/7"
    eol: 2013-02-28
-   releaseCycle: "releng/6.4"
    eol: 2010-11-30
    releaseDate: 2008-11-28
-   releaseCycle: "releng/6.3"
    eol: 2010-01-31
    releaseDate: 2008-01-18
-   releaseCycle: "releng/6.2"
    eol: 2008-05-31
    releaseDate: 2007-01-15
-   releaseCycle: "releng/6.1"
    eol: 2008-05-31
    releaseDate: 2006-05-09
-   releaseCycle: "releng/6.0"
    eol: 2007-01-31
    releaseDate: 2005-11-04
-   releaseCycle: "stable/6"
    eol: 2010-11-30
-   releaseCycle: "releng/5.5"
    eol: 2008-05-31
    releaseDate: 2006-05-25
-   releaseCycle: "releng/5.4"
    eol: 2006-10-31
    releaseDate: 2005-05-09
-   releaseCycle: "releng/5.3"
    eol: 2006-10-31
    releaseDate: 2004-11-06
-   releaseCycle: "stable/5"
    eol: 2008-05-31
-   releaseCycle: "releng/4.11"
    eol: 2007-01-31
    releaseDate: 2005-01-25
-   releaseCycle: "stable/4"
    eol: 2007-01-31

---

> [FreeBSD](https://www.freebsd.org) is an operating system used to power modern servers, desktops, and embedded platforms.

Each release is supported by the Security Officer for a limited time only. Under the current support model, each major version's stable branch is explicitly supported for 5 years, while each individual point release is only supported for three months after the next point release.

The Expected EoL (end-of-life) column indicates the earliest date on which support for that branch or release will end. Please note that these dates may be pushed back if circumstances warrant it.

The FreeBSD Security Officer provides security advisories for `-STABLE` Branches and the Security Branches. Advisories are not issued for the `-CURRENT` Branch, which is primarily oriented towards FreeBSD developers.

The -STABLE branch tags have names like `stable/10`. The corresponding builds have names like `FreeBSD 10.1-STABLE`.

Each FreeBSD Release has an associated Security Branch. The Security Branch tags have names like `releng/10.1`. The corresponding builds have names like `FreeBSD 10.1-RELEASE-p4`.
