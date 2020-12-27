# sync kai-morich/usb-serial-for-android-mik3y to mik3y/usb-serial-for-android

## init
* create usb-serial-for-android-mik3y repo
* run locally:

      mkdir usb-serial-for-android-mik3y
      cd usb-serial-for-android-mik3y
      git init
      git remote add origin https://github.com/kai-morich/usb-serial-for-android-mik3y.git
      git remote add base https://github.com/mik3y/usb-serial-for-android.git
      git fetch base
      git checkout master
      git push -u origin master
      cd ..

## sync

`sync` action runs daily at 4PM
