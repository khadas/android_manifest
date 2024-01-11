# Make a directory where Repo will be stored and add it to the path

$ mkdir ~/bin

$ PATH=~/bin:$PATH

# Download Repo itself
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

# Make Repo executable
$ chmod a+x ~/bin/repo

# Create a directory for the source files
$ mkdir android

$ cd android

# Install Repo in the created directory
$ repo init -u git://github.com/ampir-nn/android_manifest.git -b  khadas-vims-pie --git-lfs
