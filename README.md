Support phpMyAdmin 4.8 (+ v4.9 verified)

## Install

Put the theme folder to your phpMyAdmin/themes folder
### XAMPP in Windows
\xampp\phpMyAdmin\themes

### MAMPP in MacOS
/Applications/MAMP/bin/phpMyAdmin

Open phpMyAdmin dashboard and change theme to **pmahomme_dark** at *Appearance settings*

### Force default theme by adding this settings to your _config.inc.php_ file (optional)

```conf
$cfg['ThemeDefault'] = 'pmahmdark';
$cfg['ThemePath']   = './themes';
$cfg['ThemeManager']    = true;
```

---
