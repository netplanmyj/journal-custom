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

## Ghostプラグイン
Local環境でjsonをダウンロードしようとするとWarningが表示されて失敗。
wp-config.php に、
```
ini_set('display_errors',0);
error_reporting(0);
```
を追加して再起動したところダウンロードできました。

## サイト内検索
[How to Add Google Custom Search to Ghost](https://ghost.org/docs/tutorials/google-custom-search/)

# GitHub Actions によるデプロイ
[Use GitHub Actions to deploy your theme](https://ghost.org/integrations/github/)
