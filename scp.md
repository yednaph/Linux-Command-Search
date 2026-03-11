<b> Some example usage of the `scp` command </b>

To copy a file from your local machine to a remote server: `scp <fullfilePath> <user>@<hostaddress>:<destinationPath>`

To copy a file from a remote server to your local machine: `scp <user>@<hostaddress>:<filePathSource> <destinationPath>`

To scp between two remote servers from the third machine: `scp -3 <user>@<host1address>:<SourceFilePath> <user>@<host2address>:<destinationPath>`
