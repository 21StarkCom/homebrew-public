# 21StarkCom/public (retired)

This tap is retired. Its entries moved to [`21StarkCom/tap`](https://github.com/21StarkCom/homebrew-tap),
which is public now: the same entries install from there with no GitHub login.

```sh
brew tap 21StarkCom/tap
brew install 21StarkCom/tap/<entry>
brew install --cask 21StarkCom/tap/<cask>
```

`tap_migrations.json` sends each old name to `21StarkCom/tap`, so `brew update` moves an
installed entry there. Then `brew untap 21StarkCom/public`.
