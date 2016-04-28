# maker

Maker sets up a new project using [fem](https://github.com/lode/fem).


## Install

[Use Composer](http://getcomposer.org/). And use create-project to get an example project for fem.

``` sh
composer create-project alsvanzelf/maker:dev-master name-of-your-project
```

#### Autoloading your own project's namespace

Overwrite `composer.json` with the `example-composer.json`,
adjust the autoloading with your own project name, and run `composer update`.
Also change the namespace statement in `application/controllers/home.php`.

#### Setup a virtual host

Set up a virtual host, i.e. to `dev.projectname` and navigate to it.
You should see a "Hello World" example application.
Experiment with `application/controllers/home.php` to get to know fem.

#### Further steps

See [fem's own documentation](https://github.com/lode/fem/wiki) for further steps.


## Contribute

Pull Requests or issues are welcome!


## License

[MIT](/LICENSE)
