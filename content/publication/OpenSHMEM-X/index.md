+++
title = "An Initial Implementation of Libfabric Conduit for OpenSHMEM-X"
date = 2018-08-21T11:30:00
abstract = "As a representative of Partitioned Global Address Space models, OpenSHMEM provides a variety of functionalities including one-sided communication, atomic operations, and collective routines. The communication layer of OpenSHMEM-X plays a crucial role for its functionalities. OFI Libfabric is an open-source network library that supports portable low-latency interfaces from different fabric providers while minimizing the semantic gap across API endpoints. In this paper, we present the design and implementation of OpenSHMEM-X communication conduit using Libfabric. This Libfabric conduit is designed to support a broad range of network providers while achieving  excellent network performance and scalability. We have performed an extensive set of experiments to validate the performance of our implementation, and compared with the Sandia OpenSHMEM implementation. %using the OpenSHMEM micro-benchmarking suite and OSU Micro-Benchmarks 5.4.3. Our results show that the Libfabric conduit improves the communication bandwidth on the socket provider by up to 42% and 10%, compared to an alternative OpenSHMEM implementation for put and get operations, respectively. In addition, our implementation of atomic operations has achieved similar latency to that of the Sandia implementation." 

publication = "OpenSHMEM 2018: Fifth Workshop on OpenSHMEM and Related Technologies"
url_pdf = "https://www.osti.gov/servlets/purl/1468149"
selected = false

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
#   4 = Stream
list_format = 0

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++