---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: photo
photo: "{{ replace .Name "-" " " | title }}.JPG"
resolution: 0
camera: 0
exposuretime: 0
focallength: 0
fstop: 0
ISO: 0
---
![your image](/images/{{ replace .Name "-" " " | title }}.JPG)