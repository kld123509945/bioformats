.. index:: Micro-Manager
.. index:: .tif, .txt, .xml

Micro-Manager
===============================================================================

Extensions: .tif, .txt, .xml

Developer: `Vale Lab <https://valelab.ucsf.edu/>`_


**Support**


BSD-licensed: |yes|

Export: |no|

Officially Supported Versions: Up to 1.4.22

Reader: MicromanagerReader (:bsd-reader:`Source Code <MicromanagerReader.java>`, :doc:`Supported Metadata Fields </metadata/MicromanagerReader>`)


Freely Available Software:

- `Micro-Manager <https://micro-manager.org/>`_


We currently have:

* many Micro-manager datasets
* `public sample images <http://downloads.openmicroscopy.org/images/Micro-Manager/>`__

We would like to have:


**Ratings**


Pixels: |Outstanding|

Metadata: |Outstanding|

Openness: |Outstanding|

Presence: |Fair|

Utility: |Good|

**Additional Information**


- Bio-Formats will recognize a :file:`*metadata.txt` file as part of a
  Micro-Manager fileset if pointed at it and will load the fileset including
  the companion TIFF files.
- If pointed at a companion :file:`.ome.tif` file, Bio-Formats will recognize
  an OME-TIFF format instead. This means it may load the fileset if there are
  multiple .ome.tif but it will not include :file:`*metadata.txt` in this
  fileset and therefore the extended Micro-Manager metadata will be skipped.
- See :doc:`/users/micromanager/index` for more information.
