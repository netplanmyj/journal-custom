# journal-custom

## ローカル環境でのテーマ編集について
[How to install Ghost locally](https://ghost.org/docs/install/local/)


## Developing Themes
```
/content/themes/
```
ここに配置すること。

## Validating with GScan
検証のしかた。
```
# Install gscan globally
npm install gscan -g

# Scan a theme directory for compatibility
gscan /path/to/ghost/content/themes/casper

# Scan a theme zip file for compatibility
gscan -z /path/to/downloads/theme.zip
```
## Google Analyticsのタグについて
[Google Analytics + Ghost](https://ghost.org/integrations/google/)

Use Ghost `Code Injection`  
ということで Settings からエディタを開いてヘッダー・フッターに必要なタグを保存できます。
