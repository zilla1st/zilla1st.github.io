Libre Writer to Github page

# 1\. Text

Nach der Überschrift 1 folgt normaler Text. 

Das war ein Umbruch.

# 2\. Bilder

Hier wird ein Screenshot eingefügt..

![](/images/100002010000024B0000006D0CB7F2B069FC12F6.png)

.. und dann geht es mit Text weiter.

Und dann kommt der Test.

![](/images/10000201000000630000006FC0B61C0D76045959.png)

Text links, Bild rechts davon

Cmd-Line Befehl:

pandoc -o 2020-01-21-LibreWriter\_to\_GithubPage.md --extract-media=2020-01-21-LibreWriter\_to\_GithubPage/ 2020-01-21-LibreWriter\_to\_GithubPage.odt -w gfm --atx-headers --columns 9999


{% include screenshot url="100002010000024B0000006D0CB7F2B069FC12F6.png" %}
