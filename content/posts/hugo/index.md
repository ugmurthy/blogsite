+++
date = '2025-03-04T16:07:43+05:30'
draft = false 
tags = ["hugo","technology","shortcodes"]
categories = ["HowTo"]
title = 'Using shortcodes in Hugo'
summary = "How to use shortcodes in Hugo"
linkToMarkdown = true
+++

Usings Short codes

## Details

Details allow you to expand some text below a given summary text

{{< details summary="See the details" >}}

> This is a **bold** world.This is a **bold** world. Don't tread lightly out here as there will be some nefarious character who could ambush you and that wont go well. So beware!
> {{< /details >}}

## Tweet

{{< x user="murthyug" id="1892509779504894447" >}}

## Figure

{{< figure src="heading.png" title="SpeechTrack (figure)" >}}

## Extended Shortcodes

_style_

{{< style "text-align:center; strong{color:#ffb100;}" >}}

This is a **right-aligned** paragraph.

{{< /style >}}

_admonition_

{{< admonition type=tip title="This is a tip" open=false >}}
A **tip** banner
{{< /admonition >}}

{{< admonition type=Example title="Few Examples" open=false >}}

1. This is an example
2. This is another example
3. This is the third example
   {{< /admonition >}}

{{< admonition type=quote title="My Favorite Quote" open=false >}}
_Spend a handful of hours a day going fast. Crush a gym session. Do deep work on a project you care about. Spend the rest of the day going slow. Take walks. Read books. Get a long dinner with friends. Either way, avoid the anxious middle where you never truly relax or truly move forward._

:-- Charles Miller

{{< /admonition >}}

**Music**

{{< music url="acrylic.wav" name=Wavelength artist=oldmanyoung cover="/images/Wavelength.jpg" >}}

**Typeit**

{{< typeit >}}
This is a _paragraph_ with **typing animation** based on [TypeIt](https://typeitjs.com/)...
{{< /typeit >}}

**mermaid**

**Pie Chart**

{{< mermaid >}}
pie
"Value 1" : 50
"Value 2" : 40
"Value 3" : 100
"Value 4" : 200
"Value 5" : 80
{{< /mermaid >}}

**GitGraph**

{{< mermaid >}}
gitGraph
commit
commit
branch develop
checkout develop
commit
commit
checkout main
merge develop
commit
commit
{{< /mermaid >}}

**Gantt Chart**

{{< mermaid >}}
gantt
dateFormat YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task :done, des1, 2014-01-06,2014-01-08
Active task :active, des2, 2014-01-09, 3d
Future task : des3, after des2, 5d
Future task2 : des4, after des3, 5d
{{< /mermaid >}}
