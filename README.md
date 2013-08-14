android_local_qinara
======================

Local Manifest for Motorola Atrix HD devices

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	mkdir .repo/local_manifests

To initialize your local repository using the AOSP manifest, use commands like these:


    curl -L -o .repo/local_manifests/qinara.xml -O -L https://raw.github.com/UISS-Dev-Team/android_local_qinara/jb-aosp/qinara.xml
 
    	( or Download: https://github.com/UISS-Dev-Team/android_local_qinara/blob/jb-aosp/qinara.xml
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

Then to sync up:

    repo sync
