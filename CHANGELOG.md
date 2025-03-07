# Changelog

### 0.15.3
* Fixed text wrapping of headline icons (e.g. +2)
* Fixed wrongly associated language keys

### 0.15.2
* Enrich the output of stunts and extras with entity links

### 0.15.1
* Allow skill ranks to go beyond +9

### 0.15.0
* Added compatibility to FoundryVTT v9

### 0.14.1
* Added the ability to change the image for unlinked items

### 0.14.0
* Another big round of style refactorings
* Added compatibility to the compendium folders module
* Made the actor system compatible to 0.8 again
* Updated all npm dependencies except for FoundryVTT types

### 0.13.0
* Fixed bug which sorted skills into alternating columns
* Added skill sorting by name and a sort reversal button

### 0.12.4
* Fixed sorting for aspects and consequences

### 0.12.3
* Updated Swedish transalation to include all character setup files (big thanks to contributor [Grottmastaren](https://github.com/Grottmastaren))
* Bug fixes for the template picker system

### 0.12.2
* Re-enabled the description field for skills

### 0.12.1
* Fixed a bug there the character biography was not editable anymore

### 0.12.0
* Big refactoring of all style files by [Pjb518](https://github.com/Pjb518)
* Updated compatability up to FoundryVTT 0.8.8

### 0.11.3
* Moved template preloading to the end of the init hook to prevent ActorSheets to be registered too late

### 0.11.2
* Changed terser settings to stop rewriting class names

### 0.11.1
* Fixed bug when opening the german sheet setup window

### 0.11.0
* Added compatibility to FoundryVTT 0.8 (big thanks to contributors [saif-ellafi](https://github.com/saif-ellafi) and [Pjb518](https://github.com/Pjb518))
* Updated all npm dependencies

### 0.10.0
* Added new translations
  * Swedish (big thanks to contributor [Grottmastaren](https://github.com/Grottmastaren))
* Updated all npm dependencies
* Added new "Alpha features" setting to system
  * This enables experimental alpha features. These are subject to change and could potentially break things.
* Added alpha version of the group system. This is still a very early, unfinished version. Only meant for deverloper use.

### 0.9.3
* Added new translations
  * Korean (big thanks to contributor [MaronKB](https://github.com/MaronKB))
* Updated all npm dependencies


### 0.9.2
* Fixed italian language file
* Updated all npm dependencies
* Fixed build errors

### 0.9.1
* Fixed biography editor 
* Better handling of tab height for actor sheets

### 0.9.0
* Started this changelog
* Added new translations
  * Chinese (big thanks to contributor [Nowpaper](https://github.com/Nowpaper))
  * Italian (big thanks to contributor [smoothingplane#6772](https://github.com/smoothingplane))
* [Added the ability to sort skills by rank](https://github.com/anvil-vtt/FateX/pull/40) (big thanks to contributor JeansenVaars#2857 / [Saif Addin](https://github.com/saif-ellafi))
* Switched to [foundry-vtt-types](https://github.com/League-of-Foundry-Developers/foundry-vtt-types) 
* Fixed some generic build / type errors
* Updated all npm dependencies
