# COnCEPT upper-level Design Ontology (COnDO)
COnDO is an upper-level ontology which is designed aiming to support the designer in various activities of knowledge management during the initial stage of the product design process.

The class Person may represent the end-user of the product as well as designer, customer or any other expert in the design team. The designer may belong to the design team (the class DesignTeam) which is working on the design project (the class DesignProject). The class Product accumulates the information about the product being designed, or in use. The product being designed is associated with the person during its design stage or in use. The class PersonProfile is defined to represent various personal and professional aspects of the person. The designer profile may contain for example the level of expertise, role in the projects, interests, language, and preferred information sources. From the product user point of view, the profile can be used as a way to describe the target end-user of the product being designed. The class Content represents the associated resources (documents, sketches, images, videos, etc.) used or created to facilitate the conceptualization of the product.

The list of concepts currently defined in the COnDO ontologies are not meant to be as exhaustive. The objective of the modelling work was to create the initial easily extendable model of design vocabularies and give it to researchers an developers for further developing and testing with own applications.
The early stage conception process is entirely subjective and fluid, so we believe that the underlying question about how knowledge needs to be structured should be approached from product point of view. Consequently, the COnDO ontology is designed to attain a common vision through the set of ontological concepts, allowing the product to be described from different points of view, based on the understanding of currently used vocabularies and accordingly to propose the structured organisation of the design content. Accordingly, the proposed concepts aim at providing the common vocabularies to support various stakeholders collaborating in the initial stage of product design. The content metadata aligned with the proposed concepts allows the restriction and personalisation of the search spaces such as: search of content based on the application domain of the product, deployed technology, market aspects or semantic properties of the product. The ontology may facilitate the search for related and associated content, for example to search for products/concepts based on the similar property of product/concept being considered, but from a different domain.

Model also enables experimental research to test some theoretical approaches introduced to tackle the complex field of creativity support, such as e.g. (Gero, 2004) 

The COnCEPT COnDO ontology is based on the concepts introduced by Offenbach theory of Product Language (Gross, 1987; Steffen, 2007; Steffen 2009). Moreover, it is extended and initiated with the concepts suggested by end-user partners of the COnCEPT consortium (http://www.concept-fp7.eu/), as well as leveraging the concepts gathered in the literature review (e.g. Mougenot, 2007; Guaenand, 2003).

#Overview of ontology
High level classes of COnDO help to sharing information between products and design teams and associate content to products (see Fig.1). 

Profiles and content metadata can be extended with other conceptual classifications or generic ontologies such as FOAF or those provided by semantic desktops such as Nepomuk. Guidelines for mapping to other ontologies are provided in wiki pages. 

![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/COnDO%20high%20level%20classes.png)

Fig 1: High level classes

Following the conceptual model defined by Gross COnDO makes a distinction between the practical functions of a product on the one hand, and the formal and communicative aspects, the so-called product language functions on the other (see Fig.2). Analogous to the differentiation commonly deployed in a science of language between syntax and semantics the specific object of product language is subdivided into formal aesthetic functions, i.e. those aspects that can be observed irrespective of the meaning of their content – and the semantic functions. Following distinction between sign and symbol, he then proceeded to differentiate between sign functions or indication functions and symbolic functions. 
![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/Gross%20prduct%20language.png)

Fig 2: Gross conceptual model

It is assumed that this overall conceptual model will remain stabile and extensions will be done mainly by extending or specializing the subcategories defined by it. More detailed conceptualizations of subcategories based on this model are partly visualised in the following diagrams (see Fig 3- Fig. 6).

The Product Function related concepts describe more practical aspect of the product such as the purpose it serves (e.g. provide services), the domain of the product under design (e.g. web, fashion, kitchen-ware or consumer electronics), deployment technology, as well as ergonomical, economical, and ecological properties of the product. 
The concepts of Aesthetic functions help to distinguish between order and complexity, and reduction of stimuli versus richness of stimuli using the terms of shapes, colour, texture, material etc. These terms that can be understood as a theory of the design are represented by the Universal Design Principles, and can be brought to the designer on the demand based on the context of the task in hand. The Indication functions (the class IndicationFunction) enable the nature of a product or the product category to be identified. Various characteristics such as brand, material, texture, etc. can help to recognise the product.
The Symbol functions are associated with objects in the imagination of the end-user or designer. The symbol functions refer to conceptions and associations that come to a person’s mind while interacting with object. These can be for example historical, societal, socio-cultural, and technological aspects. They may convey, for example, conceptions of style. 
Finally, the symbolic functions also invoke associations like cold - warm, strong-weak, aggressive, dark, etc. The important term belonging to symbolic functions of the product is also the Trend as a concept. The trend is associated with various conceptions such as for example the style and the technology.   

![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/Product%20functions.png)

Fig 3: Product functions

![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/Aesthetic%20functions.png)

Fig 4: Aesthetic functions

![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/Indication%20functions.png)

Fig 5: Indication functions

![alt tag](https://raw.githubusercontent.com/OntoRep/COnCEPT/master/Symbol%20functions.png)

Fig 6: Symbol functions

#References
Gros, J. Grundlagen einer Theorie der Produktsprache, Symbolfunktionen. (1987) (Ed. Academyof Art and Design Offenbach).Fischer R. and Mikosch G. Grundlagen einer Theorie der Produktsprache, Anzeichenfunktionen ,1984 (Ed. Academy of Art and Design Offenbach).

Steffen, D. (2007). Design semantics of innovation, product language as a reflection on technical innovation and socio-cultural change. In Proceedings of Design Semiotics in Use workshop, held as a part of World Congress in Semiotics "Communication: Understanding/ Misunderstanding, June 6-8, Helsinki, Finland

Steffen, D. (2009). Meaning and narration of product design. International conference on designing pleasurable products and interfaces (DPPI’09), 13-16 Oct., Compiegne, France

Mougenot, C., et al. (2007). Creativity in design - how designers gather information in the preparation phase. In Proceedings of IASDR conference on scientific design research, 2007

Guenand, A. and Zapata, F.C. (2003). A performance aid in creativity and capitalization for designers and semiologists.in 6th Asian International Design Conference. 2003.Tsukuba, Japan

Gero, J.S., and Kannengiesser, U. (2004). The situated function–behaviour– structure framework. Design Studies. Volume 25, Issue 4, July 2004, Pages 373–391



