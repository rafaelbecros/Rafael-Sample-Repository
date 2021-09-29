<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Garcia De Orta" 
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Matadecacao.jpg/400px-Matadecacao.jpg">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is some sample text for the visual essay based on my topic for my paper.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Garcia De Orta_ Garcia de Orta (or Garcia d'Orta) (1501? – 1568) was a Portuguese Renaissance Sephardi Jewish physician, herbalist and naturalist
       label="G" 
       description="Garcia de Orta, 1906, by Veloso Salgado" 
       license="public domain" 
       url= <"https://upload.wikimedia.org/wikipedia/commons/8/8a/Garcia_de_Orta_%28c._1906%29_-_Veloso_Salgado.png">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
