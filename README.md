# GraphML-for-neo4j
MetaEdit+ generator to export models to Neo4j via GraphML

Generators exports a model made with any domain-specific language from MetaEdit+ to Neo4j. Generators proudce a restricted format of GraphML as Neo4j import does not support all GraphML features such as ports.

.rep files include MERL generators for MetaEdit+ (www.metacase.com) that can be read into Generator Editor (see https://www.metacase.com/support/56/manuals/mwb/Mw-5_3_1.html#Heading1539). These can be imported to your language definition (Graph type) or to the main Graph enabling export to all languages. Genenerators can be freely changed in Generator Editor to detail them fitting to your language (e.g. exclude elements, move some items to edges instead of been nodes, or apply non-directed edges by setting explicty role types of your language etc.).

MetaEdit+ is a language workbench that allows supporting your modeling language. Tool provides functionality for collaborative modeling, versioning, model checking and publishing goal structures, available at: https://www.metacase.com/download.
