This wiki describes the SData protocol.

The introduction contains a subsection on
[terminology](/daisy/sdata/Introduction/186-DSY.html "1.1 Terminology") and another one on
[general principles](/daisy/sdata/Introduction/663-DSY.html "1.2 General Principles") that underpin the design of
SData.

The first four sections give general information about the SData protocol and
answers the following questions:

*   What is the [URL syntax](/daisy/sdata/AnatomyOfAnSDataURL.html "2  Anatomy of an SData URL")?
*   What is the [payload](/daisy/sdata/AnatomyOfAnSDataFeed.html "3 Anatomy of an SData Feed") for SData requests and
response?
*   What is the [metadata](/daisy/sdata/Metadata.html "4  Metadata") format (how does an SData
provider expose the structure of the resources to its consumer)?
*   How is [security](/daisy/sdata/Security.html "5 Security") handled?

The following sections are centered around the operations exposed by an SData
service. They describe how the request should be formed (URL, HTTP headers,
payload) and what the service should respond (HTTP status code, HTTP headers,
payload). These sections cover functional issues such as error handling,
concurrency handling, paging, caching in the contexts where they are relevant.

The following operations are covered:

*   [Query](/daisy/sdata/Queries.html "6  Queries") (returns a collection of resources).
*   [Read](/daisy/sdata/ReadOperation.html "7 Read Operation") (returns a single resource).
*   [Create. ](/daisy/sdata/CreateOperation.html "8 Create Operation")

*   [Update](/daisy/sdata/UpdateOperation.html "9 Update Operation").
*   [Delete](/daisy/sdata/DeleteOperation.html "10 Delete Operation").
*   [Service operation](/daisy/sdata/ServiceOperations.html "11 Service Operations") (request/response that does not
fit into the CRUD model) and [named queries](/daisy/sdata/596-DSY.html "12 Named Queries").
*   [Batch operation](/daisy/sdata/165-DSY.html "13 Batch Operations").

The last section describes the [SData registry](/daisy/sdata/423-DSY.html "14 SData Registry")
that applications can use to discover and register service endpoints.

* * *