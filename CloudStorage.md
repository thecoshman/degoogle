Being able to just save files on one machine and have them sync to an online backup and to other machines is really nice. Especially when you can 'share' files/folders with other people. Google Drive is a nice enough offering, but doesn't have the greatest of clients for having offline copies of your files.

## Dropbox

Perhaps the most well known free option available. You get a good bit of space for free, and with referral links you can get more (though I doubt there are many people left to invite). The client works well for syncing files you your local machine. 

## Nextcloud

This is an option that is currently being investigated. It would be a self managed option, so a server would need to be rented from some provider, and the software installed and managed. Not for the faint of heart, and perhaps a bit much for just yourself.

## Syncthing

An alternative to traditional cloud services is P2P synchronization. Each device involved is running a Syncthing daemon which can be configured to point at a specific directory on a device. That directory will be automatically synchronized across all devices running the Syncthing daemon synchronizing the same directory.

## Duplicati

Backup solution that encrypts before sending to remote server. This way your storage provider can't access your files. Supports various storage providers, and also sending to a SFTP server.