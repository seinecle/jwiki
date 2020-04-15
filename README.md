# jwiki
[![Build Status](https://travis-ci.org/fastily/jwiki.svg?branch=master)](https://travis-ci.org/fastily/jwiki)
![JDK-11+](https://upload.wikimedia.org/wikipedia/commons/e/ef/Blue_JDK_11%2B_Shield_Badge.svg)
[![MediaWiki 1.31+](https://upload.wikimedia.org/wikipedia/commons/b/b2/Blue_MediaWiki_1.31%2B_Shield_Badge.svg)](https://www.mediawiki.org/wiki/MediaWiki)
[![License: GPL v3](https://upload.wikimedia.org/wikipedia/commons/8/86/GPL_v3_Blue_Badge.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

Programmatically accessing [Wikipedia](https://en.wikipedia.org/wiki/Main_Page)/[MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) via the [API](https://en.wikipedia.org/w/api.php) is hard ☹️.  I thought it didn't have to be, so I made it easy 😀.  jwiki lets you perform all sorts of crazy API calls with 1️⃣ line of Java.  

Yes, **one** line.  

It's so easy that _anyone_ (including your grandma 👵🏻) can write a program that works with MediaWiki.

Not convinced?  Try out the [examples](https://github.com/fastily/jwiki/wiki/Examples).

## Download
#### Maven
```xml
<dependency>
  <groupId>org.fastily</groupId>
  <artifactId>jwiki</artifactId>
  <version>1.8.0</version>
</dependency>
```

#### Gradle
```groovy
implementation 'org.fastily:jwiki:1.8.0'
```

⚠️ ATTENTION: COORDINATES HAVE CHANGED (since 1.7.0)!  jwiki's new groupId is `org.fastily`

## Build
Build and publish (install) jwiki on your computer with
```bash
./gradlew publishToMavenLocal
```

## Resources
* [Examples](https://github.com/fastily/jwiki/wiki/Examples)
* [Javadocs](https://fastily.github.io/jwiki/docs/jwiki/)

Please create a new [issue](https://github.com/fastily/jwiki/issues) for bug reports and/or feature requests.