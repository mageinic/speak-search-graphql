# Speak Search GraphQL

**Speak Search GraphQL is a part of MageINIC Speak Search extension that adds GraphQL features.** This extension extends Speak Search definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/speak-search-graph-ql 

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Speak Search GraphQL requires installing [MageINIC Speak Search](https://github.com/mageinic/Speak-Search) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/speaksearch
```

## 2. How to use

- To view the queries that the **MageINIC Speak Search GraphQL** extension supports, you can check `SpeakSearch GraphQl User Guide.pdf` Or run `Speaksearch Graphql.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
