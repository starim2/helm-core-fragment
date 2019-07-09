# Helm Core Fragment

A catalog of [MegaMek](https://github.com/MegaMek) robot units in MTF and JSON format.

There's been some small tweaks to a few of the mtf files in the catalog to improve consistancy. Some things are still outstanding, e.g. 'history' vs. 'hist'.

The json versions are close approximations of the mtf structure, though unit name, model, alias, and nicknames are in separate fields, and a variety of things that should be numbers are strings. The schema is my first time making one so... it's probably not great and may be removed. 


`catalog.json` includes entries for each unit where
```
	id: Unit file name (sans extension)
	name: "
	model: "
	alias: Alternative name, e.g. Daishi. Optional.
	modelNickname: e.g. Yen Lo Wang
```

`catalog.json` and json files and were generated with a separate MTF parser that I hope to release eventually. 
