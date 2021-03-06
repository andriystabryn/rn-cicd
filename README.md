## Compare Table
| CI/CD | Time | CI URL | Note |
|---|---|---|---|
| semaphoreci | 18:11 | https://andriystabryn.semaphoreci.com/workflows/edf0281c-6f3c-4230-842d-b30002e6dabd?pipeline_id=c596317c-bb0a-42f8-b2d8-f5bde5ec7368 | yarn install & pod install & build & artifact push |
| GitHub | 33:11 | https://github.com/andriystabryn/rn-cicd/runs/4896453645?check_suite_focus=true | yarn install & pod install & build  |
| appcircle | not finished (errors) |  |
| bitrise | 09:05 | https://app.bitrise.io/build/927ec155-8d1e-4b5f-99b6-be353456442b#?tab=log | yarn install & pod install & build & artifact export |
| codemagic | 18:04 (probably unstable) | https://codemagic.io/app/61ee9d994d0eb94abcddf07d/build/61eeba1c298f33a38ebc4f74 - (!) haven't found a way to share build publically with free account | yarn install & pod install & build & artifact export
| AWS | required to buy a mac  |  |
| circleci | required a paid account | https://app.circleci.com/pipelines/github/andriystabryn/rn-cicd |  |

## semaphoreci opensurce
```
System:
    OS: macOS 11.5.1
    CPU: (4) x64 Intel(R) Xeon(R) CPU E5-2697 v2 @ 2.70GHz
    Memory: 3.83 GB / 8.00 GB
    Shell: 3.2.57 - /bin/bash
  Binaries:
    Node: 16.10.0 - /var/folders/rg/92ky7bj54xj6pcv5l24g6l_00000gn/T/yarn--1642680931348-0.7620712985818772/node
    Yarn: 1.22.15 - /var/folders/rg/92ky7bj54xj6pcv5l24g6l_00000gn/T/yarn--1642680931348-0.7620712985818772/yarn
    npm: 7.24.0 - /usr/local/bin/npm
    Watchman: 2021.09.27.00 - /usr/local/bin/watchman
  Managers:
    CocoaPods: 1.11.2 - /Users/semaphore/.rbenv/shims/pod
    Homebrew: 3.2.14 - /usr/local/bin/brew
    pip3: 21.2.4 - /usr/local/bin/pip3
    RubyGems: 3.0.3.1 - /Users/semaphore/.rbenv/shims/gem
  Utilities:
    Make: 3.81 - /usr/bin/make
    GCC: 12.5.1. - /usr/bin/gcc
    Git: 2.32.0 - /usr/local/bin/git
    Clang: 12.0.5 - /usr/bin/clang
  Servers:
    Apache: 2.4.46 - /usr/sbin/apachectl
  SDKs:
    iOS SDK:
      Platforms: iOS 14.5, DriverKit 20.4, macOS 11.3, tvOS 14.5, watchOS 7.4
 
    Nano: 2.0.6 - /usr/bin/nano
    Vim: 8.2 - /usr/bin/vim
    Xcode: 12.5.1/12E507 - /usr/bin/xcodebuild
  Languages:
    Bash: 3.2.57 - /bin/bash
    Java: javac 14 - /usr/bin/javac
    Perl: 5.30.2 - /usr/bin/perl
    PHP: 7.3.24 - /usr/bin/php
    Python: 2.7.16 - /usr/bin/python
    Python3: 3.9.7 - /usr/local/bin/python3
    Ruby: 2.6.8 - /Users/semaphore/.rbenv/shims/ruby
  Databases:
    SQLite: 3.32.3 - /usr/bin/sqlite3
```

