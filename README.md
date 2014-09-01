SerializerTranslationBundle
===========================

[![Scrutinizer Code Quality]
(https://scrutinizer-ci.com/g/avoo/SerializerTranslationBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/avoo/SerializerTranslationBundle/?branch=master)
[![Build Status]
(https://scrutinizer-ci.com/g/avoo/SerializerTranslationBundle/badges/build.png?b=master)](https://scrutinizer-ci.com/g/avoo/SerializerTranslationBundle/build-status/master)
[![Latest Stable Version]
(https://poser.pugx.org/avoo/serializer-translation-bundle/v/stable.svg)](https://packagist.org/packages/avoo/serializer-translation-bundle)
[![License]
(https://poser.pugx.org/avoo/serializer-translation-bundle/license.svg)](https://packagist.org/packages/avoo/serializer-translation-bundle)

This bundle integrates [SerializerTranslation](http://github.com/avoo/SerializerTranslation)

Installation
------------

Require [`avoo/serializer-translation-bundle`](https://packagist.org/packages/avoo/serializer-translation-bundle)
into your `composer.json` file:


``` json
{
    "require": {
        "avoo/serializer-translation-bundle": "@dev-master"
    }
}
```

Register the bundle in `app/AppKernel.php`:

``` php
// app/AppKernel.php
public function registerBundles()
{
    return array(
        // ...
        new Avoo\SerializerTranslationBundle\AvooSerializerTranslationBundle(),
    );
}
```


Documentation
-------------

This bundle integrates [SerializerTranslation](https://github.com/avoo/SerializerTranslation), translate properties from JMS serializer
see [Serializer translation documentation](https://github.com/avoo/SerializerTranslation/blob/master/README.md) for more details


Credits
-------

* Jérémy Jégou <jejeavo@gmail.com>


License
-------

This bundle is released under the MIT license. See the complete license in the bundle:

[License](https://github.com/avoo/SerializerTranslationBundle/blob/master/LICENSE)
