---
title: Lähmung aufheben
description: 
published: 1
date: 2024-01-13T16:43:20.246Z
tags: zauber
editor: markdown
dateCreated: 2024-01-13T16:43:20.246Z
---

# Lähmung aufheben
**Bannzauber**
**Level:** [Clr 3](/spellLists/cleric)
**Komponenten:** ? **Bitte eintragen**
**Zauberzeit:** 2/10 Runde
**Reichweite:** Mittel (30m.+3m/L)
**Ziel oder Bereich:** 1 Kreatur
**Dauer:** instant
**Save:** N/A
**Zauberresistenz:** Nein

> Hebt alle Lähmungseffekte im Zielbereich auf.


## Roll20 Makro
`&{template:DnD35StdRoll} {{spellflag=true}} {{name=@{character_name} }} {{subtags=casts [Lähmung aufheben!](http://g07ch4.com:3000/e/en/faq/zaubergrad)}} {{School:= Bannzauber}} {{Cmpnts:=V, S, M}} {{Casting Time:=1 Rundenhälfte}} {{Range:= Berührung}} {{Target:= 3m Radius}} {{Duration:= 1 round/level (D); see text}} {{Saving Throw:= Will negates; see text}} {{Spell Resist.:= Yes}} {{Range touch: = [[ 1d20+@{casterlevel2} ]] [[ 1d20+@{casterlevel2}+@{spellpen} ]] vs spell resistance.}} {{check=2 missiles blast from the caster's fingers,}} {{checkroll=hitting for [[ 1d4+1 ]] | [[ 1d4+1 ]] force damage.}} {{notes=  You blast your enemies with magic missiles. }}`