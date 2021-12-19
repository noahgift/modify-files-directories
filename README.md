# modify-files-directories
Notes on modifying files and directories in linux

![IMG_29BAAF801B32-1](https://user-images.githubusercontent.com/58792/146691100-78f4abbc-e22f-41fd-bc9f-fbde67ffc92c.jpeg)

## Create, Copy, Move and Sync Data

```bash

# Make a directory
mkdir foo

# Make many directories 
mkdir -p bar/bam/biz

# Create files
touch bar/one.txt && touch bam/two.txt && touch biz/three.txt

# Move files
mv bar /tmp/

# copy files
cp -r bam /tmp/

# sync files
touch bam/four.txt
rsync -av bam /tmp/

# delete directory
mkdir noneDir
rmdir noneDir

# remove folder
rm -rf biz

```

