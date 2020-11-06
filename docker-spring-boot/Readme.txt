To build Campaign Manager code, just run:
mvn clean install

To build SMP code, just run:
mvn clean install -P smp

to build the Service Portal, just run:
mvn clean install -P ui

Notes:
    - The SMPEar is being in SMP built right now, customizations are done to Workflow Engine war file
    - the UI build has been separated into its own build so that just building the UI does not require the rest of the build.
