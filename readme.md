## Drago Dirs

Easier access to individual directories.

## Instruction

Add the configuration file:

```
extensions:

	# Easier access to individual directories.
	dirs: Drago\Directory\DirsExtension
```

Inject the class to presenter and use:

```php
// Web directory
$this->dirs->getWebDir();

// Temporary directory
$this->dirs->getTempDir();

// App directory
$this->dirs->getAppDir();
```
