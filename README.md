# URL-Title
A library based on Codeigniter

# How to use

```php
use UrlTitle\Convert;

$title = new Convert();
$title->input("Albertho Malaquena Joris", 'dash', FALSE);
$output = $title->output;
echo $output;
//Output (if param set FALSE)
albertho-malaquena-joris
//Output (if param set TRUE)
Albertho-Malaquena-Joris
```