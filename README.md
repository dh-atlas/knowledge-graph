# The ATLAS Knowledge Graph
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14058143.svg)](https://doi.org/10.5281/zenodo.14058143)

The [**ATLAS Ontology**](https://w3id.org/dh-atlas/) has been implemented to describe the metadata of selected pilot projects and their related entities.  
This effort has resulted in a Knowledge Graph, currently available as a [compressed archive](releases/v2.0/knowledge-graph-2.0.zip) containing Turtle (`.ttl`) serializations.

---

## 🆕 Current Version

- **Version:** 2.0  
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

### What's New

The current version of the Knowledge Graph revises the Turtle serializations according to the new properties of the [**ATLAS Ontology v2.0**](https://w3id.org/dh-atlas/2.0).  

Described resources include **54 Research Products** among:
- Digital Scholarly Editions  
- Text Collections  
- Software  
- Ontologies  
- Linked Open Data  
- *New classes:* **Language Model** and **3D Digital Twin**

These are linked to their contextual entities: Research Projects, Organizations, People, Websites, and Computer Programs.

In addition, **this version introduces a set of extraction graphs** — i.e., *named graphs* (`.ttl` files) containing subjects corresponding to the described research products.  
These graphs were produced through **semi-automatic knowledge extraction** directly from the available sources, including **APIs, SPARQL endpoints, static files, websites**, and **textual descriptions**.  
They represent an enrichment of the ATLAS Knowledge Graph with empirically derived connections between resources and metadata.

---

## 📦 Previous Versions

### Version 1.1
- **Version DOI:** [https://doi.org/10.5281/zenodo.15480439](https://doi.org/10.5281/zenodo.15480439)  
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

#### What's New
This version extends the Knowledge Graph with the **Turtle (.ttl) serializations** of the records created during the **Datathon** held as part of the [**ATLAS Workshop (March 26, 2025)**](https://dh-atlas.github.io/workshop.html).  

Data are structured according to the [**ATLAS Ontology v1.0**](https://w3id.org/dh-atlas/1.0).  

Described resources include **37 Research Products** among Digital Scholarly Editions, Text Collections, Software, Ontologies, and Linked Open Data, along with their contextual entities (Research Projects, Organizations, People, Websites, and Computer Programs).

---

### Version 1.0
- **Version DOI:** [https://doi.org/10.5281/zenodo.14058144](https://doi.org/10.5281/zenodo.14058144)  
- **License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

#### What's New
This is the **initial version** of the ATLAS Knowledge Graph, consisting of **Turtle (.ttl) serializations** structured according to the [**ATLAS Ontology v1.0**](https://w3id.org/dh-atlas/1.0).  

Provided data are based on **16 selected pilot Research Products** among Digital Scholarly Editions, Text Collections, Software, Ontologies, and Linked Open Data, together with their contextual entities (Research Projects, Organizations, People, Websites, and Computer Programs).

Additionally, some [demo files](releases/v1.0/knowledge_graph_demo/) have been curated to illustrate the structure of the main entities within this model.
