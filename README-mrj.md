# Stuff I need to remember for local dev

### Build for install

To build installable packages

```bash
yarn run bks:build

# to install locally
sudo apt install ./apps/studio/dist_electron/beekeeper-studio_2.1.4_amd64.deb
```

### Keep up to date with upstream

Initially, set the upstream
```bash
git remote add upstream https://github.com/beekeeper-studio/beekeeper-studio.git
```

Then, to keep up to date

```bash
git checkout master
git fetch upstream
git rebase upstream/master
```

