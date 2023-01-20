
# C85C68464: Tengyur texts not in the Derge edition

This collection contains all of the texts included in the Pedurma edition of the Tengyur that aren't found in the Derge edition.

## Table of contents
<p align="center">
  <a href="#collection-content">Collection content</a> •
  <a href="#views">Views</a> •
  <a href="#data-preparation">Data preparation</a> •
  <a href="#quality-assurance">Quality assurance</a> •
  <a href="#questions-about-this-collection">Help</a> •
  <a href="#acknowledgments">Acknowledgments</a> •
  <a href="#terms-of-use">Terms of use</a>
</p>

## Collection content
- **456** texts presented in two views:
  - Without annotations
  - With annotations that reference the source image files
- Two folders containing the files:
  - [PlainBase](https://github.com/OpenPecha-Data/C85C68464/tree/main/PlainBase) contains plain `.txt` files without annotations
  - [HFML](https://github.com/OpenPecha-Data/C85C68464/tree/main/HFML) (Human Friendly Markup Language) contains `.txt` files with annotations that reference the source image files
- Two catalogs of the texts:
  - [Catalog_PlainBase.csv](https://github.com/OpenPecha-Data/C85C68464/tree/main/PlainBase) lists the PlainBase versions of the texts
  - [Catalog_HFML.csv](https://github.com/OpenPecha-Data/C85C68464/blob/main/Catalog_HFML.csv) lists the HFML versions of the texts
- A `.yml` file that defines the structure of the repo

## Views

This collection contains two views of the texts:
- PlainBase view, which is the texts as plain `.txt` files
- HFML view, which adds annotations using the Human Friendly Markup Language

### PlainBase view

This view presents the texts in plain `.txt` files without annotations.

### HFML view

This view presents the texts in `.txt` files with HFML annotations that reference the source image files.

**Annotation format**:
[image number] bdrc_image_file_name

<details >
<summary>Example</summary>

〔587〕 I1PD958870587.jpg
  
ཆེན་འབྱུང་གནས་སྣོད་གྱུར་ལ། །མྱ་ངན་འདས་པའི་ལམ་གྱི་མཆོག་སྟོན་པས། །

ཐམས་ཅད་དུ་ནི་བསམ་པ་རྫོགས་མཛད་པའི། །དེ་བཞིན་གཤེགས་པ་རྣམས་ལ་

ཕྱག་འཚལ་ལོ། །སེམས་ཅན་དོན་གྱི་བསམ་པ་རྫོགས་མཛད་ཅིང་། །གདུལ་བྱ་

པདྨའི་འབྱུང་གནས་སད་པར་མཛད། །ཡོན་ཏན་འབྱུང་གནས་སློབ་མ་མཆོག་་

ལས་རྒལ། །དེ་བཞིན་མཐའ་ཡས་བསྐལ་པར་བསགས་པའི་བསྟན་པ་ལ། །
  
</details>
  
## Catalog reference

Both the PlainBase and HFML catalogs follow this format:

| Field    | Description    | Example    |
| --- | --- | --- |
| File name    | Same as BDRC ID unless it doesn't have one. In that case, a unique ID is given.   | MW1PD95844_2598    |
| Title    | Title in Tibetan.     | དབང་གི་དོན་ངེས་པར་འབྱེད་པ།    |
| OP ID    | The text's OpenPecha ID.     | I00388DFB    |
| BDRC ID    | The text's BDRC ID.     | MW1PD95844_2598    |
| Volume Number    | The volume of the Pedurma Tengyur that the text is in.    | 43    |

<!--

## Data preparation



## Quality assurance

-->

## Questions about this collection?

* Email us at openpecha[at]gmail.com.
* Join our [Discord](https://discord.com/invite/7GFpPFSTeA).
* File an issue.

## Acknowledgments

<!-- Delete organizations that are not part of this collection -->

Thanks to the **Buddhist Digital Resource Center** for providing data used in this collection!

![BDRC logo](https://user-images.githubusercontent.com/51434640/194739598-8a630a40-b83e-46cd-9f52-3f746db9864f.png)

## Terms of use

This collection is provided by OpenPecha under the [CC0 Public Domain Dedication](/LICENSE.md).
