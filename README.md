# MyBearerToken

# Install

```
composer require emalherbi/mybearertoken
```

# Usage

```php
require_once 'vendor/autoload.php';

$bearer = new MyBearerToken\MyBearerToken();
$token = $bearer->getBearerToken();

echo $token;
```

# References

[wildiney](https://gist.github.com/wildiney/b0be69ff9960642b4f7d3ec2ff3ffb0b)
