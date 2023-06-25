# flatjak

## What is flatjak?
Well, as the description says, `flatjak` is a little bash script that installs **Flatpak** with necessary software center and desktop integrations & enables the all important **Flathub** repository in **Ubuntu** & its derivatives. `flatjak` should work fine on **Debian** and other **Debian** based distributions too.    

## Why flatjak?
All official flavors of **Ubuntu** will stop including **Flatpak** by default from version **23.04** (**Lunar Lobster**) onward. Here is an excerpt from Canonical's announcement on this subject,  
> As part of our combined efforts, the Ubuntu flavors have made a joint decision to adjust some of the default packages on Ubuntu: Going forward, the Flatpak package as well as the packages to integrate Flatpak into the respective software center will no longer be installed by default in the next release due in April 2023, Lunar Lobster.  

Installing the **flatpak** package in any **Ubuntu** based distribution is relatively straight forward but installing **Flatpak** with necessary **software center** and **desktop** integrations can be tricky for many users. `flatjak` makes this task as easy as possible, even for new users. `flatjak` also enables the all important **Flathub** repository.  

## How to install and use flatjak?  
It's easy-peasy to install `flatjak`. Just download flatjak-main zip, extract its contents and copy the file `flatjak` to **/usr/local/bin/** directory,  

```bash
sudo cp flatjak /usr/local/bin/
```

And make it executable,  

```bash
sudo chmod 755 /usr/local/bin/flatjak
```

Using `flatjak` is even simpler, all you need to do is open a terminal emulator and run,  

```bash
sudo flatjak
```

`flatjak` will install **Flatpak** with all the bells and whistles for you.  

## Support:

If you liked `flatjak`, please consider supporting it, even the smallest contribution goes a long way. It is quick & easy via **PayPal**, **Buy Me a Coffee**, **Liberapay** or **Stripe**:  

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://paypal.me/hakerdefo)  

[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/hakerdefo)  

[![Support via Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/hakerdefo/donate)  

[**Support via Stripe**](https://buy.stripe.com/28odRcfob9or41OdQQ)

## License:

[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">flatjak</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/flatjak)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.github.io), is free of known copyright restrictions.  

[flatjak-main]:https://github.com/hakerdefo/flatjak/archive/refs/heads/main.zip  
