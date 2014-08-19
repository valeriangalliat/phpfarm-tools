phpfarm tools
=============

> A set of tools for phpfarm

Installation
------------

```sh
cd /path/to/phpfarm
git clone https://github.com/valeriangalliat/phpfarm-tools tools
tools/install
```

The `install` script will link `tools/phpfarm-*` in
`inst/bin/phpfarm-*`.

`phpfarm-alias`
---------------

### Automatic

```sh
phpfarm-alias 5.5.15
```

```
./php-config-5.5 => ./php-config-5.5.15
./pyrus-5.5 => ./pyrus-5.5.15
./php-5.5 => ./php-5.5.15
./php-cgi-5.5 => ./php-cgi-5.5.15
./phpize-5.5 => ./phpize-5.5.15
```

### Custom

```sh
phpfarm-alias 5.5.15 current
```

```
./php-config-current => ./php-config-5.5.15
./pyrus-current => ./pyrus-5.5.15
./php-current => ./php-5.5.15
./php-cgi-current => ./php-cgi-5.5.15
./phpize-current => ./phpize-5.5.15
```
