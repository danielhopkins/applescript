This is a collection of Apple scripts. I've been running using [fastscripts](http://www.red-sweater.com/fastscripts/) to map key commands to different scripts.

## Installation ##
Copy, or alias the Scripts directory into your Library directory. ~/Library/Scripts is a special directory, it is picked up by the normal script menu and by fast scripts.

The included install bash script aliases the directory into the Library because symlinks don't work with fast scripts ([known bug](http://www.red-sweater.com/forums/discussion/1274/mobileme-syncing-of-fastscripts-settings-and-scripts/p1)).

## Archive message ##
I started using this in my quest for zero inbox in Mail.app 5.0. This script moves messags out of the inbox and to "All Mail", which effectively archives.

### todo ###
    - Get rid of hard coded links, otherwise people have to fix the script and it won't work in a multi-account environment.
    - When you archive a file it tends to get stuck, like the folder needs to get refreshed
    - There are some times errors if you move the selection around
    - Perfomance? Woah.

## Other script ideas ##
    - Coffee shop mode: locks down the computer
        - turn on a password protect screen saver
    - Word mode: does the opposite of coffee shop mode
    - Mark as gmail spam: moves to spam folder, similar to archive script
