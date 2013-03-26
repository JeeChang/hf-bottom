## Core DOM ##

### Node Object ###
Every document enherits from Node object.

1. Element
2. Attr(ibute) ######has nodeValue attribute
3. Text ######has nodeValue attribute
4. CDATASection ######has nodeValue attribute
5. EntityReference
6. Entity
7. ProcessingInstruction ######has nodeValue attribute
8. Comment ######has nodeValue attribute
9. Document
10. DocumentType
11. DocumentFragment
12. Notation

#### Node Relativeship ####

* childNodes
* parentNode
* previousSibling
* nextSibling
* firstChild
* lastChild

#### Node Attribute ####
attributes
:NamedNodeMap->getNamedItem() it is similar with [element].getAttribute()

#### Node ownerDocument ####

#### Check node/attribute ####
hasChildNodes()/hasAttributes()
childNodes/attributes

#### Operate Node ####
* appendChild()/insertBefore(new,ref)
* removeChild()
* replaceChild(new,old)
* cloneNode


### Core Element ###
* getAttribute/setAttribute/removeAttribute
* getAttributeNode/setAttributeNode/removeAttributeNode

### Core Document ###
* document.documentElement
* createAttribute()/createCDATASection(data)/createComment(data)/createDocumentFragment()/createElement(tagName)/createEntityReference(name)/createProcessingInstruction(target,data)/createTextNode(data)
* getElementById()/getElementsByTagName()

## DOM HTML ##

### HTML DOCUMENT ###
- title
- referrer
- domain
- URL
- body
- images
- applets
- links
- forms
- anchors
- cookie

+ open()
+ close()
+ write()
+ writeln()
+ getElementsByName()


### HTML ELEMENT ###
- id
- title
- lang
- dir
- className
