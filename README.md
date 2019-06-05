Support phpMyAdmin 4.8 (+ v4.9 verified)

## Install

Put the theme folder to your phpMyAdmin/themes folder
### XAMPP in Windows
\xampp\phpMyAdmin\themes

### MAMPP in MacOS
/Applications/MAMP/bin/phpMyAdmin

Open phpMyAdmin dashboard and change theme to **pmahomme_dark** at *Appearance settings*

### Force default theme (optional)
Add this settings to your _config.inc.php_ file:

```conf
$cfg['ThemeDefault'] = 'pmahomme_dark';
$cfg['ThemePath']   = './themes';
$cfg['ThemeManager']    = true;
```

---
