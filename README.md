# maker

Maker sets up a new project using [fem](https://github.com/lode/fem).


## Getting started with fem

1. **Install with [Composer](http://getcomposer.org/)**. Use `create-project` to get an example project for fem.

  ``` sh
  composer create-project alsvanzelf/maker:dev-master name-of-your-project
  ```

2. **Autoloading your own project's namespace.** 
  Overwrite `composer.json` with the `example-composer.json`,
  adjust the autoloading with your own project name, and run `composer update`.
  Also change the namespace statement in `application/controllers/home.php`.

3. **Setup a virtual host.**
  I.e. `dev.projectname`, and navigate to it.
  You should see a "Hello World" example application.

4. **Experiment.**
  Adjust `application/controllers/home.php` to get to know fem.
  See [fem's own documentation](https://github.com/lode/fem/wiki) for further steps.


## Contribute

Pull Requests or issues are welcome!


## License

[MIT](/LICENSE)
