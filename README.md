# Ontology

## Ruby version
2.7.4

## How to run
```
git clone https://github.com/mmariyam/ontologyapi.git
cd ontologyapi/ && gem build ontology.gemspec
1. gem install ontology-0.0.0.gem 
2. irb
3. require 'ontology_api'
4. onto = OntologyApi.new
5. onto.request(ontology_id: "efo")
```