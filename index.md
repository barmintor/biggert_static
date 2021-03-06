---
layout: default
coordinates:
  - 39.44,-98.70
---
{% include leaflet_assets.html %}
{% include leaflet_iiif.html manifest_uri="https://derivativo-2.library.columbia.edu/iiif/2/presentation/10.7916/D83B7B5F/manifest.json" %}

<br><br><br>

# Explore the Collection

{% comment %}{% include search.html %}{% endcomment %}

## About the Collection

The Robert Biggert Collection of Architectural Vignettes on Commercial Stationery was donated to the [Avery Architectural and Fine Arts Library](http://library.columbia.edu/locations/avery.html) by Robert Biggert in honor of Lisa Ann Riveaux. This unique collection of printed ephemera contains over 1,300 items with architectural imagery spanning the dates 1850 to 1920, in more than 350 cities and towns in forty-five states, as well as the District of Columbia and U.S. possessions. The collection's billheads, letterheads, envelopes, checks, and business cards document the rise of the United States as an industrial nation, in often elaborate vignettes of factories, warehouses, mines, offices, stores, banks, and hotels.

<br><br>
{% include leaflet_map.html coordinates=page.coordinates zoom=4 %}
<br><br>

## Browse the Collection

- [Companies]({{ site.baseurl }}/companies/)
- [Locations]({{ site.baseurl }}/locations/)
- [Image Gallery]({{ site.baseurl }}/gallery/)
