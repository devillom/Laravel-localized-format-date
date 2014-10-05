#Laravel Localized date format

Copyright 2014 UNLIKE
Released under the MIT license

##Макросы

dd - пн, ddd - понедельник
mm - янв, mmm - января, mmmm - январь

DD - Пн, DDD - Понедельник
MM - Янв, MMM - Января, MMMM - Январь
  
##Examples

```php
Date::now()->format('j mmm Y');  // 5 октября 2014

Date::parse('2014-10-05')->format('ddd, j mmm Y');  // воскресенье, 5 октября 2014
Date::parse('2014-10-05')->format('DDD, j mmm Y');  // Воскресенье, 5 октября 2014
```