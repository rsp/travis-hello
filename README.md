Travis Hello [![License][license-img]][license-url] [![GitHub Stars][stars-img]][stars-url] [![GitHub Forks][forks-img]][forks-url] [![GitHub Watchers][watchers-img]][watchers-url] [![Tweet][tweet-img]][tweet-url]
=
Simple Travis examples with different languages.

It show you how you can use the Travis continuous integration system to automaticcaly have your code tested on every change. See [Quick start](#quick-start) below for instructions on how to use those examples for your own projects.

Examples are currently available for:

* [**C++**][cpp-url] (default GCC and Clang compilers)
* [**Modern C++**][modern-cpp-url] (recent versions of GCC and Clang compilers)

Why a separate vesrions for C++? The one with older compiers is faster but the one with newer compilers has support for C++14 and beyond. See [travis-hello-modern-cpp][modern-cpp-url] for details.

This is work in progress, more examples will be added in the future.
To request more languages or other CI systems, please [post an issue][issues-url].

Quick start
-----------

* you need an account on [GitHub][github-website]
* you need to log into [Travis][travis-website] using your GitHub login
* create a [new project on GitHub](https://github.com/new)
* go to [Travis profile](https://travis-ci.org/profile) and click "Sync account"
* on the same page, turn on the checkbox next to your project's name

From now on, when you commit a file called `.travis.yml` into your project on GitHub, Travis will automatically start testing your project. You can base your `.travis.yml` file on one of the files from the specific examples linked above, e.g. [travis-hello-cpp][cpp-url] for C++ projects. As long as your project can be built with `make` and tested with `make test` then putting `.travis.yml` from one of my examples should be enough, but you need to use the right example suitable for your project - like e.g. [travis-hello-modern-cpp][modern-cpp-url] for modern versions of C++ etc. If you don't have `make` and `make test` already working then you can see other files like `Makefile` and `test` from the examples for a good place to start.

Issues
------
For any bug reports or feature requests please
[post an issue on GitHub][issues-url].

Author
------
[**Rafał Pocztarski**](https://pocztarski.com/)
<br/>
[![Follow on GitHub][github-follow-img]][github-follow-url]
[![Follow on Twitter][twitter-follow-img]][twitter-follow-url]
<br/>
[![Follow on Stack Exchange][stackexchange-img]][stackoverflow-url]

License
-------
MIT License (Expat). See [LICENSE.md](LICENSE.md) for details.

[github-website]: https://github.com/
[travis-website]: https://travis-ci.org/
[cpp-url]: https://github.com/rsp/travis-hello-cpp
[modern-cpp-url]: https://github.com/rsp/travis-hello-modern-cpp
[cpp-travis-url]: https://travis-ci.org/rsp/travis-hello-cpp
[cpp-travis-img]: https://travis-ci.org/rsp/travis-hello-cpp.svg?branch=master
[modern-cpp-travis-url]: https://travis-ci.org/rsp/travis-hello-modern-cpp
[modern-cpp-travis-img]: https://travis-ci.org/rsp/travis-hello-modern-cpp.svg?branch=master
[github-url]: https://github.com/rsp/travis-hello
[readme-url]: https://github.com/rsp/travis-hello#readme
[issues-url]: https://github.com/rsp/travis-hello/issues
[stars-url]: https://github.com/rsp/travis-hello/stargazers
[watchers-url]: https://github.com/rsp/travis-hello/watchers
[forks-url]: https://github.com/rsp/travis-hello/network/members
[stars-img]: https://img.shields.io/github/stars/rsp/travis-hello.svg?style=social&amp;label=Stars
[forks-img]: https://img.shields.io/github/forks/rsp/travis-hello.svg?style=social&amp;label=Forks
[watchers-img]: https://img.shields.io/github/watchers/rsp/travis-hello.svg?style=social&amp;label=Watchers
[tweet-img]: https://img.shields.io/twitter/url/https/github.com/rsp/travis-hello.svg?style=social
[tweet-url]: https://twitter.com/intent/tweet?text=%23Travis+examples+by+@pocztarski:&url=https%3A%2F%2Fgithub.com%2Frsp%2Ftravis-hello
[license-url]: https://github.com/rsp/travis-hello/blob/master/LICENSE.md
[license-img]: https://img.shields.io/github/license/rsp/travis-hello.svg
[travis-url]: https://travis-ci.org/rsp/travis-hello
[travis-img]: https://travis-ci.org/rsp/travis-hello.svg?branch=master
[snyk-url]: https://snyk.io/test/github/rsp/travis-hello
[snyk-img]: https://snyk.io/test/github/rsp/travis-hello/badge.svg
[github-follow-url]: https://github.com/rsp
[github-follow-img]: https://img.shields.io/github/followers/rsp.svg?style=social&label=Follow
[twitter-follow-url]: https://twitter.com/intent/follow?screen_name=pocztarski
[twitter-follow-img]: https://img.shields.io/twitter/follow/pocztarski.svg?style=social&label=Follow
[stackoverflow-url]: https://stackoverflow.com/users/613198/rsp
[stackexchange-url]: https://stackexchange.com/users/303952/rsp
[stackexchange-img]: https://stackexchange.com/users/flair/303952.png
[gitlab-url]: https://gitlab.com/rsp/travis-hello
[gitlabci-img]: https://gitlab.com/rsp/travis-hello/badges/master/build.svg
[gitlabci-url]: https://gitlab.com/rsp/travis-hello/builds
