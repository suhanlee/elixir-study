# elixir-study
elixir study guides


# Elixir IDE Plugin

# Install Language

## Install Erlang 
- https://github.com/kerl/kerl
``` 
$ brew install kerl
Updating Homebrew...
==> Auto-updated Homebrew!
Updated 3 taps (homebrew/core, caskroom/versions, caskroom/cask).
==> New Formulae
mariadb-connector-odbc
==> Updated Formulae
amber                     bdw-gc                    dnscrypt-proxy            gitbucket                 hadolint                  joplin                    lysp                      oniguruma                 spigot
angular-cli               certbot                   dscanner                  godep                     hg-fast-export            kite                      mapnik                    picard-tools              vault
arangodb                  crystal-icr               ecl                       gradle                    htslib                    libphonenumber            micro                     s-search                  w3m
augeas                    crystal-lang              firebase-cli              guile                     iron-functions            libtensorflow             mp3gain                   sagittarius-scheme        xtensor
autogen                   diamond                   fn                        guile@2.0                 jenkins-job-builder       lynis                     neko                      samtools                  zile

==> Downloading https://github.com/kerl/kerl/archive/1.8.1.tar.gz
==> Downloading from https://codeload.github.com/kerl/kerl/tar.gz/1.8.1
######################################################################## 100.0%
==> Caveats
Bash completion has been installed to:
  /usr/local/etc/bash_completion.d

zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/kerl/1.8.1: 6 files, 95.6KB, built in 4 seconds

$ kerl list releases
R10B-0 R10B-10 R10B-1a R10B-2 R10B-3 R10B-4 R10B-5 R10B-6 R10B-7 R10B-8 R10B-9 R11B-0 R11B-1 R11B-2 R11B-3 R11B-4 R11B-5 R12B-0 R12B-1 R12B-2 R12B-3 R12B-4 R12B-5 R13A R13B01 R13B02-1 R13B02 R13B03 R13B04 R13B R14A R14B01 R14B02 R14B03 R14B04 R14B R14B_erts-5.8.1.1 R15B01 R15B02 R15B02_with_MSVCR100_installer_fix R15B03-1 R15B03 R15B R16A_RELEASE_CANDIDATE R16B01 R16B02 R16B03-1 R16B03 R16B 17.0-rc1 17.0-rc2 17.0 17.1 17.3 17.4 17.5 18.0 18.1 18.2 18.2.1 18.3 19.0 19.1 19.2 19.3 20.0 20.1 20.2

$ kerl build 20.2 20.2
Downloading otp_src_20.2.tar.gz to /Users/Kyle/.kerl/archives
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   178  100   178    0     0    114      0  0:00:01  0:00:01 --:--:--   114
100 83.1M  100 83.1M    0     0   164k      0  0:08:37  0:08:37 --:--:--  144k
Getting checksum file from erlang.org...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   178  100   178    0     0    121      0  0:00:01  0:00:01 --:--:--   121
100 28110  100 28110    0     0   7429      0  0:00:03  0:00:03 --:--:-- 22470
Verifying archive checksum...
Checksum verified (429f126fd3e1e29a1eb1be2f8a15dc90)
Extracting source code
Building Erlang/OTP 20.2 (20.2), please wait...
APPLICATIONS DISABLED (See: /Users/Kyle/.kerl/builds/20.2/otp_build_20.2.log)
 * odbc           : ODBC library - header check failed

APPLICATIONS INFORMATION (See: /Users/Kyle/.kerl/builds/20.2/otp_build_20.2.log)
 * wx             : wxWidgets not found, wx will NOT be usable

DOCUMENTATION INFORMATION (See: /Users/Kyle/.kerl/builds/20.2/otp_build_20.2.log)
 * documentation  :
 *                  fop is missing.
 *                  Using fakefop to generate placeholder PDF files.

Erlang/OTP 20.2 (20.2) has been successfully built

$ kerl install 20.2 ~/kerl/20.2
Installing Erlang/OTP 20.2 (20.2) in /Users/Kyle/kerl/20.2...
You can activate this installation running the following command:
. /Users/Kyle/kerl/20.2/activate
Later on, you can leave the installation typing:
kerl_deactivate

$ . /Users/Kyle/kerl/20.2/activate
 
$ erl -version
Erlang (SMP,ASYNC_THREADS,HIPE) (BEAM) emulator version 9.2
```

## Install Elixir
- https://github.com/taylor/kiex
``` 
$ \curl -sSL https://raw.githubusercontent.com/taylor/kiex/master/install | bash -s
$ kiex install 1.6.0
```
