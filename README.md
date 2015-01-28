#Jade it!
Jade-Boilerplate with some little mixins.


##Mixins
**+google-analytics(** *ID* , *Domainname* **)**

Creates the Google-Analytics-Code of an `ID` and `Domainname`.



**+js(** *jsFile* **,** *async* **)**

	<script src="[jsFile]" [async]></script>


	
**+css(** *cssFile* **)**

	<link rel="stylesheet" href="[cssFile]" />
		


**+browsehappy**

If the browser is outdated, a message with a link to browsehappy.com will be displayed.
	


**+meta(** *key*, *value* **)**	

	<meta name="[key]" content="[value]" />



**+og-meta(** *key*, *value* **)**	

	<meta property="og:[key]" content="[value]" />



**+page-meta(** *object* **)**	
Creates a meta-block with meta-tags for:

- description
- author
- keywords

and following og-meta-tags:

- title
- site_name
- description
- image
- url
- type







[![Analytics](https://ga-beacon.appspot.com/UA-54136231-1/jadeid/readme)](https://github.com/igrigorik/ga-beacon)
