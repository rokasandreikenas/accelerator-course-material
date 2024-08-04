## HTML Klausimai

1. Kas yra HTML?

	HTML (_HyperText Markup Language_) yra standartinė teksto formatavimo kalba, naudojama kurti ir atvaizduoti interneto puslapius. HTML dokumentai yra sudaryti is elementų (_elements_) ir žymių (_tags_), kurie formatuoja tekstą tinkamam atvaizdavimui interneto puslapiuose.

2. Kuo skiriasi HTML ir XML formatavimo kalbos?

	HTML -  naudojamas atvaizduoti turiniui interneto svetainėse ir yra orientuotas į žmogaus ir kompiuterio sąveiką. XML -  naudojamas duomenims aprašyti ir perduoti, orientuotas į kompiuterių tarpusavio sąveiką.  

3. Kuo skiriasi HTML žymės (_tags_) ir elementai (_elements_)?

	HTML žymės (_tags_) naudojamos apibūdinti internetinio puslapio struktūrą. HTML elementai (_elements_) yra sudaryti iš HTML žymių (_tags_) rinkinio, kuris apibūdina konkrečias tinklapio dalis.

4.  Kokia yra HTML dokumento struktūra?

	HTML dokumentas prasideda nuo _<!DOCTYPE html>_ deklaracijos, po jos eina _<html>_ žymė (_tag_) apimanti _<head>_ ir _<body>_ elementus (_elements_).
				
	Pavyzdys:
	```html
	<!DOCTYPE html>  
	<html>  
		<head>  
			<title>Page Title</title>  
		</head>  
		<body>  
			<h1>My First Heading</h1>  
			<p>My first paragraph.</p>  
		</body>  
	</html>
	```
5. Kokia yra `<!DOCTYPE html>` deklaracijos paskirtis?

	 `<!DOCTYPE html>` deklaracija nurodo dokumento tipą ir naudojamos HTML kalbos versiją, kad naršyklės teisingai atvaizduotų turinį.  

6. Koks yra `<head>` žymės (_tag_) vaidmuo HTML dokumente?  

	`<head>` žymė (_tag_) apibrėžia informaciją apie tinklalapį, kuri nėra rodoma pačiame puslapyje (_tačiau yra nuskaitoma naršyklės ir paieškos sistemų (SEO)_), tokią kaip jo pavadinimas ar raktiniai žodžiai. Ji yra tarp `<html>` ir `<body>` žymių (_tags_) ir paprastai yra pirmasis HTML dokumento elementas.

7. Koks yra `<meta>` žymės (_tag_) vaidmuo HTML dokumente?

	`<meta>` žymė (_tag_) pateikia papildomą informaciją apie tinklalapį (naršyklėms ir paieškos sistemoms), tokią kaip autorius, aprašymas ir raktiniai žodžiai. Ji yra HTML dokumento `<head>` dalyje.

8. Koks yra `<link>` žymės vaidmuo HTML dokumente?

	`<link>` žymė (_tag_) apibrėžia ryšį tarp HTML dokumento ir išorinio resurso. Dažniausiai naudojama susieti su stiliaus (_CSS_) failais.

9. Kokios yra pagrindinės HTML žymės (_tags_)?

	Pagrindinės HTML žymės (_tags_) yra `<html>`, `<head>`, `<title>`, `<body>`, `<p>`, `<a>`, `<img>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<tr>`, `<td>`, `<th>`, `<form>`, `<input>`, `<select>`, `<option>`, `<button>`  ir `<div>`. 

10. Kas yra HTML atributai?

	Atributai tai yra HTML žymių (_tags_) savybės, kurios keičia kaip žymė (_tag_) elgiasi arba, kaip ji yra atvaizduojama. Pavyzdžiui, `<img>` žyma (_tag_) turi `src` atributą, kurį naudojate norėdami nurodyti šaltinį (_source_) (pvz., URL nuoroda į paveikslėlį arba kelias į paveikslėlį esantį jūsų kompiuteryje), iš kurio turėtų būti atvaizduojamas paveikslėlis. 

11. Kokią paskirtį turi HTML elementų `class` atributas?

	HTML  elementų `class` atributas nurodo HTML elementų klasę. Pagrinde naudojamas pritaikyti tam tikram stilių elementų grupei.

