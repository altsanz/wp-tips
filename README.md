# Wordpress development tips
Some wordpress development tips, like a cookbook.

## Widgets

### Widget images
Add an asset with proper url:

```php
<?php printf(
    '<img src="%1$s" alt="{YOUR COMPANY} logo" />',
    plugins_url( '/assets/images/company_logo.png', __FILE__ )
); ?>
```
