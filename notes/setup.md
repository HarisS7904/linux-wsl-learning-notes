# WSL setup
We need to setup the WSL which stand for Windows Subsystem for Linux to
let the Windows to run the linux distribution without erasing the Windows.

This can be done by run the Powershell as administrator and run:
```powershell
wsl --install
```

This will automatically install wsl with latest default Ubuntu release.

# Update Ubuntu
Then we need to update it by running:
```bash
sudo apt update
sudo apt upgrade
```
sudo will run the command as administrator permission, apt is a package manager,
update will download a current list of available package versions and
upgrade will compared installed package to the new list and install it.
