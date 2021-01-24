## Inspiration
The inspiration for this project started as soon as I started getting into the field of Artificial intelligence and data science, and in the age of deep learning, data becomes an important resource to build smart systems. In several fields, we already see that the amount of data that is required to build competitive systems is easily available for some fields, for example, state-of-the-art large vocabulary speech recognition systems that are available from major players such as Google or Nuance are trained with up to 1 million hours of speech. With such large amounts of data, we are now able to train speech-to-text systems with accuracies of up to 99.7%. This is close to or even exceeds the human performance, given that the system does not need breaks, sleep, or ever gets tired. Similarly There is no doubt that healthcare data can be life savior too, it can revolutionize the healthcare industry as a whole, positively impacting the medical care and assistance provided to the patients. But as we can also see the data in the field of healthcare is very scarce and the medical data problem is far from being solved.

**And hence was born MedicalVault - A completely new, non-intrusive way to collect health data from both patients and health service providers.**


## What it does
MedicalVault, at its core, is a cloud repository for medical and healthcare data associated with certain patients and address the following problems:
1. The platform will act as a repository and will serve patients by giving them a single place to safely store and view all of their health data.
2. The platform will also act as a data acquisition & filtering repository for the big data analytics life cycle and also help researchers for clinical trial analytics (for example we can track all the patients for side effects of certain drug or vaccine (in cases such as COVID-19)).
3. Also, we can start integrating some state of the art Artificial intelligence models to provide inference for medical records that patients have stored on our platform and these AI models can also be improved with the help of this data .
_So, actually the plan is not just to build a platform, the idea is to build an organization for data driven clinical trials, analytics and drug discovery_

## Getting Started

To get a local copy up and running, follow these simple example steps.

### Prerequisites

- django

  ```sh
  pip install django
  ```

- django REST framework
  ```sh
  pip install djangorestframework
  ```
- django CORS header

  ```sh
  pip install django-cors-headers
  ```

- or run requirements file
  ```sh
  pip install -r requirements.txt
  ```
