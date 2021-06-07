---
marp: true
title: Project organization
description: Multidimensional Software Project management structure
theme: default
paginate: false
style: |
    section {
        display: block;
        color: #cccccc;
        background-color: black;
        background-image: url("img/logo.png");
        background-position: top right;
        background-repeat: no-repeat;
        padding: 50px;
        font-size: 170%;
    }
    section h1 {
        color: white;
        font-weight: bold;
        font-size: 170%;
    }
    section.lead {
        padding: 100px;
    }
    section.lead h1 {
        font-size: 250%;
        font-weight: bold;
    }
    section.lead h2 {
        font-size: 200%;
    }
    XXXsection th {
        background-color: #444444;
    }
    XXXsection td {
        background-color: black;
    }
    .container {
        display: flex;
    }
    .column {
        flex: 1;
        padding: 0 30px;
    }
    .red {
        color: red;
        font-weight: bold;
    }
    .orange {
        color: orange;
        font-weight: bold;
    }
    .green {
        color: green;
        font-weight: bold;
    }
    .why {
        color: #7777ff;
    }
    .fix {
        color: #77ff77;
    }
    .res {
        color: #aaaaff;
        font-weight: bold;
    }

    section.white-page {
        color: black;
        background: url(img/logo.png) top right no-repeat;
        background-color: white;
        XXXbackground: url(img/background.jpg);
        XXXbackground-size: cover;
    }
    section.white-page h1 {
        color: black;
    }
    section.white-page th {
        background-color: #cccccc;
    }
    section.white-page td {
        background-color: #eeeeee;
    }

    section.yellow-page {
        color: black;
        background-color: #ffffaf;
        background-image: url("img/logo.png");
    }
    section.yellow-page h1 {
        color: black;
    }
    section.yellow-page blockquote {
        color: green;
        border-left: .25em solid green;
    }

    section.green-page {
        background-color: green;
    }
    section.green-page th {
        background-color: #004400;
        font-size: 85%;
    }
    section.green-page td {
        background-color: #002200;
        font-size: 85%;
    }
    section.green-page pre {
        background-color: #112211;
    }
    section.green-page strong {
        color: lime;
    }
    section.green-page blockquote {
        color: lime;
        border-left: .25em solid lime;
    }
    section.green-page .hljs-string {
        color: yellow;
    }

    section.blue-page {
        background-color: blue;
    }
    section.blue-page strong {
        color: aqua;
    }
    section.blue-page a {
        color: yellow;
    }
    section.blue-page blockquote {
        color: lime;
        border-left: .25em solid lime;
    }

---
<!-- _class: lead white-page -->

Project organization
====================

Multidimensional Software Project management structure

<br><br><br><br><br><br><br>

Alexander Krapivin

2020.06.03

---
<!-- _class: white-page-->

![bg cover](img/background.jpg)

Background
==========

* 1
* 2
* 3

---
<!-- _class: white-page -->

![bg cover](img/background.jpg)

Required efforts
================

<div class="container">
<div class="column">

Development                  | MM
-----------------------------|---
Bla bla bla                  | 4​
Implement                    | 2​
Bla bla bla                  | 1​
Test                         | 6​
Bla bla bla                  | 8​
**TOTAL:**                   | 21

</div>
<div class="column">

Maintenance                  | MM
-----------------------------|---
Bla bla bla                  | 4​
Support                      | 1​2
Bla bla bla                  | 6+
**TOTAL:**                   | 22

</div>
</div>

---

<style scoped>
    section h1 {
        text-align: center;
    }
</style>

<br><br><br><br><br>

Have a nice day!
================

---
<!-- _class: white-page -->

Current deployment status
=========================

<div class="container">
<div class="column">

## ✅ Done

* 1
* 2
* 3
* 4

</div>
<div class="column">

## 🚧 ToDo

* 5
* 6
* 7

</div>
</div>

---
<!-- _class: white-page -->

Components, roles and responsibilities
======================================

![](img/modules.png)

