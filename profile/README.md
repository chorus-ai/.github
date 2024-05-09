<a name="readme-top"></a>

# CHoRUS for Equitable AI
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Patient-Focused Collaborative Hospital Repository Uniting Standards (CHoRUS) for Equitable AI

## Table of Contents

- [About](#about)
- [Get Started](#get-started)
  - [Data Site Managers](#data-site-managers)
  - [Clinical Collaborators](#clinical-collaborators)
  - [Project Managers](#project-managers)
  - [Software Developers](#software-developers)
  - [Community Users](#community-users)
- [License](#license)
- [Contact](#contact)


## About
The goal of the CHoRUS Network is to develop the most diverse, high-resolution, ethically sourced, AI-ready data set to answer the grand challenge of improving recovery from acute illness.
<br/>
This collaboration spans 20 academic centers, of which 14 will contribute as Data Acquisition centers.
<br/>
Patient-focused efforts will determine the ethical and legal approaches to manage privacy and bias, while accounting for Social Determinants of Health.
<br/>
Unified standards will harmonize multi-modal EHR, waveform, imaging, and text data.
<br/>
A visualization and annotation environment will label data with targets important for prediction.
<br/>
A comprehensive set of approaches will develop the skills and workforce for a next generation of diverse academic and community AI scientists.
<br/>
Federated access will enable sampling methods to ensure a balanced and diverse cohort.
<br/>
Collaborating with Bridge2AI and 3 other data generation projects, the CHoRUS Network will help us cross the Bridge2AI network together.

## Get Started

The CHoRUS GitHub organization houses active repositories that provide:
  1. Software and tooling to interact with and extract insight from clinical data in diverse formats
  2. Validated semantic mappings for connecting clinical data in various source formats to [international standards](https://ohdsi.github.io/CommonDataModel/)
  3. Standard operating protocols (SOPs) to instruct data contributing sites about best practices for curating and delivering interoperable datasets
  4. Project management overviews to help track data delivery statuses and complex task dependencies within CHoRUS

We've defined different groups of anticipated users of this GitHub in the sections below, and direct those users to appropriate locations within the chorus-ai repository space.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Data Site Managers

The starting reference for data managers at data contributing sites is the [Chorus_SOP](https://chorus-ai.github.io/Chorus_SOP/) page. 

Here, you will find an interactive workflow diagram describing the step-by-step process for extracting and contributing clinical data to CHoRUS, with dynamic links to various SOP documents that have undergone an internal validation and review process within the [Chorus_SOP](https://github.com/chorus-ai/Chorus_SOP) repository.

The workflow diagram also includes links to a wealth of recordings and documentation compiled by the various sub-teams (Standards, Data Acquisition, and Tooling) within the CHoRUS DGP.

If you run into any issues in the creation or submission of your data extract, please feel free to post them in the relevant context-specific discussion location:
- [Standards Discussions](https://github.com/chorus-ai/StandardsModule/discussions)
- [Data Acquisition Discussions](https://github.com/chorus-ai/data_acq_SOP/discussions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Clinical Collaborators

Clinical expertise is invaluable to semantic mapping and validation within CHoRUS. We have established a [chorus-mapping](https://github.com/chorus-ai/chorus-mapping) repository with documentation and pooled tabular mappings along with an associated [clinical validation SOP](https://github.com/chorus-ai/Chorus_SOP/blob/review-mappings-clinical-validation/sop-website/docs/OMOP-Mapping/Mappings-Clinical-Validation.mdx) for contributing to mapping efforts.

If you're interested in getting involved in downstream analytics on the mapped and assembled dataset, please feel free to reach out using the [contact details below](#contact)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Project Managers

We've established two different modes of project management within the chorus-ai organization:
1. Task tracking among CHoRUS members and across teams
2. Status tracking of data contributing sites to identify and resolve any blocking issues

#### Task Tracking

We are aggregating issues across various repositories into an [overall task management project](https://github.com/orgs/chorus-ai/projects/16). In this GitHub project, we assign users to tasks, create and track anticipated delivery dates, and highlight dependencies between tasks and users. Several per-repo projects are also active, but we are in the process of phasing those projects out and migrating their contents to this central project space.

#### Status Tracking

We have asked data contributing sites to provide regular status updates with regard to their progress in creating and curating a CHoRUS-specific clinical data extract. Sites can submit updates either using the GitHub interface directly, or by submitting a Google Form (please [reach out](#contact) to get a link to the form if you'd like to submit an update for your site). We've created a [GoogleScript](https://github.com/chorus-ai/StandardsModule/blob/main/googleformintegration.gs) that is triggered on each Google Form submission and makes calls to the GitHub API to update status and issue information appropriately. These site statuses end up in either the [Standards Project](https://github.com/orgs/chorus-ai/projects/11) or the [Data Acquisition Project](https://github.com/orgs/chorus-ai/projects/7).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Software Developers

We have software contributors within CHoRUS who have a broad range of expertise, and who have produced powerful open-source tooling for transforming and interacting with clinical data. We have created a [web guide](https://chorus-ai.github.io/chorus-developer/) for both contributors and users of the CHoRUS software packages that compiles documentation in the [chorus-developer](https://github.com/chorus-ai/chorus-developer) repository.

You can check the versions, maintainers, and other metadata about CHoRUS packages using our [package status page](https://chorus-ai.github.io/chorus-developer/packageStatuses.html).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Community Users

Welcome! Feel free to browse any of the resources listed above, or check out our [public-facing webpage](https://bridge2ai.org/chorus/) for more information about the project, its progress, and high-level aims.

Thanks for stopping by!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for more details.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Contact

For any inquiries or feedback, please feel free to reach out to us:

- Request access: [dbold@emory.edu](mailto:delgersuren.bold@emory.edu) or [jared.houghtaling@tuftsmedicine.org](mailto:jared.houghtaling@tuftsmedicine.org)
- Website: [www.bridge2ai.org/chorus](https://bridge2ai.org/chorus/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

