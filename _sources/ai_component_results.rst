
============================
AITE Test Results
============================

Quantum Dot Control
~~~~~~~~~~~~~~~~~~~

.. dropdown:: Quantum Dot Control Test v1.0
    :open:

    Charge stability diagrams are two-dimensional measurements that show how the electrical response of a quantum dot changes as voltages applied to control electrodes are varied. Given an image patch of a charge stability diagram, the model must output a three-state probability vector that the image patch displays a double-dot, a single-dot or no dot. The primary metric is `mean squared error <https://en.wikipedia.org/wiki/Mean_squared_error>`_ between output and expert-labeled state vectors.

    .. A report is available as a pdf file: :download:`pdf <https://drive.google.com/file/d/1fx0zHgeIbcItoS6KHQrYn46_whttXuKT/view?usp=sharing>`

    .. csv-table::
             :file: _static/data/results_quantum_dots.csv
             :header: "Model ID", "Date Submitted", "Test Set",  "Mean Squared Error (95% CI)"
             :class: datatable

---------

Human Genome Variant Curation
~~~~~~~~~~~~~~~~~~~~~
.. dropdown:: Human Genome Variant Curation Test v1.0
    :open:

    Given an image of a small region of the genome and text describing a set of variants in this region, the model must determine whether all of the given variants were correctly called. The primary metric is an unweighted linear combination of `Type I and Type II error rates <https://en.wikipedia.org/wiki/Type_I_and_type_II_errors>`_.
    
    
    .. csv-table::
             :file: _static/data/results_human_genome.csv
             :header: "Model ID", "Date Submitted", "Test Set", "Average Error Rate (95% CI)"
             :class: datatable

---------

Public Safety Visual Event Recognition
~~~~~~~~~~~~~~~~~~~~~

.. dropdown:: Public Safety Visual Event Recognition Test v1.0
    :open:

    Given a set of three video key frames, the model must output a yes or no decision whether the key frames provide evidence of a public safety event occurring. The primary metric is a detection cost function, which is a weighted linear combination of `Type I and Type II error rates <https://en.wikipedia.org/wiki/Type_I_and_type_II_errors>`_.

    .. csv-table::
             :file: _static/data/results_public_safety.csv
             :header: "Model ID", "Date Submitted", "Test Set", "Detection Cost Function Value (95% CI)"
             :class: datatable
