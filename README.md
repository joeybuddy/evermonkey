# EverMonkey

[![Build Status](https://travis-ci.org/michalyao/evermonkey.svg?branch=master)](https://travis-ci.org/michalyao/evermonkey)
[![bitHound Overall Score](https://www.bithound.io/github/michalyao/evermonkey/badges/score.svg)](https://www.bithound.io/github/michalyao/evermonkey)
[![bitHound Code](https://www.bithound.io/github/michalyao/evermonkey/badges/code.svg)](https://www.bithound.io/github/michalyao/evermonkey)
[![bitHound Dependencies](https://www.bithound.io/github/michalyao/evermonkey/badges/dependencies.svg)](https://www.bithound.io/github/michalyao/evermonkey/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/michalyao/evermonkey/badges/devDependencies.svg)](https://www.bithound.io/github/michalyao/evermonkey/master/dependencies/npm)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/michalyao/evermonkey.svg)](http://isitmaintained.com/project/michalyao/evermonkey "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/michalyao/evermonkey.svg)](http://isitmaintained.com/project/michalyao/evermonkey "Percentage of issues still open")


Evernoting in vscode with *Markdown* Support!


[Get Doc And Star Me](http://monkey.yoryor.me)

## Features

You can use `ever new` to create an untitle file with metadata support, edit it and use `ever publish` to publish it to evernote. And of course more than that.

Why EverMonkey is better? EverMonkey is inspired by the Sublime Text one, make local cache to avoid making net request everytime and in result
you got a faster experience.


**For tags use: you may have to use comma "," to split tags**. You can get tips if you insert tags already exsist. Otherwise a new tag will be created.

```
---
title: note title
tags: tag1, tag2, tag3
notebook: notebook
---
```



![example](assets/monkey.gif)

Result:

![result](assets/result.jpg)

## Extension Settings

**IMPORTANT: Please read this carefully before you start using the extension**

Use command `ever token` to help you get your token & noteStoreUrl. After enter that command (Or your can visit the page directly - [China](https://app.yinxiang.com/api/DeveloperToken.action) | [Other Countries](https://www.evernote.com/api/DeveloperToken.action)).

Then open your user setting by `Preferences: Open User Settings`, and copy&paste token info to (Search `evermonkey` to get you there):

* `evermonkey.token`: your developer token
* `evermonkey.noteStoreUrl`: your API url


## Known Issues

* If you edit your note content in other client. For example, in the Evernote client. Then when you open note in the vscode again, you will see some extra html in the markdown text. So try to edit your note only in evermonkey, this way the markdown text will stay clean.
* You can report issues here [Github issues](https://github.com/michalyao/evermonkey/issues)

-----------------------------------------------------------------------------------------------------------

## Buy me a coffee

If you really like evermonkey, what about buying me a coffee? :smile:

[paypal](https://paypal.me/Michalyao)

![支付宝](assets/alipay.png)

![微信](assets/wechatpay.jpg)

**Have fun!**