## GitHub
```
System:
    OS: macOS 11.6.2
    CPU: (3) x64 Intel(R) Xeon(R) CPU E5-1650 v2 @ 3.50GHz
    Memory: 4.97 GB / 14.00 GB
    Shell: 3.2.57 - /bin/bash
  Binaries:
    Node: 14.18.3 - /var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/yarn--1642769268501-0.1598469361069499/node
    Yarn: 1.22.17 - /var/folders/24/8k48jl6d249_n_qfxwsl6xvm0000gn/T/yarn--1642769268501-0.1598469361069499/yarn
    npm: 6.14.15 - ~/hostedtoolcache/node/14.18.3/x64/bin/npm
  Managers:
    Cargo: 1.58.0 - ~/.cargo/bin/cargo
    CocoaPods: 1.11.2 - /usr/local/lib/ruby/gems/2.7.0/bin/pod
    Composer: 2.2.4 - /usr/local/bin/composer
    Gradle: 7.3.3 - /usr/local/bin/gradle
    Homebrew: 3.3.11 - /usr/local/bin/brew
    Maven: 3.8.4 - /usr/local/bin/mvn
    pip2: 20.3.4 - /usr/local/bin/pip2
    pip3: 21.3.1 - /usr/local/bin/pip3
    RubyGems: 3.2.33 - /usr/local/opt/ruby@2.7/bin/gem
  Utilities:
    Bazel: 5.0.0 - /usr/local/bin/bazel
    CMake: 3.22.1 - /usr/local/bin/cmake
    Make: 3.81 - /usr/bin/make
    GCC: 13.1. - /usr/bin/gcc
    Git: 2.34.1 - /usr/local/bin/git
    Clang: 13.0.0 - /usr/bin/clang
    Subversion: 1.14.1 - /usr/local/bin/svn
  Servers:
    Apache: 2.4.52 - /usr/local/bin/apachectl
    Nginx: 1.21.5 - /usr/local/bin/nginx
  SDKs:
    iOS SDK:
      Platforms: DriverKit 21.0.1, iOS 15.0, macOS 12.0, tvOS 15.0, watchOS 8.0
    Android SDK:
      API Levels: 27, 28, 29, 30, 31, 32
      Build Tools: 27.0.0, 27.0.1, 27.0.2, 27.0.3, 28.0.0, 28.0.1, 28.0.2, 28.0.3, 29.0.0, 29.0.1, 29.0.2, 29.0.3, 30.0.0, 30.0.1, 30.0.2, 30.0.3, 31.0.0, 32.0.0
      Android NDK: 21.4.7075529
  IDEs:
    Nano: 2.0.6 - /usr/bin/nano
    Vim: 8.2 - /usr/bin/vim
    Xcode: 13.1/13A1030d - /usr/bin/xcodebuild
  Languages:
    Bash: 3.2.57 - /bin/bash
    Go: 1.15.15 - /usr/local/bin/go
    Java: 1.8.0_312 - /usr/bin/javac
    Perl: 5.34.0 - /usr/local/bin/perl
    PHP: 8.1.1 - /usr/local/bin/php
    Python: 2.7.18 - /usr/local/bin/python
    Python3: 3.9.10 - /usr/local/bin/python3
    Ruby: 2.7.5 - /usr/local/opt/ruby@2.7/bin/ruby
    Rust: 1.58.0 - /Users/runner/.cargo/bin/rustc
  Databases:
    MongoDB: 5.0.5 - /usr/local/bin/mongo
    PostgreSQL: 14.1 - /usr/local/bin/postgres
    SQLite: 3.32.2 - /Users/runner/Library/Android/sdk/platform-tools/sqlite3
  Browsers:
    Chrome: 97.0.4692.71
    Edge: 97.0.1072.62
    Firefox: 96.0.1
    Safari: 15.2
```

## Bitrise
```
  System:
    OS: macOS 12.0.1
    CPU: (8) x64 Intel(R) Core(TM) i7-8700B CPU @ 3.20GHz
    Memory: 30.20 GB / 35.00 GB
    Shell: 3.2.57 - /bin/bash
  Binaries:
    Node: 12.22.6 - /usr/local/bin/node
    Yarn: 1.22.11 - /usr/local/bin/yarn
    npm: 6.14.15 - /usr/local/bin/npm
    Watchman: 2021.08.30.00 - /usr/local/bin/watchman
  Managers:
    CocoaPods: 1.11.2 - /Users/vagrant/.rbenv/shims/pod
    Gradle: 7.2 - /usr/local/bin/gradle
    Homebrew: 3.3.9 - /usr/local/bin/brew
    Maven: 3.8.2 - /usr/local/bin/mvn
    pip3: 21.2.4 - /usr/local/bin/pip3
    RubyGems: 3.0.3 - /Users/vagrant/.rbenv/shims/gem
  Utilities:
    CMake: 3.21.2 - /usr/local/bin/cmake
    Make: 3.81 - /usr/bin/make
    GCC: 13.2.1. - /usr/bin/gcc
    Git: 2.33.0 - /usr/local/bin/git
    Clang: 13.0.0 - /usr/bin/clang
    Mercurial: 5.9.1 - /usr/local/bin/hg
  Servers:
    Apache: 2.4.48 - /usr/sbin/apachectl
  SDKs:
    iOS SDK:
      Platforms: DriverKit 21.2, iOS 15.2, macOS 12.1, tvOS 15.2, watchOS 8.3
    Android SDK:
      API Levels: 15, 17, 19, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30
      Build Tools: 19.1.0, 21.1.2, 22.0.1, 23.0.3, 24.0.3, 25.0.3, 26.0.1, 26.0.2, 27.0.0, 27.0.1, 27.0.2, 27.0.3, 28.0.0, 28.0.1, 28.0.2, 28.0.3, 29.0.0, 29.0.1, 29.0.2, 29.0.3, 30.0.0, 30.0.1, 30.0.2, 30.0.3
      System Images: android-26 | Google APIs Intel x86 Atom, android-28 | Google APIs Intel x86 Atom_64, android-29 | Google APIs Intel x86 Atom, android-30 | Google APIs Intel x86 Atom
      Android NDK: 21.4.7075529
  IDEs:
    Nano: 2.0.6 - /usr/bin/nano
    Vim: 8.2 - /usr/bin/vim
    Xcode: 13.2.1/13C100 - /usr/bin/xcodebuild
  Languages:
    Bash: 3.2.57 - /bin/bash
    Go: 1.16.7 - /usr/local/bin/go
    Java: 11.0.11 - /Users/vagrant/.jenv/shims/javac
    Perl: 5.30.3 - /usr/bin/perl
    Python: 2.7.18 - /usr/bin/python
    Python3: 3.9.7 - /usr/local/bin/python3
    Ruby: 2.6.5 - /Users/vagrant/.rbenv/shims/ruby
  Databases:
    SQLite: 3.36.0 - /usr/bin/sqlite3
```

