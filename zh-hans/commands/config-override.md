# config:override
Override config value in active configuration.

**application.gitbook.messages.usage:**
```
drupal config:override [arguments]
co
```

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
name | Configuration name
key | Key
value | Value

## application.gitbook.messages.examples
* Set the Contact module flood limit to 10.
```
drupal config:override contact.settings flood.limit 10
```