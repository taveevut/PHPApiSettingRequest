# PHPApiSettingRequest

```php
header( 'Content-type: application/json' );
header( "Access-Control-Allow-Origin: *" );
header( 'Access-Control-Allow-Headers: X-Requested-With, content-type, access-control-allow-origin, access-control-allow-methods, access-control-allow-headers' );
```

#### Angular js http request data
```php
$postdata = file_get_contents( "php://input" );
$request = json_decode( $postdata, TRUE );
```
