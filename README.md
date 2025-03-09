# quick-s6
### Description
Shell scripts that prevent manual labor

**quick-s6-compile:** for compiling services with [s6-rc-compile](https://skarnet.org/software/s6-rc/s6-rc-compile.html)

**quick-s6-init:** for creating and installing s6 init with [s6-linux-init-maker](https://skarnet.org/software/s6-linux-init/s6-linux-init-maker.html) (you can edit this one easily)

[s6 is an init system](https://skarnet.org/software/s6/), the best for linux, I guess it works for BSD too
### Install
Learn s6 and s6-rc, install what you need, you probably already have (s6, s6-rc, s6-linux-init, skalibs, execline), then

```
git clone https://github.com/loadfred/quick-s6
```

or

```
curl -LO https://github.com/loadfred/quick-s6/raw/refs/heads/main/quick-s6-compile
curl -LO https://github.com/loadfred/quick-s6/raw/refs/heads/main/quick-s6-init
```

and

```
chmod +x quick-s6-*
```

and use the scripts, maybe put them in /usr/local/bin/
