# Star Citizen Runner Updater
A script to make installing the latest wine runners from [Snatella's Awesome Star Citizen Runners](https://github.com/snatella/wine-runner-sc) even easier.

Primarly for use with Lutris.

## Prior Note
This was heavily inspired by flubberding's awesome [ProtonUpdater](https://github.com/flubberding/ProtonUpdater). Props to him for making a great script and allowing me to use it as a foundation for this one.

## Installation & Execution
Just copy the `update.sh` file to your chosen directory and run `bash update.sh` to execute.

If you are feeling extra spicy, run:

```
sudo cp update.sh /usr/local/bin/sc-updater
```
Which renames the file to `sc-updater` and moves it to the local application folder

```
sudo chmod +x /usr/local/bin/sc-updater
```
Makes the file executable.

Now you can `sc-updater` from anywhere in a terminal to run the script.

## Options
You can set some options at the start of the script

`restart_lutris` can be set as the following:
```
0 to not restart Lutris after installing the runner
1 to autorestart Lutris after installing the runner
2 to to ask with a y/n prompt if Lutris is running
```

`base_path` can be set to whichever directory you usually install your Lutris wine runners to.

## License
This project is licensed under the MIT License
