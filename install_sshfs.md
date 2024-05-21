#steps to set up SSHFS on Mac OS (as of May 2024)

Over time, the list of steps to set up SSHFS to access remote file systems has changed. Here are some steps that worked for me:
1. Install Homebrew via
   - `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   - <a href = "https://mac.install.guide/homebrew/3">More homebrew installation instructions</a>
3. Follow instructions that are a part of "Enable System Extensions" in this: https://eengstrom.github.io/musings/install-macfuse-and-sshfs-on-macos-monterey
2. Install MacFuse via https://osxfuse.github.io
3. Restart your Mac
4. Install SSHFS: `brew install gromgit/fuse/sshfs-mac`. <a href = "https://github.com/osxfuse/osxfuse/issues/781#issuecomment-833421071">Source</a>
5. Type `which sshfs` to check installation
6. Usage
- `sshfs -p <port_ID> remote_file_system_username@IP_address:/folder/ ~/<location_of_folder_on_local_desktop>`




