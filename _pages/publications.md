---
layout: page
permalink: /publications/
title: Publications
description: Peer-reviewed publications and research outputs.
nav: true
nav_order: 3
---

## Peer-reviewed publications

<div class="publications">
{% bibliography --query @*[type=peer-reviewed] %}
</div>

## Preprints & manuscripts under review

<div class="publications">
{% bibliography --query @*[type=preprint] %}
</div>

## Theses

<div class="publications">
{% bibliography --query @*[type=thesis] %}
</div>