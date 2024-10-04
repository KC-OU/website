---
title: "{{ replace .Name "-" " " | title }}"

date: {{ now.Format "2006-01-02" }}
url: /{{ .Name }}/
image: images/gameboy-walkthroughts/{{ .Name }}.jpg
categories:
    - gameboy-walthroughs
tags:
  - gameboy
  - {{ .Name }}
draft: true
---
<!--more-->

## Walkthrough Video

{{< youtube "g2cZgF7fcNI" >}}
