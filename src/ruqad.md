# ![RuQaD Logo](./assets/ruqad_logo.webp) RuQaD Batteries

*Like a rocket, but for batteries*

The **RuQaD** **Batteries** (Reuse Quality-assured Data for Batteries)
project demonstrates the bridging between a research data infrastructure
(POLIS) and an industrial data space (BatCAT) for the efficient reuse of
quality-assured research data from the context of battery production. As
part of the [EU-HORIZON consortium
BatCAT](https://www.nmbu.no/en/research/projects/batcat), a dataspace
based on the FAIR principles for lithium-ion and sodium-ion button cells
and redox-flow batteries is being created. The dataspace is
technologically based onThe **RuQaD** **Batteries** (Reuse Quality-assured Data for Batteries)
project demonstrates the bridging between a research data infrastructure
(POLIS) and an industrial data space (BatCAT) for the efficient reuse of
quality-assured research data from the context of battery production. As
part of the [EU-HORIZON consortium
BatCAT](https://www.nmbu.no/en/research/projects/batcat), a dataspace
based on the FAIR principles for lithium-ion and sodium-ion button cells
and redox-flow batteries is being created. The dataspace is
technologically based on
[LinkAhead](https://docs.indiscale.com/caosdb-deploy/) as a Data and
Knowledge Management System (DKMS) and [Eclipse Dataspace
Components](https://projects.eclipse.org/projects/technology.edc) (EDC)
for the trust-based sharing and exchange of data in the dataspace.
[Kadi4Mat](https://kadi.iam.kit.edu/) is being developed and used as
part of the NFDI consortium NFDI4Ing and the [Post-Lithium Storage
Cluster of Excellence](https://www.postlithiumstorage.org/en/polis)
(POLIS), among others. Data on sodium ion batteries from POLIS is of
particular interest for the R&D activities of the BatCAT consortium. The
enrichment or validation of the data collected as part of BatCAT with
additional data offers an effective advantage for the development and
training of models (keywords: machine learning and artificial
intelligence).

The aim of the demonstrator is to create a link between a research data
infrastructure and a dataspace that promotes the reuse of existing data.
On the one hand, this requires a high degree of automation in order to
be able to process a large number of data sets. On the other hand, a
"human-in-the-loop", i.e. human interaction, is required to allow
additional control to ensure that no data records are introduced into
the dataspace that are not intended for this purpose. For dataspaces to
offer great added value, the data and metadata should be of high
quality. However, this can be a challenge if data is to be reused that
was collected before the dataspace was created, for example. To meet
this challenge, we integrate comprehensive quality checks into the
publication process with our RuQaD demonstrator.

The RuQaD demonstrator reads (meta) data from Kadi4Mat and publishes it
to the data space after a quality check. This workflow is, among other
things, made possible by the [*LinkAhead
Crawler*](https://www.mdpi.com/2306-5729/9/2/24#) data integration and
harmonization tool. This will be used in the demonstrator for processing
the data records and for the connection to LinkAhead. For the quality
check, RuQaD builds on the existing FAIR dataspaces demonstrator 4.2
(Data Quality Assurance and Workflows) and extends it. In addition to
the existing quality checks, the quality checks also include a check as
to whether the metadata complies with the metadata standard defined by
the BatCAT dataspace, or which information is missing, and whether the
FAIR principles are observed. This means that the RuQaD Demonstrator
builds on two essential, already existing components (LinkAhead Crawler,
Demonstrator 4.2) and uses them to enable data reuse between data space
and research data infrastructure in an innovative way.

The implementation of the RuQaD demonstrator aims at two concrete
infrastructures (POLIS & BatCAT). However, the technologies, interfaces
and design used allow the demonstrator to be easily extended to other
use cases (e.g. another Kadi4mat-based research data infrastructure or
another EDC-based data space) that go beyond battery research.
[LinkAhead](https://docs.indiscale.com/caosdb-deploy/) as a Data and
Knowledge Management System (DKMS) and [Eclipse Dataspace
Components](https://projects.eclipse.org/projects/technology.edc) (EDC)
for the trust-based sharing and exchange of data in the dataspace.
[Kadi4Mat](https://kadi.iam.kit.edu/) is being developed and used as
part of the NFDI consortium NFDI4Ing and the [Post-Lithium Storage
Cluster of Excellence](https://www.postlithiumstorage.org/en/polis)
(POLIS), among others. Data on sodium ion batteries from POLIS is of
particular interest for the R&D activities of the BatCAT consortium. The
enrichment or validation of the data collected as part of BatCAT with
additional data offers an effective advantage for the development and
training of models (keywords: machine learning and artificial
intelligence).

The aim of the demonstrator is to create a link between a research data
infrastructure and a dataspace that promotes the reuse of existing data.
On the one hand, this requires a high degree of automation in order to
be able to process a large number of data sets. On the other hand, a
"human-in-the-loop", i.e. human interaction, is required to allow
additional control to ensure that no data records are introduced into
the dataspace that are not intended for this purpose. For dataspaces to
offer great added value, the data and metadata should be of high
quality. However, this can be a challenge if data is to be reused that
was collected before the dataspace was created, for example. To meet
this challenge, we integrate comprehensive quality checks into the
publication process with our RuQaD demonstrator.

The RuQaD demonstrator reads (meta) data from Kadi4Mat and publishes it
to the data space after a quality check. This workflow is, among other
things, made possible by the [*LinkAhead
Crawler*](https://www.mdpi.com/2306-5729/9/2/24#) data integration and
harmonization tool. This will be used in the demonstrator for processing
the data records and for the connection to LinkAhead. For the quality
check, RuQaD builds on the existing FAIR dataspaces demonstrator 4.2
(Data Quality Assurance and Workflows) and extends it. In addition to
the existing quality checks, the quality checks also include a check as
to whether the metadata complies with the metadata standard defined by
the BatCAT dataspace, or which information is missing, and whether the
FAIR principles are observed. This means that the RuQaD Demonstrator
builds on two essential, already existing components (LinkAhead Crawler,
Demonstrator 4.2) and uses them to enable data reuse between data space
and research data infrastructure in an innovative way.

The implementation of the RuQaD demonstrator aims at two concrete
infrastructures (POLIS & BatCAT). However, the technologies, interfaces
and design used allow the demonstrator to be easily extended to other
use cases (e.g. another Kadi4mat-based research data infrastructure or
another EDC-based data space) that go beyond battery research.
