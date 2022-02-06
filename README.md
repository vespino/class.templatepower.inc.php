# class.templatepower.inc.php
Update  class.templatepower.inc.php
This library Used In a lot of Old Php from php4 to Now Some Of the Hosting companies Stop Supporting php 5 and if we transfer to php 7 you wil face this Error 
PHP Deprecated:  Methods with the same name as their class will not be
constructors in a future version of PHP;
SubClass has a deprecated constructor in
As this Lib USe PHP4-style constructor So I update this Lib To Support Php7 To not break everyone using this library, I have to keep backwards compatibility: Add the PHP5-style constructor, but keep the PHP4-style one. 
I Hope That Help any one Still Using This library
