#######################################
Vorlagen-Generator für PKI-Bestimmungen
#######################################

Dieses Projekt dient dazu, eine Vorlage für PKI-Bestimmungen gemäß :RFC:`3647` zu generieren.
Das Resultat liegt im `reStructuredText <https://docutils.readthedocs.io/en/sphinx-docs/user/rst/quickstart.html>`__-Format
vor und kann mit `Sphinx <https://www.sphinx-doc.org/>`__ in verschiedene Formate, z. B. HTML, PDF oder Confluence,
gerendert werden.

Anleitung
=========

* Python-Module ``Sphinx`` und ``sphinx-rtd-theme`` in ein Python-venv installieren und ``sphinx-build`` in ``$PATH`` symlinken.
* ``./create-outline`` ausführen.
* ``.gitignore``, ``source/`` und ``Makefile`` in ein neues Git-Repository kopieren
* ``source/**`` an eigene Bedürfnisse anpassen.
* Interne Referenzen können z. B. mit ``:ref:`s_2_3``` gesetzt werden.
* ``make html`` ausführen.
* ``firefox build/html/index.html``

Lizenz
======
`english.txt <english.txt>`__ ist ein Extrakt aus :RFC:`3647#section-6` und sollte somit keinen weiteren
Copyright-Einschränkungen unterliegen.

`deutsch.txt <deutsch.txt>`__ ist eine automatische Übersetzung von ``english.txt`` mit Hilfe von https://deepl.com/ und unterliegt
auch keinen Einschränkungen.

`create-outline <create-outline>`__ steht unter der MIT-Lizenz.

Die übrigen Dateien sind mangels Schöpfungshöhe gemeinfrei.
