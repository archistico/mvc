# Test MVC
  
Autoload, phpunit ecc.  

## Info
  
composer init  
composer require --dev phpunit/phpunit  
// Aggiungo autoload in composer.json  
composer dump-autoload  
php -S 127.0.0.1:8000 -d display_errors=1  

git remote add origin https://github.com/archistico/mvc.git
git push origin master

// PHPUNIT
./vendor/bin/phpunit tests/Framework/AppTest.php