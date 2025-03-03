Datasets available
------------------
This page gives a description of the datasets available on /disk2/shared_datasets of lsmosrv5.

General Notes
^^^^^^^^^^^^^^
The datasets can have AsIs in their name. This means that the dataset is the exact match of what is available online, and the user should be careful when using it.
The AsIs datasets have not gone through any cleaning or processing.


Summary
^^^^^^^^^^^^^^^^^^

The datasets that are available are:

====================================  ================================  ======  =================  =======================================================================  ===========
Dataset                               Location                          Count   File Type          Relevant link                                                            Availablity
====================================  ================================  ======  =================  =======================================================================  ===========
CSD MOF Collection Original           /disk2/CSD_MOF_Collection_AsIs    14,077   .cif              `CSD <https://www.ccdc.cam.ac.uk/free-products/csd-mof-collection/>`_     Free
CoRE MOF Original                     /disk2/CoRE_MOF_AsIs              10,367  .cif, .csv         `CoRE MOF <https://zenodo.org/records/14184621>`_                         Free 
====================================  ================================  ======  =================  =======================================================================  ===========


Detailed description
^^^^^^^^^^^^^^^^^^^^

1. **CSD MOF Collection Original:**
    - Location: /disk2/CSD_MOF_Collection_AsIs
    - Count: 14,077
    - File Type: .cif
    - Relevant link: `CSD <https://www.ccdc.cam.ac.uk/free-products/csd-mof-collection/>`_
    - Availablity: Free
    - Clone date: 3 March 2025
    
    The CSD MOF collection contains just over 14,000 3D MOF crystal structures available to use for free in academic research.
    The information about curation strategy has not been found yet (add if you know). They mention that the 3D MOF structures with no disorder in the main framework are around 27,000 in the CSD,
    and after curation they have 14,000 structures that are computation ready and have significant void space.
    
    **Naming:** The file names have the CCDC code + "_P1" + either "_H" or "_charged" or "_charged_H" + ".cif" as the extension.
    Example file names: "kivfay_P1_H.cif", "kivlou_P1_charged.cif", "kinrik_P1_charged_H.cif"

2. **CoRE MOF Original:**
    - Location: /disk2/CoRE_MOF_AsIs
    - Count: 10,367 (for more detail visit the link)
    - File Type: .cif, .csv
    - Relevant link: `CoRE MOF <https://zenodo.org/records/14184621>`_
    - Availablity: Free
    - Clone date: 3 March 2025

    The CoRE MOF database is a collection of MOFs where the structures are taken from the CSD and are cleaned and processed. 
    For more information on the cleaning and processing, visit the `Paper <https://pubs.acs.org/doi/10.1021/acs.jced.9b00835>`_ and the `Zenedo Link <https://zenodo.org/records/14184621>`_.
    The database has .csv files where some properties (e.g. topology and Zeo++) of the MOFs are stored.

    **Naming:** The file names are diverse so check the directory to see the naming conventions.
    Usually they have the CCDC code + either "_clean_pacman" or "_freeONLY" or "_clean" or "_manual" + ".cif" as the extension.
    Example file names: "UGUXAV_clean_pacman.cif", "BEPNER_freeONLY.cif", "kinrik_clean.cif", "MEJZUY_clean.cif"