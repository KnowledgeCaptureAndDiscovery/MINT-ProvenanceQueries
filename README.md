# MINT-ProvenanceQueries
A repository for storing the provenance queries in MINT.

Current endpoint for testing: http://disk.isi.edu:3030/ds/query

GRLC REST API: http://ontosoft.isi.edu:8001/api/KnowledgeCaptureAndDiscovery/MINT-ProvenanceQueries

Queries to be specified below

Retrieve executions of a given template (URI of the template should be urlencoded): 

http://ontosoft.isi.edu:8001/api/KnowledgeCaptureAndDiscovery/MINT-ProvenanceQueries/getExecution?templ=http%3A%2F%2Fwww.opmw.org%2Fexport%2Fomics%2Fresource%2FWorkflowTemplate%2FPEPTIDE_SEARCH-D751713988987E9331980363E24189CE

#Queries:

* GetTemplates
* GetExecutions
* GetExecutions<Template>
* GetResourceMetadata
* GetInputs<Execution>
* GetResults<Execution>
* GetActivities<Execution>
