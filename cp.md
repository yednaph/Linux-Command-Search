<b> Some example usage of `cp` command </b>

Copy a file and paste it to another location: `cp ~/Desktop/file.txt ~/Downloads/file.txt`

To copy a directory and paste it to another location: `cp -r ~/Desktop/foldername/ ~/user/`

To create a copy but ask to overwrite if the destination file already exists: `cp -i ~/Desktop/file.txt ~/Documents/file.txt`

To create a backup file with date: `cp filename.txt{,."$(date +%Y%m%d-%H%M%S)"}`
