# Rounded Product Price

[![Latest Stable Version](https://img.shields.io/packagist/v/blackbird/rounded-discount-price.svg?style=flat-square)](https://packagist.org/packages/blackbird/rounded-discount-price)
[![License: MIT](https://img.shields.io/github/license/blackbird-agency/magento-2-rounded-discount-price.svg?style=flat-square)](./LICENSE)

This module allows you to round your catalog rule product discount price to the rounded up integer or rounded down integer.

It adds a field, Rounding Type, to setup rounded price on catalog rule action form with 3 options : None, Up and Down :

![Illustration](illustration.png)

**Result :** here the price become 41.00€ instead of 41.30€ (if Rounding Type is "Up" the discount price will become 42.00€)

![Illustration Front](illustration-front.png)

## Setup

### Get the package

**Composer Package:**


```
composer require blackbird/rounded-discount-price
```

**Zip Package:**

Unzip the package in app/code/Blackbird/RoundedDiscountPrice, from the root of your Magento instance.


### Install the module

Go to your Magento root directory and run the following magento command:

```
php bin/magento setup:upgrade
```

**If you are in production mode, do not forget to recompile and redeploy the static resources, or use the `--keep-generated` option.**

## Support

- If you have any issue with this code, feel free to [open an issue](https://github.com/blackbird-agency/magento-2-category-empty-button/issues/new).
- If you want to contribute to this project, feel free to [create a pull request](https://github.com/blackbird-agency/magento-2-category-empty-button/compare).

## Contact

For further information, contact us:

- by email: hello@bird.eu
- or by form: [https://black.bird.eu/en/contacts/](https://black.bird.eu/contacts/)

## Authors

- **Bruno Fache** - *Maintainer* - [It's me!](https://github.com/bruno-blackbird)
- **Blackbird Team** - *Contributor* - [They're awesome!](https://github.com/blackbird-agency)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

***That's all folks!***