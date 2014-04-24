# Tempomat: Infrastruktur mit Qualität fortentwickeln und betreiben

Wir müssen das Thema der Qualität in der Infrastrukturentwicklung neu definieren.
Die Komplexität und Vielfalt nimmt täglich zu. Als Reaktion darauf müssen wir in der Adminstration und der Entwicklung
konsequenter automatisieren. Immer mehr wird deutlich, dass uns alle das Thema "Infrastruktur als Code" etwas angeht.
Eine neue komplexe Herausforderungen wird uns da beschert. 

In diesem Blog beginnen wir nun die testgetriebene Vorgehensweise auch für die Entwicklung der Infrastruktur zu adaptieren. Hierbei versuchen wir bestehende Techniken, Werkzeuge und Vorgehensweise vorzustellen.

## Setup
- Start von Intellij und import des Projekts (RubySDK installed)
- Öffnen eines Terminals
- jekyll serve --watch --drafts
- Öffnen eines Browser unter Adresse http://localhost:4000
- Editiren der blog post
- Reload des browser zeigt die Änderungen
- Bei Änderungen der _config.yml oder später der Inhalte des Verzeichnis _data ist ein Reload des webbrick Servers notwendig!

### Erzeugen einer neuer Post
    rake new_post
### Erzeugen einer neuen Seite
    rake new_page
### Testumgebung starten
    rake
           
## Links
- Blog Software Jekyll [Jekyll](http://jekyllrb.com/)
- Dieser Blog basiert auf dem Theme von [JekyllThemeDbykll](http://dbtek.github.io/dbyll/)
- Information zur markdown syntax [Markdown](http://daringfireball.net/projects/markdown/syntax#precode)
- Setup eines Jekyll blog [JekyllIntro](http://jekyllbootstrap.com/lessons/jekyll-introduction.html)
- Google Meta Tagging [GoogleMetaTagging](https://support.google.com/webmasters/answer/79812?hl=de)
- Jekyll bootstrap site generator [Jekyllbootstrap](http://jekyllbootstrap.com/)

## Infos
* http://blog.crowdint.com/2010/08/02/instant-blog-using-jekyll-and-heroku.html
* https://github.com/ejholmes/vagrant-heroku
* https://github.com/bry4n/rack-jekyll
* http://jekyllthemes.org/
* https://github.com/jamesallardice/jslint-error-explanations

## Link List ServerSpec

* http://serverspec.org
* http://de.slideshare.net/m_richardson/serverspec-and-sensu-testing-and-monitoring-collide
* http://de.slideshare.net/aschmidt75/testing-server-infrastructure-with-serverspec

## Copyright
* logo http://commons.wikimedia.org/wiki/File:Kontrollleuchte_Geschwindigkeitsregelanlage.svg

## License

- [MIT](http://opensource.org/licenses/MIT)

