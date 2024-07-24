# Faker PHP "Green" - fr_FR

This repository is a fork of [FakerPHP/Faker](https://github.com/FakerPHP/Faker). It has been created in order to reduce the carbon footprint of Faker.

Indeed, as reported by the original developer [François Zaninotto](https://github.com/fzaninotto/Faker) on his blog post _[Sunsetting PHP Faker](https://marmelab.com/blog/2020/10/21/sunsetting-faker.html)_, there is now too much locales supported, with a real and negative impact on the amount of bytes downloaded.

Limiting Faker by reducing the number of locales supported is probably the only way to quickly avoid this carbon footprint issue.

In conclusion, this unofficial repository is Faker, but only with two locales supported :

* en_US : the default one.
* fr_FR : the one which I need (and maybe you too)

## Documentation

See [the official documentation](https://github.com/FakerPHP/Faker): the only change is the removal of unnecessary providers.