12. Kuo skiriasi HTML elementų `id` ir `class` atributai?  

	`id` atributas nurodo unikalų identifikatorių HTML elementui, o `class` atributas apibrėžia klasę elementų grupei, `id` gali būti naudojamas tik vieną kartą puslapyje, o `class` gali būti naudojamas daug kartų.

13. Kaip struktūrizuoti HTML lentelę?

	Lentelė struktūrizuojama naudojant `<table>` žymę (_tag_), su `<tr>` žyme (_tag_) eilutėms, `<td>` žyme (_tag_) duomenų langeliams ir `<th>` žyme (_tag_) antraštės langeliams.
	
	Pavyzdys:
	```html
	<table>  
		<tr>  
			<th>Month</th>  
			<th>Savings</th>  
		</tr>  
		<tr>  
			<td>January</td>  
			<td>$100</td>  
		</tr>  
	</table>	
	```

14. Kas yra HTML formos ir kaip jas kurti?

	HTML formos renka naudotojo duomenis, tokius kaip prisijungimo informacija arba paieškos užklausos. Formos gali būti sukurtos naudojant `<form>` žymę (_tag_), o įvesties laukai, gali būti pridedami naudojant `<input>` žymę (_tag_).

	Pavyzdys:

	```html
	<form>  
		<label for="fname">First name:</label><br>  
		<input type="text" id="fname" name="fname"><br>  
		<label for="lname">Last name:</label><br>  
		<input type="text" id="lname" name="lname">  
	</form>
	```

15. Kokie yra skirtingi HTML formos įvesties laukai?

	HTML formose yra keli įvesties laukų tipai, įskaitant teksto laukus, žymės langelius (_checkboxes_), pasirinkimo mygtukus (_radio buttons_), išskleidžiamuosius meniu (_select menus_) ir didesnės apimties teksto laukus (_text areas_). Kiekvienas įvesties lauko tipas naudojamas skirtingų duomenų rinkimui iš vartotojų.

16. Kaip sukurti HTML išskleidžiamąjį sąrašą (_dropdown list_)?

	Išskleidžiamasis sąrašas (_dropdown list_) yra sukuriamas naudojant `<select>` žymę (_tag_), su `<option>` žymėmis (_tags_) kiekvienam sąrašo elementui.

	Pavyzdys:

	```html
	<label for="cars">Choose a car:</label>  
	  
	<select name="cars" id="cars">  
		<option value="volvo">Volvo</option>  
		<option value="saab">Saab</option>  
		<option value="mercedes">Mercedes</option>  
		<option value="audi">Audi</option>  
	</select>
	```

17. Kokie yra skirtingi HTML sąrašų (_HTML lists_) tipai?

	HTML kalboje yra trys sąrašų tipai: `<ol>` numeruoti sąrašai (_ordered_), `<ul>` nennumeruoti sąrašai (_unordered_) ir `<dl>` apibrėžimų sąrašai (_definition_). Numeruoti sąrašai sužymėti skaičiais, nennumeruoti sąrašai – sužymėti ženklais, o apibrėžimų sąrašai yra terminų `<dt>` ir jų apibrėžimų `<dd>` sąrašai.

18. Kuo skiriasi HTML ir HTML5?

	HTML5 yra naujausia HTML kalbos versija. Pagrindiniai skirtumai yra multimedijos elementų (pvz., garso ir vaizdo) palaikymas, patobulinta semantika ir geresnis palaikymas mobiliems įrenginiams.

