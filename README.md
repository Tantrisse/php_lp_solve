# lpsolve

A PHP extension to execute [lpsolve](https://sourceforge.net/projects/lpsolve/), a Mixed Integer Linear Programming (MILP) solver.

Compatible with PHP >= 7.0 & PHP >= 8.0

## How to compile

```bash
# Replace X.X in phpX.X-dev by the version number your builing for
apt-get install liblpsolve55-dev phpX.X-dev

# To build for PHP 7.X, use the php-7 branch
git clone --branch php-7 git@github.com:Tantrisse/php_lp_solve.git

# To build for PHP 8.X, use the php-8 branch
git clone --branch php-8 git@github.com:Tantrisse/php_lp_solve.git

cd php_lp_solve/Sources
phpize
./configure
make
```

## Credits

- Jesse Denardo
- [@jrhigueras](https://github.com/jrhigueras)
