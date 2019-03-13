# MINT-ProvenanceQueries
A repository for storing the provenance queries in MINT.

Current endpoint for testing: http://disk.isi.edu:3030/ds/query
Current endpoint for production: http://ontosoft.isi.edu:3030/provenance/query

GRLC REST API: http://ontosoft.isi.edu:8001/api/mintproject/MINT-ProvenanceQueries

Queries to be specified below

Retrieve executions of a given template (URI of the template should be urlencoded): 

http://ontosoft.isi.edu:8001/api/mintproject/MINT-ProvenanceQueries/getExecution?templ=http%3A%2F%2Fwww.opmw.org%2Fexport%2Fomics%2Fresource%2FWorkflowTemplate%2FPEPTIDE_SEARCH-D751713988987E9331980363E24189CE

# Queries in the API (more to be included when necessary):

* (done)GetAllExecutions: gets all existing executions and whether they are successful or not
* (done)GetAllWorkflowTemplates: gets all published templates and their names
* (done)getExecutionsForTemplate[iri:Template]: gets all executions for a template and their status
* (done)GetResourceMetadata[iri:Resource]: gets all metadata for a resource
* (done)GetExecutionInputs[iri:Execution]: gets all inputs and parameters of an execution 
* (done)GetExecutionResults[iri:Execution]: gets all results of an execution
* (done)GetExecutionActivities[iri:Execution]: gets all the activities of an execution.
* (done)GetTemplateForExecution[iri:Execution]: gets the template that was executed to produce the target execution.
* (done)GetTemplateInputs[iri:Template]: gets all inputs of a template and their metadata.
* (done)GetTemplateOutputs[iri:Template]: gets all outputs of a template and their metadata.
* (done)GetTemplateSteps[iri:Template]: gets all steps of a template and their metadata.
* (done)GetPublisherURI[iri:WorkflowExecutionArtifact]: get the remote/publisher location of a dataset.

