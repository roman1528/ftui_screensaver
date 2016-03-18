# ftui_screensaver


```html
<div data-type="screensaver"
     data-timeout="60">
     <!--INHALT FÜR DEN SCREENSAVER AB HIER-->
     <!--ALLE FTUI-ELEMENTE ODER EIGENE-->
     <!--SWIPER UND POPUP FUNKTIONIEREN WAHRSCHEINLICH NICHT-->
</div>
```

Wenn ihr, so wie ich, mit PageTab arbeitet reicht es wenn ihr dieses
```html
<div>
```
nur auf der ersten Seite (wahrscheinlich index.html) irgendwo unten vor
```html
</body>
```
einfügt. Der Screensaver ist dann auf allen Unterseiten gleich.

---

Wenn ihr einzelne Seiten verwendet muss dieses
```html
<div>
```
auf jeder Seite irgendwo unten vor
```html
</body>
```
eingefügt werden. So kann man natürlich auf jeder einzelnen Seite einen eigenen Screensaver-Inhalt bauen.

data-timeout="60" // Timeout in Sekunden bis zur (Re)Aktivierung. 60 ist der Standardwert.

Datei muss in /tablet/js/
