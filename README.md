Obsidian Moon Framework
=======================

<a name="installing"></a>
## Installing Obsidian Moon Engine

Since Obsidian Moon Engine uses [Composer](http://getcomposer.org) you will need to install it before you can run the
code with it. Once you have installed Composer you will then be able to install it by running the following command:

```bash
composer create-project dark-prospect-games/obsidian-moon-framework
```

Once installed you can change the namespace of your application's files by entering the following into the
`composer.json` file:

```json
{
  "autoload": {
    "psr-4": {
      "MyCompanyNamespace\\MyApplication\\": "src/"
    }
  }
}
```
