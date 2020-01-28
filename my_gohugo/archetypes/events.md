---
title: "{{ replace .Name "-" " " | title }}"
address: ""
postalCode: 75000
city: "Paris"
label: ""
when: {{ now.Format "2006-01-02" }}
description: ""
draft: true
photos: []
important: false
association: ""
tags: 
- past
- upcoming
---