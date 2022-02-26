---
title: "Home"
date: 2022-02-26T21:16:17Z
draft: true
---

{{ $visitor := getJSON "./netlify/functions/geolocate"}}

<p>{{ visitor }}</p>