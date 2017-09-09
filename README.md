### Installing Antvel

[![Total Downloads](https://img.shields.io/packagist/dt/antvel/Installer.svg?style=flat-square)](https://img.shields.io/packagist/dt/antvel/Installer.svg?style=flat-square)
[![Packagist](https://img.shields.io/packagist/v/antvel/Installer.svg?style=flat-square)](https://github.com/ant-vel/Shop)

Antvel uses [Composer](https://getcomposer.org) to manage its dependencies. So, before using it, make sure you have Composer installed on your machine.

#### Via Antvel Installer

First, download the Antvel installer through Composer:

    composer global require "antvel/installer"

Make sure to place the `$HOME/.composer/vendor/bin` directory (or the equivalent directory for your OS) in your $PATH so the `antvel` executable can be located by your system.

Once installed, the `antvel install` command will create a fresh copy of the project in the directory you provided. For example, `antvel install` will create a directory named `App-master` containing a fresh Antvel installation with all of its dependencies already installed:

    antvel install
    

#### What will be executed

We are going to run all the required commands to get you started as quickly as possible. The commands stack can be seen on <a href="https://github.com/ant-vel/Installer/blob/master/src/Installer.php#L164">Commands stack</a>

***Note:*** This process will take a little bit of time, so make you, you are not in a hurry :)

Once the installing process is done, you will have to install the Javascript dependencies through <a href="https://github.com/yarnpkg/yarn" target="_blank">yarn</a>. As so:

```
yarn install
```

Then, you will have to run ```bower install``` to install all the Antvel assets where the belong. As so:

```
bower install
```


### Video Illustration

See the video on youtube clicking on <a href="https://youtu.be/YR-PgotQhdQ" _target="blank">here</a>


### Inspiration

The inspiration came from a needed of a quick method to install the project, so everybody can start using right away. I took as reference the Laravel installer, to learn and to have a similar tool for myself ;)


### Contributing

Please feel free to fork this package and contribute by submitting a pull request to enhance the functionalities.


### License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.


### How can I thank you?
Why not star the github repo? or share the link for this repository on Twitter? Spread the word!


Don't forget to [follow me on twitter](https://twitter.com/gocanto)!

Thanks!

Gustavo Ocanto.
gustavoocanto@gmail.com