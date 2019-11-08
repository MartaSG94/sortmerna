# Table of Contents
* [Using GitHub release binaries](#using-github-release-binaries)


## Using GitHub release binaries

Visit [Sortmerna GitHub Releases](https://github.com/biocore/sortmerna/releases) to view the available releases 

The releases are distributed as shell scripts that contain embedded release archives. 

Perform the installation as follows 
```
# download the installer into a directory of your choice (substitute the release version as desired)
pwd
  /home/biocodz
wget https://github.com/biocore/sortmerna/releases/download/v4.0.0/sortmerna-4.0.0-linux.sh

ls -lrt
  ...
  sortmerna-4.0.0-linux.sh

# view help
bash sortmerna-4.0.0-linux.sh --help

# run the installation
bash sortmerna-4.0.0-linux.sh --skip-license
```