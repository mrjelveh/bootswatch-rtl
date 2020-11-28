<p align="center">
  <img width="200" height="200" src="./docs/_assets/img/logo-dark.svg">
</p>

<h3 align="center">Bootswatch-rtl</h3>

<p align="center">
  A collection of open source themes for <a href="https://mrjelveh.github.io/BootsDrac/">BootsDrac 🧛‍♂️</a> and <a href="https://getbootstrap.com/">Bootstrap</a>
  <br>
  <a href="https://mrjelveh.github.io/bootswatch-rtl"><strong>View Bootswatch-rtl themes »</strong></a>
  <br>
  <br>
  <a href="https://github.com/mrjelveh/bootswatch-rtl/issues/new">Report bug</a>
  ·
  <a href="https://github.com/mrjelveh/bootswatch-rtl/issues/new">Request feature</a>

</p>

## Usage

There are a few different ways you can integrate Bootswatch into your project.

### Via Pre-compiled Asset

Download the `bootstrap.min.css` file associated with a theme and replace
Bootstrap's default stylesheet. You must still include Bootstrap's JavaScript
file to have functional dropdowns, modals, etc.


### Via Sass Imports

First of all, you should install Bootsdrac ```npm i bootsdrac ```, If you're using [Sass](https://sass-lang.com/) (SCSS) in your project, you can
import the `_variables.scss` and `_bootswatch.scss` files for a given theme.
This method allows you to override theme variables.

```scss
// Your variable overrides go here, e.g.:
// $h1-font-size: 3rem;

@import "~bootswatch/dist/[theme]/variables";
@import "~bootsdrac/scss/bootstrap-rtl";
@import "~bootswatch/dist/[theme]/bootswatch";
```

Make sure to import Bootstrap's `bootstrap-rtl.scss` in between `_variables.scss`
and `_bootswatch.scss`!


## Customization

Bootswatch is open source and you’re welcome to modify the themes.

Each theme consists of two SASS files. `_variables.scss`, which is included by default in Bootstrap, allows you to customize the settings. `_bootswatch.scss` introduces more extensive structural changes.

Check out the [Help page](https://mrjelveh.github.io/bootswatch-rtl/help/#customization) for more details on building your own theme.



## Author

MohammadReza Jelveh

* <https://github.com/mrjelveh>
* <https://mrjelveh.com/>


Thomas Park

* <https://github.com/thomaspark>
* <https://thomaspark.co/>


## Copyright and License

Copyright 2020 MohammadReza Jelveh

Copyright 2014-2020 Thomas Park


Code released under the MIT License.
