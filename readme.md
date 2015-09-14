####Build your own smartvisu-cleaninstall for use with fronthem:

- Install smartVISU 2.8 ( https://github.com/Martin-Gleiss/smartvisu )
- Download herrmannj's smartvisu-cleaninstall ( https://github.com/herrmannj/smartvisu-cleaninstall/archive/master.zip )
- Copy the following files from smartvisu-cleaninstall-master.zip to your smartVISU 2.8 directory (yes, to have to overwrite some files)

```
./readme.txt
./lib/functions_config.php
./lib/includes.php
./config.ini.default
./pages/base/configure.php
./driver/io_fhem.js
./driver/io_fhem.min.js
```

To migrate from smartVISU 2.7 to 2.8:
- copy your pages folder and other added files to smartVISU 2.8
- copy your config.ini to smartVISU 2.8

To start a new installation:
- rename/copy config.ini.default to config.ini

That's all.