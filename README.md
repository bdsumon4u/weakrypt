#### A weak encryption/decryption tool for PHP.

###### Interesting fact is, the tool itself is mostly encrypted with the tool itself.

##### Before Encryption:

```php
<?php

if (mt_rand(1, 10) <= 3) {
    echo "Hello World\n";
} else {
    echo "Hotash World\n";
}
```

##### Encrypt

`php weakrypt file1.php file2.php file3.php ...`

##### After Encryption:

```php
<?php (require_once 'weakrypt')(__FILE__,'HotashTech','v1.0.0');
##!!!##QUVTLTI1Ni1DQkMjIyEhISMjNGJlZDMzMTFlNDY3ZjQyMTNkNzIyZWZhNmI0ZmU1ZDFmZTQ2NTFhZWI0NjVlMDNmYzlhM2U5ZGVhMzlmOWM3MSMjISEhIyMxZjFlZWJmNzEzNWI3N2IwNTFjMGIzODk2MDJmYTQ5ZSMjISEhIyN6THJsbWxoRHBPTElaWk5HK0dvbThIeXR2WGVLblkwY3p2elJwOHR0KzVKRHNtdS94S0hid05Qa1BsTG5nVDQyY29FbHdRb1JPT1Y3VjFOZ244M3NSSVJzZ0NDWDN2RUpaNWE0TmlMY2pwVT0=
```
