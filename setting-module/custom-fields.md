title: Custom fields
subtitle: Setting Module
-------

- [Custom Fields](#custom-fields)

## <a name="custom-fields" class="anchor" href="#custom-fields"></a> Setting module : Custom fields

If you have a need for a custom field like a calendar for instance, you can specify the complete path in the `view:` key.

For instance your module might make a calendar field available:

``` .language-php
'this-is-a-calendar' => [
   'description' => 'This is a radio',
   'view' => 'Module::admin.fields.calendar'
],

```

This wil override the basic available fields and use yours.
