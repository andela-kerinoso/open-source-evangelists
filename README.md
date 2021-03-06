# open-source-evangelists

[![Build Status](https://travis-ci.org/andela-kerinoso/open-source-evangelists.svg)](https://travis-ci.org/andela-kerinoso/open-source-evangelists)

This package encourages programmers to contribute more to open source by ranking an individual based on the number of public repositories s(he) possesses on GitHub. An individual is ranked to one of these categories:

`>= 5 and <= 10        Junior Evangelist`

`>= 11 and <= 20       Associate Evangelist`

`>= 21                 Most Senior Evangelist`

## Installation

[PHP](https://php.net) 5.5+ and [Composer](https://getcomposer.org) are required.

Via Composer

``` bash
$ composer require kola/open-source-evangelists
```

``` bash
$ composer install
```

## Usage

```
$status = new EvangelistStatus($username);
```

```
$status->getStatus();
```

Note that $username is the GitHub username of the individual.

## Change log

Please check out [CHANGELOG](CHANGELOG.md) file for information on what has changed recently.

## Testing

``` bash
$ vendor/bin/phpunit test
```

## Contributing

Please check out [CONTRIBUTING](CONTRIBUTING.md) file for detailed contribution guidelines.

## Credits

Open-source Evangelist is maintained by `Kolawole ERINOSO`.

## License

Open-source Evangelist is released under the MIT Licence. See the bundled [LICENSE](LICENSE.md) file for details.