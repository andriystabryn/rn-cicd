## Compare Table
| CI/CD | Time | Note |
|---|---|---|
| semaphoreci | 18:11 | yarn install & pod install & build & artifact push |
| GitHub | 33:11 | yarn install & pod install & build  |
|  |  |  |

## semaphoreci opensurce
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


## GitHub
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