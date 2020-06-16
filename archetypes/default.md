---
title: "{{ replaceRE "[0-9]{2,}" "" .Name | replaceRE "^-*" "" | replaceRE "-" " " | title }}"
date: {{ .Date }}
lastmod: 

slug: ""
description: ""
# images is optional, but needed for showing Twitter Card
featured_image: ""

author: "Kip Jiang"
draft: false
comment : true
disableToC: false
disableAutoCollapse: false

categories: ""
tags: [""]
---