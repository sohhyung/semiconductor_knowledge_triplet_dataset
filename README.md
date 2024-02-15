# Semiconductor Domain Specific Knowledge Triplet Dataset


## Anotated Format
```
[{"abstract":'A fabrication process employing the use of ScAlN as an etch mask is disclosed. The ScAlN etch mask is chemically nonvolatile in fluorine-based etch chemistries and has a low sputter yield, resulting in greater etch mask selectivity and reduced surface roughness for silicon and other semiconductor materials. The ScAlN etch mask has an etch mask selectivity of greater than 200,000:1 relative to silicon compared to an etch mask selectivity of less than 40,000:1 for a prior art AlN etch mask relative to silicon. Further, due to reduced sputtering of the ScAlN etch mask, and thus reduced micromasking, the ScAlN etch mask yielded a surface roughness of 0.6 μm compared to a surface roughness of 2.8 μm for an AlN etch mask.', 
  "sentences":[
				{'sentence': 'A fabrication process employing the use of ScAlN as an etch mask is disclosed.',
				 'tagged_sentence': 'A <e1>fabrication process</e1> employing the use of <e2>ScAlN</e2> as an <e3>etch mask</e3> is disclosed.',
				 'keyphrases': ['fabrication process', 'ScAlN', 'etch mask'],
				 'labeled_relation': [[('etch mask', 'used_for', 'fabrication process'),(3,1)], [('ScAlN', 'used_for', 'fabrication process'),(2,1)]},
				{sentence2}
					...
				]  
},
{"abstract": abstract2_text,
	"sentences":[{abstract2 sentences1},{abstract2 sentences2}]}
]
```
