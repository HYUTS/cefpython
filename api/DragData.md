[API categories](API-categories.md) | [API index](API-index.md)


# DragData (object)


Table of contents:
* [Methods](#methods)
  * [IsLink](#islink)
  * [IsFragment](#isfragment)
  * [GetLinkUrl](#getlinkurl)
  * [GetLinkTitle](#getlinktitle)
  * [GetFragmentText](#getfragmenttext)
  * [GetFragmentHtml](#getfragmenthtml)


## Methods


### IsLink

| | |
| --- | --- |
| __Return__ | bool |

Returns true if the drag data is a link.


### IsFragment

| | |
| --- | --- |
| __Return__ | bool |

Returns true if the drag data is a text or html fragment.


### GetLinkUrl

| | |
| --- | --- |
| __Return__ | string |


Return the link URL that is being dragged.


### GetLinkTitle

| | |
| --- | --- |
| __Return__ | string |

Return the title associated with the link being dragged.


### GetFragmentText

| | |
| --- | --- |
| __Return__ | string |

Return the plain text fragment that is being dragged.


### GetFragmentHtml

| | |
| --- | --- |
| __Return__ | string |

Return the text/html fragment that is being dragged.


### GetImage

| | |
| --- | --- |
| __Return__ | [Image](Image.md) |

Get image representation of drag data. Check with HasImage() first,
otherwise if there is no image an exception is thrown.


### HasImage

| | |
| --- | --- |
| __Return__ | bool |

Whether image representation of drag data is available.
