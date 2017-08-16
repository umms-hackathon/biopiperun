#bioPipeRun

**1. Project Name:** 
bioPipeRun v1.0.0

**2. Project repository:** 
https://github.com/umms-hackathon/biopiperun.git

**3. Team members:**

**4. Aim:** 
The aim of this project is to create a nextflow runner for generated pipeline.

**5. Project description:**

The pipelines will be generated using bioPipeGen project. Some of the input parameters of a generated pipeline will be asked to the user by a form. Some of the initial parameters can be lookup fields that can be filled as dropdown lists, radio buttons or check boxes in the form. 
Other input parameters will be free text fields.

To be able to run any nextflow, input files that doesn't match with an ouput needs to be in this form to be filled by the user.  

When a workflow starts running, all running workflows needs to be in a list like in the example below.

Example workflow run status page

![Alt text](img/example2.png?raw=true "Workflow Run Status Page")

When a "Status" button clicked. Running process will be shown as active in green color with a runnin animation in the workflow design

An example workflow design.

![Alt text](img/example1.png?raw=true "Example Workflow Design")

