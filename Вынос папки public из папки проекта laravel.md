
```php
$app = _require_once __DIR__ . '/../cms/bootstrap/app.php';
app()->usePublicPath(__DIR__);
$app->handleRequest(Request::capture());
```

