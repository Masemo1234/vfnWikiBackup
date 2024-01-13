---
title: Template Zauber
description: 
published: 1
date: 2024-01-13T12:52:03.313Z
tags: 
editor: markdown
dateCreated: 2024-01-13T12:47:54.533Z
---

# Name des Zaubers
**Zauberschule**
**Level:** Liste der enthaltenden Zauberlisten
**Komponenten:** V,S,M
**Zauberzeit:** z.B. Rundenhälfte
**Reichweite:** z.B. Berührung,10m/level
**Ziel oder Bereich:** z.B. Berührtes Objekt, 3m Radius
**Dauer:** 10 min./level
**Save:** z.B. s. Text/Wille Halbiert/Reflex negiert
**Zauberresistenz:** Ja/Nein

> Hier ist Platz für Flavortext und Infos


## Roll20 Makro
`&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Zaubertemplate!](http://g07ch4.com:3000/e/en/faq/zaubergrad)}} {{School:= Enchantment}} {{Cmpnts:=V, S, M}} {{Casting Time:=1 Rundenhälfte}} {{Range:= Berührung}} {{Target:= 3m Radius}} {{Duration:= 1 round/level (D); see text}} {{Saving Throw:= Will negates; see text}} {{Spell Resist.:= Yes}} {{Range touch: = [[ 1d20+@{casterlevel2} ]] [[ 1d20+@{casterlevel2}+@{spellpen} ]] vs spell resistance.}} {{check=2 missiles blast from the caster's fingers,}} {{checkroll=hitting for [[ 1d4+1 ]] | [[ 1d4+1 ]] force damage.}} {{notes=  You blast your enemies with magic missiles. }}`