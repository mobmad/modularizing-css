.front-page

# Strukturert CSS

Fagdag i BEKK

Mads Mobæk

31/08/2012

---

# Mål

* Best mulig ytelse for sluttbruker 
	* 1-3 css-requests
	* Raskt for nettleser (todo: finn dokumentasjon på om det er noen vits å mikrooptimalisere bruk av id fremfor klasser osv.)
* Modularisert slik at det er enkelt å
	* vedlikeholde
	* gjenbruke

---

http://www.justinmarsan.com/blog/researches/2012/04/21/css-methodology-oocss-bem-smacss/

http://lea.verou.me/2011/03/on-css-preprocessors/

http://37signals.com/svn/posts/3003-css-taking-control-of-the-cascade

http://nicolasgallagher.com/about-html-semantics-front-end-architecture/

http://www.slideshare.net/stubbornella/our-best-practices-are-killing-us

http://coding.smashingmagazine.com/2012/06/19/classes-where-were-going-we-dont-need-classes/

http://coding.smashingmagazine.com/2012/04/20/decoupling-html-from-css/

http://www.markdotto.com/2012/03/02/stop-the-cascade/

Semantisk css?

* Semantisk HTML eller CSS? (microformats, HTML5). Er det noen vits?
	* http://coding.smashingmagazine.com/2011/11/11/our-pointless-pursuit-of-semantic-value/
	* http://coding.smashingmagazine.com/2011/11/12/pursuing-semantic-value/
	* Semantikkens verdi sammen med JS
	* W3C HTML5 spec: "authors are encouraged to use values that describe the nature of the content, rather than values that describe the desired presentation of the content"

* OOCSS
	http://coding.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/
	* Separer 
		* struktur og skin
		* container og innhold
	* Flere klasser i markup.
	* Vanskeligere å ta i bruk på en eksisterende side?
	* Har ikke semantiske klasser (dvs. de er stil-semantisk, men ikke innholds-semantisk)

* BEM
	http://coding.smashingmagazine.com/2012/04/16/a-new-front-end-methodology-bem/
	http://bem.github.com/bem-method/pages/beginning/beginning.en.html

# CSS-patterns?

---

# CSS preprocessors

* Konkatenering
* (Minifisering)
* Nettleserstøtte

* Noen alternativer
	* LESS
	* SASS
	* Stylus

---


# LESS

---

# SASS

* Avhengighet til Ruby
* Compass
	* Sprites

---

# Drawbacks

http://blog.millermedeiros.com/there-is-no-spoon/

* Kan få generert store CSS-filer ved uheldig bruk av mixins/include (eksempel)
* Kan få for spesifikke selektorer/store filer ved overdreven bruk av nøsting
* Noe mer komplekst utviklingsmiljø (og byggmiljø)
* Ikke gitt at det lønner seg i veldig små prosjekter