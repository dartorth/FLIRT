## DIARIES

This is a dynamic input method that allows the building of an interface that will 
enable fast data entry using data already entered.

* a cloud class is created  `cloud=new Cloud(parentId,size)`, with a phraseLst
* phrase element can be created `cloud.addPhrase()` and added to the  phraseList of the cloud; the element created is also returned
* the phraseElement can be positioned `cloud.setPosition(element,position)`
* the phraseElemenst can be tested for overlap `cloud.overlap(el1,el2)`
