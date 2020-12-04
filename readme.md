# localhost.localhost

An unpretentious welcome page for Laragon dev env which lists the directories present in its parent folder.

* Made for `.localhost` vhost configuration
* Vanilla php, which works fully offline

Note: If you want to automaticly redirect `http(s?)://localhost` to `https://localhost.localhost`, you can add an `index.php` file in your `www` folder like this :

```php
<?php

header('Location: https://localhost.localhost');
```

![Project screenshot](https://i.imgur.com/rQBRQNY.png)
