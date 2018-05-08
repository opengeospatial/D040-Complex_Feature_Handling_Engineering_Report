# Complex Feature Handling in the next generation of OGC web services

[WFS 3.0](https://github.com/opengeospatial/WFS_FES) is a revision of the
[OGC Web Feature Service standard](http://www.opengeospatial.org/standards/wfs) that proposes a modernized service architecture following the current Web architecture, has a focus on the developer experience, supports the [OpenAPI specification](https://www.openapis.org/), and modularizes WFS into building blocks for fine-grained access to spatial data that can be used in data APIs. The current work on WFS 3.0 has focused on simple features and interaction, interrogation and extraction of these.

The contents of this repository is research and is developed as part of the [OGC Testbed 14](http://www.opengeospatial.org/projects/initiatives/testbed14). It addresses the [Complex Feature Handling task](https://portal.opengeospatial.org/files/77327#ComplexFeatures). The task reviews the work on this next generation of OGC web services ("NextGen services") from the perspective of supporting complex 3D data or complex data schemas. The goal is to identify the best service solution for these particular needs, whether the result are WFS 3.0 extensions or other approaches. In this context the approach that the NextGen services are not monolithic web services, but API building blocks, is important. The same API should be able to support requirements that currently require separate OGC web services, e.g. a WFS and a 3DPS server.

The report will eventually propose how to extend the NextGen service architecture with API building blocks for complex data, complex queries and 3D portrayal. WFS 3.0, Part 1, is used as the starting point for the NextGen service architecture. The proposals will be based on existing requirements and use cases.

The files in this repository use the [AsciiDoc template used by the Open Geospatial Consortium for Engineering Reports](https://github.com/opengeospatial/er_template).

# This Repository is public

Although the progress achieved within this repository will result in an Engineering Report that is to be submitted to the Open Geospatial Consortium's Technical Committee for approval, OGC Testbed 14 has agreed to allow the development of this Engineering Report to be open to the public. There are three rules:

* Comments may be provided using [GitHub issues](https://github.com/opengeospatial/D040-Complex_Feature_Handling_Engineering_Report/issues).
* The contributor understands and accepts that all copyright and other intellectual property rights for any contributions incorporated from submitted Issues will be vested to the OGC.
* Issues will be responded to on a best-effort basis, and some might not be responded to at all.

In addition to the issues on GitHub, we have also set up a Gitter chat [![Gitter chat at https://gitter.im/opengeospatial/T14-ComplexFeatureHandling](https://badges.gitter.im/T14-ComplexFeatureHandling.svg)](https://gitter.im/opengeospatial/T14-ComplexFeatureHandling?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge).

# Status

The work on the Engineering Report is just starting. Most of the contents are still the original chapters from the template. Currently only chapter 1 ("Summary") has been updated.
