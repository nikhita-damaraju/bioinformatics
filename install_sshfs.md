#steps to set up SSHFS on Mac OS (as of May 2024)

Over time, the list of steps to set up SSHFS to access remote file systems has changed. Here are some steps that worked for me:
1. Install HomeBrew via 
2. Follow instructions that are a part of "Enable System Extensions" in this: https://eengstrom.github.io/musings/install-macfuse-and-sshfs-on-macos-monterey
2. Install MacFuse via https://osxfuse.github.io
3. Restart your Mac
4. Install SSHFS:
- `git clone --branch 2.9@monterey git@github.com:eengstrom/sshfs.git`
- `test -e Makefile.in || autoreconf -i`
- `brew install gromgit/fuse/sshfs-mac`




