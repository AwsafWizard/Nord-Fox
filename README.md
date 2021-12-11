# Nord-Fox
Custom firefox startpage

![](/screenshots/Screenshot_20211210_162847.png)

## Set as Home Page

Go to settings, search for `Home`. Then in the drop down list for `Homepage and new windows` select `Custom URLs` and copy the location of `index.html` file.

![](/screenshots/Screenshot_20211211_155122.png)

## Set as New Tab Page

First edit `mozilla.cfg` and put the location of `index.html` in `newTabURL`. Then open terminal in the location of newTab directory and paste the following commands -

```
sudo cp mozilla.cfg /usr/lib/firefox/
sudo cp local-settings.js /usr/lib/firefox/defaults/pref/
```

or copy `mozilla.cfg` to `/usr/lib/firefox/` and `local-settings.js` to `/usr/lib/firefox/defaults/pref/` .
