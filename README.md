#  PyMaker
## ___Python NFT creator___

Py maker is an easy to use script to generate nft

- Generate images
- Generate metadata

## HOW TO USE
Open __config.py__ file

![изображение](https://user-images.githubusercontent.com/48851275/154809124-cb52bf95-4867-4a2a-bad5-924cecd0bcac.png)
<code>
	"CountOfNFT": 100,#count of nft to create
	"Layers":{
		"first":  [["Background"], ["layers\\body"]],
		"second": [["body"],       ["layers\\body"]] ,
		"third":  [["hairstyle"],  ["layers\\hairstyle"]] ,
		"fourth": [["glases"],     ["layers\\glases"]] 
	},
	"NFTformat":{
		"width":  1750,
		"height": 1750,
	}
</code>
___CountOfNFT___ - set int count of nft to create

___"Layers":{
___"first":  [["Background"], ["layers\\body"]],___
___"second": [["body"],       ["layers\\body"]] ,___
___"third":  [["hairstyle"],  ["layers\\hairstyle"]] ,___
___"fourth": [["glases"],     ["layers\\glases"]] ___
___},___
You must  change links to your parts of nft(You can add how mutch want links)

____	"NFTformat":{
		"width":  1750,
		"height": 1750,
	}____
You must change to size of your nft

#BUILD
when you do this all, you can build, start __main.py__ file, and wait




