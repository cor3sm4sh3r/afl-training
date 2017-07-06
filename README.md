# Fuzzing with AFL workshop
Materials of the "Fuzzing with AFL" workshop.

The first public version of this workshop was presented at [SteelCon 2017](https://www.steelcon.info/the-event/workshops/#FWA).

# Pre-requisites
- 3-4 hours (more to complete all the challenges)
- Linux machine
- Basic C and command line experience - ability to modify and compile C programs.
- Docker, or the dependencies described in `quickstart`.

# Contents
- quickstart - Do this first! A tiny sample program to get started with fuzzing, including instructions on how to setup your machine.
- docker - Instructions and Dockerfile for preparing a suitable environment, and hosting it on AWS if you wish.
- challenges - a set of known-vulnerable programs with fuzzing hints

See the other READMEs for more information.

# Challenges

Challenges, roughly in recommended order, with any specific aspects they cover:
- sendmail/1301 - parallel fuzzing
- heartbleed - fuzzing with ASAN
- date - fuzzing environment variable input
- ntpq - fuzzing a network client; coverage analysis and increasing coverage
- cyber-grand-challenge - an easy vuln and an example of a hard to find vuln using afl
- sendmail/1305 - persistent mode difficulties

The challenges have HINTS.md and ANSWERS.md files - these contain useful information about fuzzing different targets even if you're not going to attempt the challenge.

All of the challenges use real vulnerabilities from open source projects (the CVEs are identified in the descriptions), with the exception of the Cyber Grand Challenge extract, which is a synthtetic vulnerability.

# Slides

TODO

# Links

- The afl docs/ directory
- Ben Nagy’s “Finding Bugs in OS X using AFL” [video](https://vimeo.com/129701495)
- The [afl-users mailing list](https://groups.google.com/forum/#!forum/afl-users)
- The smart fuzzer revolution (talk on the future of fuzzing): video / slides
- [libFuzzer](http://llvm.org/docs/LibFuzzer.html)
    - [libFuzzer workshop](https://github.com/Dor1s/libfuzzer-workshop)
    - [libFuzzer tutorial](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)

