# OnPrem
The client in the hospital

## Premise

OffPrem is a part of a larger project called Premise. This project will bring open and private research into the healthcare industry. Starting with research on COVID-19. Open refers to publically available research processes and results; private refers to mathematically guaranteed privacy for individual patients and hospitals.

OffPrem is a cloud-based deployment that manages the research across healthcare providers. It controls the parameters of experiments being run on distributed workers at individual providers. OnPrem is the on-premise deployment of a worker at an individual provider. So, there is one OffPrem deployment in the cloud, and as many OnPrem deployments as there are participating providers.

## Values

### 1. Privacy - of patients

First, do no harm. 

* Only run queries on de-identified data
* Follow principles of differential privacy in your code
* Research must be secure to be private

### 2. Transparency - of research

Second, share knowledge. 

* Do not be transparent if it threatens patient privacy
* Add documentation to your code that explains your intention and expected use

### 3. Accuracy - of research

Third, find truth. 

* Do not go for higher accuracy if it threatens patient privacy or research transparency
* Build your code from state-of-the-art knowledge

## Architecture

We designed an architecture with two main components: OnPrem to be hosted on a dedicated hardware box within each hospital, and OffPrem to be hosted on the cloud to manage research. 

We use diagrams.net to create up-to-date versions of the system architecture. [View it here](https://app.diagrams.net/#G1LZMk2MhV1ZCx0Fs_YksQ0VIhux2FbPjH). Only contributors added to the Medley Health organization are able to edit the document.
