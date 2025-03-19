---
title:  ReSearch made simple

---



<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Low code, no install__

    ---

    Use our pre-built queries to find the data you need without installing a thing. Simply replace the search terms with your term of interest and hit the 'play' button to run a query and answer your scientific questions *all without ever touching the command line.*<p>
<a href="https://colab.research.google.com/github/FHIR-Aggregator/helpdesk/tree/main/docs/Welcome.ipynb" title="Try it now" class="md-button md-button">Launch FHIR-Aggregator in the cloud
</a></p>

-   :fontawesome-brands-python:{ .lg .middle } __Use our query tool__

    ---

    Install `fhir-query`, our tool for easily searching FHIR databases,
    with `pip` and direct it to the fhir aggregator server to get up and running in no time

    ```bash title="in bash"
    pip install fhir-aggregator-client
    ```

    ```py title="in python notebook"

    %env FHIR_BASE=https://google-fhir.fhir-aggregator.org

    !fq --help

    ```



-   :octicons-code-square-24:{ .lg .middle } __Already know FHIR?__

    ---

    Direct your command line to the 
    fhir aggregator server and query using your favorite file transfer tool

    ```bash title="in bash"
    pip install fhir-aggregator-client

    %env FHIR_BASE=https://google-fhir.fhir-aggregator.org

    ```

</div>

