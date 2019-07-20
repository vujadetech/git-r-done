#### Set file/dir (type f, type d) permissions recursively
find . -type f -execdir chmod 644 {} +
find . -type d -execdir chmod 755 {} +

chown -R [USER]:[USER] [DIR]

#### Syncing
rsync -vanP (-v verbose, -a archive, -n dry run, -P = --partial --progress)

#### Add path
cat >> ~/.bashrc # or ~/.bash_profile
PATH=$PATH:[DIR] # or reverse order
export PATH

then source ~/.bashrc




