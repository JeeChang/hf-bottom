# DOM #

## Core Object ##

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
appendChild()/insertBefore(new,ref)
removeChild()
replaceChild(new,old)
cloneNode


### Core Element ###

getAttribute/setAttribute/removeAttribute
getAttributeNode/setAttributeNode/removeAttributeNode
