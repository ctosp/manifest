------------------------------------------
     
<p align="center">
 <img src="https://github.com/ctosp/manifest/blob/pie/ctOS.png" > 
</p>

------------------------------------------

------------------------------------------
# CTOSP - Android Q #
------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).


# To initialize your local repository, use a command like this:-

```bash
repo init -u git://github.com/ctosp/manifest.git -b ten
```

# To initialize a shallow clone, which will save even more space, use a command like this:-

```bash
repo init --depth=1 -u git://github.com/ctosp/manifest.git -b ten
```

# Then to sync up:- 

```bash
repo sync -c -j16 --force-sync --no-clone-bundle --no-tags
```

# Start the build:-

```bash
. build/envsetup.sh
lunch ctosp_<devicecodename>-userdebug
mka bacon -jx
 ```
---------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**PixelExperience**](https://github.com/PixelExperience)
 
----------------------------------------------

Stay tune to Telegram

* CTOSP Group Public : [**@Ctosp**](https://t.me/CTOSP)
* CTOSP-Announcement : [**@ctosp_feed**](https://t.me/ctosp_feed)
