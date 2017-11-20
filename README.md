# Chinese-Literature-NER-RE-Dataset
A Discourse-Level Named Entity Recognition and Relation Extraction Dataset  for Chinese Literature Text

We provide a new Chinese literature dataset for Named Entity Recognition (NER) and Relation Extraction (RE).
# Tagging set

We define 6 entity tags and 9 relation tags based on several available NER and RE datasets but with some additional categories specific to Chinese literature text. 
![ner.png](https://github.com/lancopku/Chinese-Literature-NER-RE-Dataset/blob/master/ner.png)
![relation.png](https://github.com/lancopku/Chinese-Literature-NER-RE-Dataset/blob/master/relation.png)

# Annotation Format

## Entity
Each entity is identified by T tag, which takes several attributes. 

Id: a unique number identifying the entity within the document. It starts at 0, and is incremented every time a new entity is identified within the same document. 

Type: one of the entity tags.
 
Begin Index: the begin index of an entity. It starts at 0, and is incremented every character.

End Index: the end index of an entity. It starts at 0, and is incremented every character.

Value: words being referred to an identifiable object.


## Relation
Each relation is identified by R tag, which can take several attributes: 

Id: a unique number identifying the relation within the document. It starts at 0, and is incremented every time a new relation is identified within the same document. 

Arg1 and Arg2: two entities associated with a relation.

Type: one of the relation tags.


The dataset is described at 