## Codemagic
```
  System:
    OS: macOS 11.6.2
    CPU: (4) x64 Intel(R) Core(TM) i7-3615QM CPU @ 2.30GHz
    Memory: 3.85 GB / 8.00 GB
    Shell: 5.8 - /bin/zsh
  Binaries:
    Node: 14.15.5 - /usr/local/bin/node
    Yarn: 1.22.17 - /usr/local/bin/yarn
    npm: 8.1.4 - /usr/local/bin/npm
  Managers:
    CocoaPods: 1.11.2 - /Users/builder/.rbenv/shims/pod
    Composer: 2.0.9 - /usr/local/bin/composer
    Gradle: 7.3.1 - /usr/local/bin/gradle
    Homebrew: 3.3.9 - /usr/local/bin/brew
    Maven: 3.8.4 - /usr/local/bin/mvn
    pip3: 21.1.2 - ~/.pyenv/versions/3.8.7/bin/pip3
    RubyGems: 3.2.33 - /Users/builder/.rbenv/shims/gem
  Utilities:
    CMake: 3.22.1 - /usr/local/bin/cmake
    Make: 3.81 - /usr/bin/make
    GCC: 13.2. - /usr/bin/gcc
    Git: 2.34.1 - /usr/local/bin/git
    Clang: 13.0.0 - /usr/bin/clang
    Mercurial: 6.0 - /usr/local/bin/hg
  Servers:
    Apache: 2.4.51 - /usr/sbin/apachectl
  Virtualization:
    Docker: 20.10.2 - /usr/local/bin/docker
  SDKs:
    iOS SDK:
      Platforms: DriverKit 21.2, iOS 15.2, macOS 12.1, tvOS 15.2, watchOS 8.3
    Android SDK:
      API Levels: 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32
      Build Tools: 19.1.0, 20.0.0, 21.1.2, 22.0.1, 23.0.1, 23.0.2, 23.0.3, 24.0.0, 24.0.1, 24.0.2, 24.0.3, 25.0.0, 25.0.1, 25.0.2, 25.0.3, 26.0.0, 26.0.1, 26.0.2, 26.0.3, 27.0.0, 27.0.1, 27.0.2, 27.0.3, 28.0.0, 28.0.1, 28.0.2, 28.0.3, 29.0.0, 29.0.1, 29.0.2, 29.0.3, 30.0.0, 30.0.1, 30.0.2, 30.0.3, 31.0.0, 32.0.0, 32.0.0
      System Images: android-29 | Google Play Intel x86 Atom
      Android NDK: 23.1.7779620
  IDEs:
    Android Studio: 4.1 AI-201.8743.12.41.7042882
    Nano: 2.0.6 - /usr/bin/nano
    Vim: 8.2 - /usr/bin/vim
    Xcode: 13.2.1/13C100 - /usr/bin/xcodebuild
  Languages:
    Bash: 3.2.57 - /bin/bash
    Go: 1.17.5 - /usr/local/bin/go
    Java: 11.0.13 - /usr/bin/javac
    Perl: 5.30.2 - /usr/bin/perl
    PHP: 7.3.29 - /usr/bin/php
    Python: 3.8.7 - /Users/builder/.pyenv/versions/3.8.7/bin/python
    Python3: 3.8.7 - /Users/builder/.pyenv/versions/3.8.7/bin/python3
    Ruby: 2.7.2 - /Users/builder/.rbenv/shims/ruby
  Databases:
    SQLite: 3.32.2 - /usr/local/share/android-sdk/platform-tools/sqlite3
```