.. Example reports documentation master file, created by
   sphinx-quickstart on Fri May  9 14:23:38 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


AITE Overview
========================

Description
...........

.. The AI Technology Evaluation (AITE) provides volunteer testing of AI models on blind data for many tasks, many datasets, many domains, and many modalities. Among the purposes of the AITE are to:
.. The NIST AI Technology Evaluation (AITE), currently in it's initial phase, is the latest in the portfolio of AI evaluations managed by the NIST Information Technology Laboratory. 
.. AITE’s goal is to evaluate AI models on a wide variety of meaningful tasks across diverse datasets, modalities, and domains.
.. Importantly, these evaluations will take place in a sequestered testbed environment, mitigating the risk of train/test data contamination and ensuring rigorous, objective assessment.
The Technology Test and Evaluation Division at the National Institute of Standards and Technology (NIST) has launched a new program to provide researchers with a sequestered testbed environment for the evaluation of AI model performance in a variety of meaningful tasks across diverse datasets, modalities, and domains. 
The Artificial Intelligence Technology Evaluation (AITE), currently in it's initial phase, provides volunteer testing of AI models on blind data and its sequestered environment mitigates the risk of train/test data contamination to ensure rigorous, objective assessment. The infrastructure provided by NIST will provide common data, metrics and scoring to help developers understand the performance of their models.

The purposes of the effort include:

* ▪ serve as a neutral 3rd party for hosting such tests;

* ▪ be able to utilize data that is not publicly released, in order to remove the potential for train/test data contamination and enable the use of data where public distribution is undesired,

* ▪ measure the state of the art.

.. AITE relies on data providers and model providers, and both benefit from AITE participation without having to conduct their own evaluations, which is challenging to do precisely and requires a substantial amount of infrastructure and coordination.
.. Data providers receive careful measurements of top models on their data conducting their task.
.. Model providers are able to see how their model performs on an increasing number of datasets and tasks. Additionally, they learn how other models perform on the same data using the same metrics. This improves comparability while also ensuring data used for evaluation is not part of the training set for any model.

AITE will rely on engagement from participants in two different tracks, each offering distinct advantages:

* ▪ *Data providers* submit an original dataset in their domain that is inaccessible to others and a meaningful task to be performed on that dataset. Data providers will receive careful measurements of top models on their data conducting their task.

* ▪ *Model providers* submit AI models to be tested on the datasets and tasks. Model providers will learn how their models perform on an increasing number of datasets and tasks, and how their models perform relative to others on the same data using the same metrics, improving comparability while ensuring the evaluation data is not used for training any model.

Participation is open to all who wish to engage in one of the ways described above, and who can abide by the AITE Participation Agreement and rules. To request participation or ask questions, contact us at aite-poc@list.nist.gov.
Results for all submitted systems are posted on the AITE website along with the identification of the submitting organizations. NIST summary reports containing general analysis are updated no less than once a year.

Currently, AITE consists of tasks for three use cases (1) Quantum Dot Control; (2) Human Genome Variant Curation; (3) Public Safety Visual Event Recognition.

Over time, AITE will build out multiple tasks under various themes (Quantum, Video, Natural Language Processing, …). Each task will have normal evaluation specification documents and submission protocols, and submissions will be scored and posted.

.. Participation is voluntary and open to all who wish to participate and can abide by the NIST AITE evaluation participation agreement. 

Available Tests
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. div:: lead

   Tests of various tasks, using various datasets, in various domains, and including various modalities.

.. This is a temporary placeholder to show an alternative to the tabbed layout
.. .. seealso::
..    :class: margin

   See this `alternate layout <as_long_page>`_ without the tabs

.. tab-set::

   .. tab-item:: Quantum Dot Control
      :class-content: d-print-block

      .. include:: domains/quantum_dots.rst

   .. tab-item:: Human Genome Variant Curation
      :class-content: d-print-block

      .. include:: domains/human_genome.rst

   .. tab-item:: Public Safety Visual Event Recognition
      :class-content: d-print-block

      .. include:: domains/public_safety.rst


Models
......

The following table lists the example model(s).

.. csv-table:: Details of participating organizations and models
   :file: _static/data/models_table_with_ref.csv
   :header-rows: 1
   :class: datatable


.. toctree::
   :caption: Results
   :maxdepth: 2
   :titlesonly:
   :hidden:

   ai_component_results
   .. ai_application_results



.. toctree::
   :caption: References
   :maxdepth: 2
   :titlesonly:
   :hidden:

   model_reference
   .. model_reference

.. glossary would go here if needed