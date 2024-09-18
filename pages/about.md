---
title: Essay
layout: about
permalink: /about.html
credits: false
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="media_image" %}

{% include feature/nav-menu.html sections="Styling;Embedding" %}

## Styling

Enhance your text using the features that are located in the Includes>Feature folder of your repository. 

These include:

{% include feature/blockquote.html text="Blockquotes to help call out specific text" speaker="The Author" source="The Literary Source" %}

{% include feature/card.html text="Which can also incorporate your items your media and alt text to make the image fully accessible." header="Cards" objectid="media_image" width="50" alt="Woman posing for a photo wearing glasses and a floral print dress." centered="true" %}

{% include feature/alert.html text="And alerts for your readers" color="info" align="center" %}

## Embedding

**Intersperse** the media around your text where ever you think they will make the biggest impact.

{% include feature/audio.html objectid="media_audio" caption=" Featured media will automatically link to the full item page with complete metadata, even if you only have an essay page listed in navigation as we do here." %}

{% include feature/pdf.html objectid="media_doc" caption="PDF files can be viewed in full without the reader needing to jump out to the item level page." %}

{% include feature/video.html objectid="media_video" %}

