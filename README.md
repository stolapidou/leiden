https://github.com/hmteditors/leiden/
README.md

**This is the working directory of the Leiden sub-group of the Homer Multitext Project.**

#Leiden

Editing HMT material at Leiden University

*Iliad* 13 in the Venetus A: folios 164 recto - 169 recto (inclusive)

##Table of contents

- [What is there on a folio?](https://github.com/hmteditors/leiden#what-is-there-on-a-folio)
- [What ought to be done to complete a folio?](https://github.com/hmteditors/leiden#what-ought-to-be-done-to-complete-a-folio)
- [Which files ought to be edited?](https://github.com/hmteditors/leiden#which-files-ought-to-be-edited)
- [Which lines are there on each folio?](https://github.com/hmteditors/leiden#which-lines-are-there-on-each-folio)
- [Progress](https://github.com/hmteditors/leiden#progress)
- [Basic infrastructure for working with digital representations of manuscripts](https://github.com/hmteditors/leiden#basic-infrastructure-for-working-with-digital-representations-of-manuscripts)
- [Useful links for editing](https://github.com/hmteditors/leiden#useful-links-for-editing)

##What is there on a folio?

* The main text of the *Iliad*
* Main scholia
* Intermarginal (*im*) scholia (between the main text and the main scholia)
* Interlinear (*il*) scholia (between the lines of the main text)
* Interior (*int*) scholia (in the inner margin of the folio, *i.e.* to the left of the main text on *recto* pages and to the right of the main text on *verso* pages)
* Exterior (*ext*) scholia (in the outer margin of the folio, *i.e.* to the right of the main scholia on *recto* pages and to the left of the main scholia on *verso* pages)
* Special signs, numbers, and abbreviations (these can be ignored for now, because this is done systematically by someone else)

**NB**: not all folios have all types of scholia

##What ought to be done to complete a folio?

* Make a palaeographic sample of every glyph in the first line of the main text on each folio (`csv`)
* Index the individual lines of the main text (`csv`)
* Index the individual main, *im*, *il*, *int*, and *ext* scholia (`csv`)
* Transcribe the individual lines of the main text (`xml`)
* Transcribe the individual main, *im*, *il*, *int*, and *ext* scholia (`xml`)

##Which files ought to be edited?

* `collections/paleography{folio}.csv`
* `indices/venA-textToImage-Iliad.csv`
* `collections/venA-mainScholia{folio}.csv`
* `collections/venA-intermarginal{folio}.csv`
* `collections/venA-interlinear{folio}.csv`
* `collections/venA-interior{folio}.csv`
* `collections/venA-exterior{folio}.csv`
* `editions/Iliad/{folio}.xml`
* `editions/scholia/MainScholia{folio}.xml`
* `editions/scholia/IntermarginalScholia{folio}.xml`
* `editions/scholia/InterlinearScholia{folio}.xml`
* `editions/scholia/InteriorScholia{folio}.xml`
* `editions/scholia/ExteriorScholia{folio}.xml`

##Which lines are there on each folio?

* **164r**: *Iliad* 13.1-25
* **164v**: *Iliad* 13.26-50
* **165r**: *Iliad* 13.51-75
* **165v**: *Iliad* 13.76-100
* **166r**: *Iliad* 13.101-125
* **166v**: *Iliad* 13.126-150
* **167r**: *Iliad* 13.151-177
* **167v**: *Iliad* 13.178-204
* **168r**: *Iliad* 13.205-229
* **168v**: *Iliad* 13.-
* **169r**: *Iliad* 13.-

##Progress

<table>
  <tr>
    <td> </td> <td> </td>
    <td> 164v</td> <td> 164r</td> <td> 165v</td> <td> 165r</td> <td> 166v</td> <td> 166r</td> <td> 167r</td> <td> 167v</td> <td> 168r</td> <td> 168v</td> <td> 169r</td>
  </tr>
  <tr>
    <td>paleography</td> <td>(<b>csv</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>main text indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  -  </td> <td>  -  </td>
  </tr>
  <tr>
    <td>main scholia indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>intermarginal scholia indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>interlinear scholia indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>interior scholia indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>exterior scholia indices</td> <td>(<b>csv</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  y  </td> <td>  y  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td> </td> <td> </td>
    <td> 164v</td> <td> 164r</td> <td> 165v</td> <td> 165r</td> <td> 166v</td> <td> 166r</td> <td> 167r</td> <td> 167v</td> <td> 168r</td> <td> 168v</td> <td> 169r</td>
  </tr>
  <tr>
    <td>main text</td> <td>(<b>xml</b>)</td>
    <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  y  </td> <td>  -  </td> <td>  -  </td>
  </tr>
  <tr>
    <td>main scholia</td> <td>(<b>xml</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>intermarginal scholia</td> <td>(<b>xml</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>interlinear scholia</td> <td>(<b>xml</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>interior scholia</td> <td>(<b>xml</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
  <tr>
    <td>exterior scholia</td> <td>(<b>xml</b>)</td>
    <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td> <td>  ?  </td>
  </tr>
</table>


**NB**: *y*: yes, finished; *?*: unclear

##Basic infrastructure for working with digital representations of manuscripts

- creating a model of the page sequences of Leiden University, codex VGF 64
- creating a navigational index of Iliad lines in VGF 64

##Useful links for editing

* http://www.homermultitext.org/hmt-digital/svcforms (to search for images of a folio; it is recommended to have the Venetus A and the Comparetti open in adjacent tabs, *especially* when working on the exterior scholia)
* https://homermultitext.github.io/hmt-docs/totaled/ (to look up the HMT project principles)
* https://homermultitext.github.io/hmt-editors-guide/editorial-policies/ (to look up the HMT `xml` editing standards)
* https://homermultitext.slack.com (to contact Neel or Stephanie)

