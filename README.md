# dotfiles

## modify npm global

1. find where npm is in:

```bash
whereis npm
```

2. find where global npmrc is in:

```bash
npm config ls -l
```

3. modify global npmrc

```
cp .npmrc /global/npmrc
```

## modify global pip source

1. using root user to execute

```bash
sudo pip config set global.index-url http://mirrors.cloud.tencent.com/pypi/simple
sudo pip config set global.trusted-host global.trusted-host
```
