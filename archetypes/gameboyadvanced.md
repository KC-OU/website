---
title: "{{ replace .Name "-" " " | title }}"

date: {{ now.Format "2006-01-02" }}
url: /{{ .Name }}/
image: images/gameboyadvanced-walkthroughts/{{ .Name }}.jpg
categories:
    - gameboyadvance-walthroughs
tags:
  - Gameboy Advanced
  - {{ .Name }}
draft: true
---
<!--more-->

## Walkthrough Video

{{< youtube "g2cZgF7fcNI" >}}
