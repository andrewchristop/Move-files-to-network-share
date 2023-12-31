# Batch Backup Script

This script creates directories on a network share based on system time and date and moves daily backup files to the newly created directory

To use this script, either direct-download, clone the repo, or run `curl https://raw.githubusercontent.com/andrewchristop/batch-backup-script/main/server.bat -o server.bat`

Then modify all instances of `UNCPATH\share` with the Universal Naming Convention (UNC) path of the network share

After that modify `E:\filename` with current location of the local directory

TIP: Use task scheduler to run the script on desired intervals

