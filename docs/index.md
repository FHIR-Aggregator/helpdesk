---
title: ReSearch made simple
template: home.html
hide:
  - navigation
  - toc
---


<div class="grid" markdown>

<div>
<h2 style="background-color:rgb(109, 172, 157, .5)"> FHIR-Aggregator: Your Catalog of Research Data</h2>
Use the FHIR Aggregator server to search patient phenotypes across multiple biomedical resources and download their files.  

The FHIR Aggregator server acts as a centralized repository for diverse healthcare data, organized using the FHIR (Fast Healthcare Interoperability Resources) standard. It provides researchers access to a wide range of information, including:

<ul>
  <li>Clinical data: Patient demographics, conditions, medications, observations, and procedures.</li>
  <li>Research studies: Information about research projects, participants, and study protocols.</li>
  <li>OMICS data associated with Specimens</li>
  <li>Learn more about the data sets we aggregate <a href="/about_us/ourdata">
     here</a> </li>
</ul>
</div>


<div>
<div>

<h2 style="background-color:rgb(109, 172, 157, .5)">fhir-query: Your FHIR Querying Assistant</h2>

Our command-line tool fhir-query (aka fq) is designed to simplify the process of interacting with FHIR servers. It provides researchers with a convenient way to:

<ul>
  <li> Retrieve the vocabulary of a FHIR server: With the vocabulary command, fq fetches and summarizes the key data elements (CodeableConcepts and Extensions) used within the FHIR data. This creates a central vocabulary Dataframe that helps researchers identify important data elements and their usage within the server.</li>
  <li>Execute queries to retrieve FHIR resources: Researchers can then use fq to execute FHIR queries using a readable syntax. This helps to retrieve and filter data from the FHIR Server based on various search parameters and criteria.</li>
</ul>
</div>



</div>


<div class="grid cards" markdown>
-   :material-clock-fast:{ .lg .middle } __Low code, no install__

    ---

    Fill in the blanks in our pre-built queries to find the data you need without installing a thing. Find the data you need, fetch all the files, and answer your scientific questions *all without ever touching the command line.*
    <a
      href="https://colab.research.google.com/github/FHIR-Aggregator/helpdesk/tree/main/docs/Welcome.ipynb"
      title="Try it now"
      class="md-button md-button">
        Launch FHIR-Aggregator in the cloud
    </a>

-   :fontawesome-brands-python:{ .lg .middle } __Use our query tool__

    ---

    Install `fhir-query`, our tool for easily searching FHIR databases,
    with `pip` and direct it to the fhir aggregator server to get up and running in no time

    ```bash
    pip install fhir-aggregator-client
    ```

    ```python

    %env FHIR_BASE=https://google-fhir.fhir-aggregator.org

    ```

-   :octicons-code-square-24:{ .lg .middle } __Already know FHIR?__

    ---

    Direct your command line to the 
    fhir aggregator server and query using your favorite file transfer tool
    
    ```bash

    FHIR_BASE=https://google-fhir.fhir-aggregator.org

    ```
</div>
