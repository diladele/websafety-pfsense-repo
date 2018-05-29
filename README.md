# websafety-pfsense-repo

# create repo structure

    mkdir diladele
    cd diladele
    mkdir websafety
    cd websafety
    fetch http://packages.diladele.com/websafety/6.3.0.1669/amd64/release/freebsd11/websafety-6.3.0-amd64.txz
    pkg repo .

Now commit the following files into ./websafety-pfsense-repo/repo/FreeBSD:11:amd64 folder and 'git push' to github.

    digests.txz
    meta.txz
    packagesite.txz
    websafety-6.3.0-amd64.txz

