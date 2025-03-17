---
title:  #FHIR-Aggregator - A Catalog of Research Data

---

<div class="center" markdown> <p>Use the FHIR Aggregator to search patient phenotypes across multiple biomedical resources and download their files</p></div>

The FHIR Aggregator acts as a centralized repository for diverse healthcare data, organized using the FHIR (Fast Healthcare Interoperability Resources) standard. It provides researchers access to a wide range of information, including:

* Clinical data: Patient demographics, conditions, medications, observations, and procedures.
* Research studies: Information about research projects, participants, and study protocols.
* OMICS data associated with Specimens



<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Low code, no install__

    ---

    Fill in the blanks in our pre-built queries to find the data you need without installing a thing. Find the data you need, fetch all the files, and answer your scientific questions *all without ever touching the command line.*<p>
<a href="https://colab.research.google.com/github/FHIR-Aggregator/helpdesk/tree/main/docs/Welcome.ipynb" title="Try it now" class="md-button md-button">Launch FHIR-Aggregator in the cloud
</a></p>

-   :fontawesome-brands-python:{ .lg .middle } __Power users__

    ---

    Install `fhir-aggregator` with `pip` and direct it to the 
    fhir aggregator server to get up and running in no time

    ```bash
    pip install fhir-aggregator-client
    ```

    ```python

    %env FHIR_BASE=https://google-fhir.fhir-aggregator.org

    ```


</div>

