# MINT-ProvenanceQueries
A repository for storing the provenance queries in MINT.

Current endpoint for testing: http://disk.isi.edu:3030/ds/query

GRLC REST API: http://ontosoft.isi.edu:8001/api/KnowledgeCaptureAndDiscovery/MINT-ProvenanceQueries

Queries to be specified below

Retrieve executions of a given template (URI of the template should be urlencoded): 

http://ontosoft.isi.edu:8001/api/KnowledgeCaptureAndDiscovery/MINT-ProvenanceQueries/getExecution?templ=http%3A%2F%2Fwww.opmw.org%2Fexport%2Fomics%2Fresource%2FWorkflowTemplate%2FPEPTIDE_SEARCH-D751713988987E9331980363E24189CE

# Queries that are part of the API:

* GetTemplates: gets all published templates and their names
* GetExecutions: gets all existing executions and whether they are successful or not
* GetExecutions<iri:Template>: gets all executions for a template
* GetResourceMetadata<iri:Resource>: gets all metadata for a resource
* GetInputs<iri:Execution>: gets all inputs and parameters of an execution 
* GetResults<iri:Execution>: gets all results of an execution
* GetActivities<iri:Execution>: gets all the activities and codes of an execution.
