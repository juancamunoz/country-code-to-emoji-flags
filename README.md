# Country Code 🔡 ➡️ Emoji Flag 🇬🇧

[![Download per Month](https://img.shields.io/packagist/dm/peterkahl/country-code-to-emoji-flag.svg)](https://packagist.org/packages/peterkahl/country-code-to-emoji-flag)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

Converts a country code to emoji flag. Most flags use a 2-letter code, but some use more (eg England=gbeng, Scotland=gbsct, Wales=gbwls, etc).

## Why Emoji❓
Emoji symbol is a textual replacement for a graphic image file while having the benefits of a graphic image. The image file is already present at your intended destination (a person's device), so why would you transmit the image to them again and again? -- Use emoji!


```php
use juancamunoz\flagEmoji\flagEmoji;

echo flagEmoji::convert('uk');    # 🇬🇧
echo flagEmoji::convert('gbwls'); # 🏴󠁧󠁢󠁷󠁬󠁳󠁿
echo flagEmoji::convert('gbsct'); # 🏴󠁧󠁢󠁳󠁣󠁴󠁿
echo flagEmoji::convert('gbeng'); # 🏴󠁧󠁢󠁥󠁮󠁧󠁿

```
# country-code-to-emoji-flags