19. Kas yra semantinis HTML?

	Semantinis HTML (_semantic HTML_) yra HTML kodo rašymo stilius, sukurtas sustiprinti kodo arba turinio (_content_) prasmę. HTML elementai aiškiai nurodo jų turinį ir paskirtį, padarydami dokumentą lengviau suprantamą tiek žmonėms, tiek paieškos sistemoms (_SEO_) ir kitoms technologijoms.  
  
	Semantiniai HTML elementai:
	- `<header>` : nurodo puslapio arba sekcijos antraštę.

	- `<nav>` :  žymi navigacijos nuorodų rinkinį.

	- `<main>` : apibrėžia pagrindinį dokumento turinį.

	- `<article>` : apibrėžia nepriklausomą, savarankišką turinį.

	- `<section>` : naudojamas logiškai suskirstyti puslapio turinį į temines grupes.

	- `<aside>` : žymi turinį, kuris yra susijęs su pagrindiniu turiniu, bet nėra jo dalis.

	- `<footer>` :  nurodo puslapio arba sekcijos poraštę.

	- `<details>` : apibrėžia papildomą informaciją, kurią vartotojas gali peržiūrėti arba paslėpti.

	- `<summary>` : apibrėžia matomą antraštę <details> elementui.

	- `<figure>` : apibrėžia savarankišką vaizdinį turinį, pvz., iliustracijas, diagramas, nuotraukas, kodo sąrašus ir pan.

	- `<figcaption>` : Apibrėžia `<figure>` elemento antraštę.

	- `<mark>` : apibrėžia pažymėtą/pabrėžtą tekstą.

	 - `<time>` : apibrėžia datą/laiką.  

	Naudojant semantinį HTML, turinys tampa geriau struktūrizuotas ir lengviau suprantamas įvairioms interneto naršyklėms, ekrano skaitytuvams ir paieškos sistemoms (_SEO_).  

20. Kuo skiriasi `<section>` ir `<div>` žymės (_tags_)?

	`<section>` žymė apibrėžia dokumento dalį, skirtą teminiam turinio grupavimui.  
  
	Tuo tarpu `<div>` žymė yra bendrasis konteineris, naudojamas stilių pritaikymui arba elementų grupavimui CSS ar JavaScript tikslais.  

21. Kuo skiriasi `<div>` ir `<span>` žymės (_tags_) ?

	`<div>` žymė yra block elementas, naudojamas kitų HTML elementų grupavimui į konteinerį.  
  
	`<span>` žymė yra inline elementas, naudojamas stilių pritaikymui konkrečioms teksto dalims.

22. Kuo skiriasi inline elementas nuo block elemento?

	Inline elementai yra elementai, kurie neprasideda naujoje eilutėje ir užima tik tiek pločio, kiek reikia.  
  
	Block elementai yra elementai, kurie prasideda naujoje eilutėje ir užima visą tėvinio konteinerio plotį.

23. Kokia yra `alt` atributo paskirtis paveikslėliuose?

	`alt` atributas pateikia alternatyvų tekstą paveikslėliui, kai jo negalima atvaizduoti (pvz., dėl tech. priežasčių). Jis yra svarbus prieinamumui (_accessibility_) ir paieškos sistemoms (_SEO_).

24. Kam reikalingi Data- atributai?

	Data- atributai leidžia saugoti papildomą informaciją HTML elementuose, nenaudojant papildomų elementų ar sudėtingo JavaScript kodo. 

25. Kaip optimizuoti HTML dokumentą, paieškos sistemoms (_SEO_)?

	 Optimizuojant HTML dokumentą paieškos sistemoms (_SEO_), pirmiausia reikėtų naudoti semantines žymes (_tags_), kurios suteikia prasmingą informaciją apie jų apimamą turinį. Toliau reikėtų įtraukti meta aprašymus, efektyviai apibendrinančius puslapio turinį, tai didina matomumą paieškos sistemų (_SEO_) rezultatuose. Taip pat, pridedant alternatyvų tekstą paveikslėliams (_alt_), pagerinamas prieinamumas (_accessibility_), taip pat  paieškos sistemoms lengviau suprasti paveikslėlių turinį.

26. Kas yra iframe ir kaip jie naudojami?

	Iframe naudojami įterpti kitą dokumentą į esamą HTML dokumentą. Jie yra naudingi įterpiant žemėlapius, vaizdo įrašus ar kitus dokumentus.

27. Kokia yra HTML elemento `<canvas>` paskirtis?

	`<canvas>` elementas naudojamas piešti grafinius elementus tinklalapyje naudojant kodą (dažniausiai JavaScript).

28. Kokia yra HTML5 internetinės saugyklos (_web storage_) paskirtis?

	HTML5 internetinė saugykla (_web storage_) leidžia svetainėms saugoti duomenis naudotojo naršyklėje, taip pagerinant žiniatinklio programos veikimą ir naudotojo patirtį.


### Šaltiniai:

- https://emeritus.org/in/learn/html-interview-questions/
- https://dev.to/ahmed0saber/most-common-html-interview-questions-38k
- https://www.simplilearn.com/html-interview-questions-and-answers-article
