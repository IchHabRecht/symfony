UPGRADE FROM 3.0 to 3.1
=======================

DependencyInjection
-------------------

 * Using unsupported configuration keys in YAML configuration files has been
   deprecated and will raise an exception in Symfony 4.0.

 * Using unsupported options to configure service aliases has been deprecated
   and will raise an exception in Symfony 4.0.

Form
----

 * The `choices_as_values` option of the `ChoiceType` has been deprecated and
   will be removed in Symfony 4.0.

Serializer
----------

 * Passing a Doctrine `Cache` instance to the `ClassMetadataFactory` has been
   deprecated and will not be supported in Symfony 4.0. You should use the
   `CacheClassMetadataFactory` class instead.

Yaml
----

 * The `!!php/object` tag to indicate dumped PHP objects has been deprecated
   and will be removed in Symfony 4.0. Use the `!php/object` tag instead.
