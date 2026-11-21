# 21StarkCom/public

<!-- BEGIN 21stark-mirror -->
## Install

The mirror job of `21StarkCom/homebrew-tap` (its `scripts/mirror.sh`) writes this
section and every file that holds its marker line. A change made here is lost at
its next run. Each of these entries downloads its asset from a public release of
this repo, so installing needs no GitHub login and no token.

```sh
brew tap 21StarkCom/public
brew trust --tap 21StarkCom/public
brew install 21StarkCom/public/<entry>
brew install --cask 21StarkCom/public/<cask>
```

A Mac that also taps `21StarkCom/tap` must use full names in every `brew`
command, `brew services` included, for example `21StarkCom/public/tyr`.

| Entry | Kind | Version |
|---|---|---|
| `bragi` | formula | 0.6.0 |
| `frigg-linux` | formula | 0.88.0 |
| `frigg` | formula | 0.88.0 |
| `heimdall` | formula | 0.2.0 |
| `lumiere` | formula | 0.11.0 |
| `plume` | formula | 0.11.0 |
| `sonar-linux` | formula | 0.15.2 |
| `sonar` | formula | 0.15.2 |
| `stark-statusline` | formula | 0.7.0 |
| `tyr` | formula | 0.109.0 |
| `urd-linux` | formula | 0.15.1 |
| `urd` | formula | 0.15.1 |
| `goldfinger` | cask | 0.21.0 |
| `mimir` | cask | 0.90.1 |
<!-- END 21stark-mirror -->
