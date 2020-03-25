Experimental [xxh](https://github.com/xxh/xxh) entrypoint for [fish-portable](https://github.com/xxh/fish-portable) - statically-linked fish.
## Install
Install from xxh repo:
```
xxh +I xxh-shell-fish
```
Install from any repo:
```
cd ~/.xxh/xxh/shells/
git clone https://github.com/xxh/xxh-shell-fish
./xxh-shell-fish/build.sh
xxh myhost +s xxh-shell-fish
```
To avoid adding `+s` every time use xxh config in `~/.xxh/.xxhc`:
```
hosts:
  ".*":                     # Regex for all hosts
    +s: xxh-shell-fish
```

## Plugins

**fish xxh plugin** is the set of fish scripts which will be run when you'll use xxh. You can create xxh plugin with your lovely aliases, tools or color theme and xxh will bring them to your ssh sessions.

🔎 [Search xxh plugins on Github](https://github.com/search?q=xxh-plugin-fish&type=Repositories) or [Bitbucket](https://bitbucket.org/repo/all?name=xxh-plugin-fish) or 💡 [Create xxh plugin](https://github.com/xxh/xxh-plugin-fish-sample)