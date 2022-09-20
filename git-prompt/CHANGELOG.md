# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.0 (2022-09-20)

The first usable release.

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 38 commits contributed to the release over the course of 22 calendar days.
 - 22 days passed between releases.
 - 0 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 2 unique issues were worked on: [#450](https://github.com/Byron/gitoxide/issues/450), [#470](https://github.com/Byron/gitoxide/issues/470)

### Thanks Clippy

<csr-read-only-do-not-edit/>

[Clippy](https://github.com/rust-lang/rust-clippy) helped 1 time to make code idiomatic. 

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#450](https://github.com/Byron/gitoxide/issues/450)**
    - fix warnings on windows ([`b8b4371`](https://github.com/Byron/gitoxide/commit/b8b4371be7802742b5cffdbc3acf8c197521ffbc))
    - Use reference `git-prompt::Options` to allow them to be re-used ([`51930a2`](https://github.com/Byron/gitoxide/commit/51930a237ec472fff34c639c9caffe74ed12ab2a))
    - always compile prompting support in ([`bd0ea68`](https://github.com/Byron/gitoxide/commit/bd0ea68225a73fb83c9fc1b8594fc6ad288a77a9))
    - set version of git-prompt to 0.1 and turn prompting on ([`7657693`](https://github.com/Byron/gitoxide/commit/7657693b8e23dfb69d6da4376bcd1b8e4e264f7e))
    - validate askpass program works ([`bb1acf4`](https://github.com/Byron/gitoxide/commit/bb1acf40ff9da965b87da6cfc695957b668f14d3))
    - getting closer to using askpass correctly ([`1ddcb50`](https://github.com/Byron/gitoxide/commit/1ddcb50a8405a9293ae01bca20047d3a3a9a56c4))
    - a test to validate askpass support ([`a023d7d`](https://github.com/Byron/gitoxide/commit/a023d7d2541ba4bfa6ecf1cea99be5c8eeb7a3d5))
    - refactor ([`77026d7`](https://github.com/Byron/gitoxide/commit/77026d76c93b4a1f05011fac94e1fb8664b84c89))
    - askpass example ([`1efb139`](https://github.com/Byron/gitoxide/commit/1efb13984c78f39c72c6bb691403011e8ad7654d))
    - tests for `Options::apply_environment()` ([`623d4a5`](https://github.com/Byron/gitoxide/commit/623d4a55b9590ff6496b7383925ec89d9d2e5d3d))
    - A for now untested way to adjust options with environment variables ([`af08b38`](https://github.com/Byron/gitoxide/commit/af08b380beff90c11900ef30e7db3ffd35a352ed))
    - refactor ([`0fa676a`](https://github.com/Byron/gitoxide/commit/0fa676a9d880eb23dcf096af09ac9b5c01b72c63))
    - a flexible `Mode` enum to handle all possible states ([`15bb50c`](https://github.com/Byron/gitoxide/commit/15bb50c9b9769a8efa8e38e51b8be4af3798eab7))
    - sketch askpass path ([`f8c8cbb`](https://github.com/Byron/gitoxide/commit/f8c8cbb4f3e3c062073af51f3a01e30e467187e2))
    - cargo-diet for git-prompt ([`db2d8ae`](https://github.com/Byron/gitoxide/commit/db2d8ae65cc94f9cd93c4f88378b38b0f734bc41))
    - refactor ([`b346169`](https://github.com/Byron/gitoxide/commit/b346169e0ca32d5568a1c924c8c291384a544daa))
    - See if not having cargo-run output in program invocation fixes it on macos ([`a8d9d12`](https://github.com/Byron/gitoxide/commit/a8d9d123f2bfdebd00a0ca27cee21916ca7e44e4))
    - add missing docs ([`f10623b`](https://github.com/Byron/gitoxide/commit/f10623bf7b574876b1fb6c75cf35890c14e2c091))
    - Also setup the tty accordingly to not echo input ([`6a55a7b`](https://github.com/Byron/gitoxide/commit/6a55a7bc338df841dd706a31e1bd2631ece4dddd))
    - save state with restore and password reading, without hiding ([`a4ec2e2`](https://github.com/Byron/gitoxide/commit/a4ec2e2b279b15de15dcea6aad93e979f1019c5e))
    - restrict tests to unix only ([`dc2765f`](https://github.com/Byron/gitoxide/commit/dc2765f27d5c684ca46960db04fedfd26aae56a8))
    - properly trim the username at the end, and test for it ([`141aaa3`](https://github.com/Byron/gitoxide/commit/141aaa3b9ee90dd91e2bd03de7ca464297ab38f3))
    - basic TTY based prompting, without hiding of secrets ([`7c0297f`](https://github.com/Byron/gitoxide/commit/7c0297f5c0716bcdf274165de0decf998ec76d34))
    - the first successful assertion, showing that expectrl can intercept the tty ([`8582697`](https://github.com/Byron/gitoxide/commit/8582697cc21adc5eeb67155a0e4b0e2780d37beb))
    - frame for cross-platform compatible implementation ([`b18866e`](https://github.com/Byron/gitoxide/commit/b18866e82b35675a936b4f7cf1147727d565c318))
    - proper prompt generation ([`63ee38d`](https://github.com/Byron/gitoxide/commit/63ee38dab45fd9d07532f6c01afc2d8dd1c1e904))
    - remove rustyline in favor of `git-prompt` ([`b3e5e59`](https://github.com/Byron/gitoxide/commit/b3e5e59cafaab0d4866c52722cd2a67aa313b395))
 * **[#470](https://github.com/Byron/gitoxide/issues/470)**
    - update changelogs prior to release ([`caa7a1b`](https://github.com/Byron/gitoxide/commit/caa7a1bdef74d7d3166a7e38127a59f5ab3cfbdd))
 * **Uncategorized**
    - Release git-hash v0.9.10, git-features v0.22.5, git-date v0.2.0, git-actor v0.12.0, git-glob v0.4.0, git-path v0.5.0, git-quote v0.3.0, git-attributes v0.4.0, git-config-value v0.8.0, git-tempfile v2.0.5, git-validate v0.6.0, git-object v0.21.0, git-ref v0.16.0, git-sec v0.4.0, git-config v0.8.0, git-discover v0.5.0, git-traverse v0.17.0, git-index v0.5.0, git-worktree v0.5.0, git-testtools v0.9.0, git-command v0.1.0, git-prompt v0.1.0, git-url v0.9.0, git-credentials v0.5.0, git-diff v0.19.0, git-mailmap v0.4.0, git-chunk v0.3.2, git-pack v0.23.0, git-odb v0.33.0, git-packetline v0.13.0, git-transport v0.20.0, git-protocol v0.20.0, git-revision v0.5.0, git-refspec v0.2.0, git-repository v0.24.0, git-commitgraph v0.9.0, gitoxide-core v0.18.0, gitoxide v0.16.0, safety bump 28 crates ([`29a043b`](https://github.com/Byron/gitoxide/commit/29a043be6808a3e9199a9b26bd076fe843afe4f4))
    - Merge branch 'index-from-tree' ([`172f73c`](https://github.com/Byron/gitoxide/commit/172f73cf26878d153d51790fa01853fa4ba6beb7))
    - WIP. ([`79d82d4`](https://github.com/Byron/gitoxide/commit/79d82d46613c83280d2401ef4d72a35010a70b87))
    - make fmt ([`535e967`](https://github.com/Byron/gitoxide/commit/535e967666c6da657ff1b7eff7c64ab27cafb182))
    - Merge branch 'main' into filter-refs-by-spec ([`9aa1d3d`](https://github.com/Byron/gitoxide/commit/9aa1d3dc46d4b1c76af257f573aff3aeef2d3fa8))
    - Merge branch 'main' into filter-refs-by-spec ([`1f6e5ab`](https://github.com/Byron/gitoxide/commit/1f6e5ab15f5fd8d23719b13e6aea59cd231ac0fe))
    - Merge branch 'main' into filter-refs-by-spec ([`51dc828`](https://github.com/Byron/gitoxide/commit/51dc8282fb77b519ff7d2c94c6bd73af306cfe8b))
    - Merge branch 'main' into filter-refs-by-spec ([`56ba481`](https://github.com/Byron/gitoxide/commit/56ba481f4c48f74f10397feb1b6dc3d7dd3704fb))
    - Merge branch 'main' into filter-refs-by-spec ([`a36c05d`](https://github.com/Byron/gitoxide/commit/a36c05d281269f3f8b297e7adc463bfb3c306663))
    - thanks clippy ([`9867384`](https://github.com/Byron/gitoxide/commit/98673846d04a76c216ddd1da942a983dd8bb4ea1))
</details>

## 0.0.0 (2022-08-29)

Initial release just for the name.

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 3 commits contributed to the release.
 - 0 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 1 unique issue was worked on: [#450](https://github.com/Byron/gitoxide/issues/450)

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **[#450](https://github.com/Byron/gitoxide/issues/450)**
    - prepare changelog ([`3c7d490`](https://github.com/Byron/gitoxide/commit/3c7d4905b2b079018ace9f9f13c40585b9fe575f))
    - Add `git-prompt` crate for registration ([`b0140a6`](https://github.com/Byron/gitoxide/commit/b0140a6819cdfce0a5d88149f3713295b3bb54b5))
 * **Uncategorized**
    - Release git-prompt v0.0.0 ([`41281ad`](https://github.com/Byron/gitoxide/commit/41281ad9bc413af519973532238b467b2eb4fa9b))
</details>
