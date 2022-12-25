# Über diese Site
Dies ist meine Begleitseite für den [openHPI](https://open.hpi.de/) Kurs
[Objektorientierte Programmierung in Java - Schulversion](https://open.hpi.de/courses/javaeinstieg-schule2023) vom 27.02.2023 bis 04.06.2023.

Der gesamte Inhalt dieser Site (HTML und Python Source Code) ist abgelegt in meinem
GitHub Repository
[openhpi_java_schule_2023](https://github.com/maroph/openhpi_javaeinstieg_schule2023/):

## Struktur der Site

* docs
  Markdown Sourcen dieser Site
* sources  
  Java Source Code
* LICENSE  
  Lizenz des Repositories (CC-BY 4.0)
* README.md  
  Readme Datei des Repositories
* mkdocs.yml  
  [MkDocs](https://www.mkdocs.org/) Konfigurationsdatei

## MkDocs Virtual Environment
Für MkDocs verwende ich das folgende Virtual Environment:

    python3 -m venv venv
    source venv/bin/activate
    python -m pip install --upgrade pip
    python -m pip install --upgrade setuptools
    python -m pip install --upgrade wheel
    python -m pip install --upgrade mkdocs
    python -m pip install --upgrade mkdocs-material
    python -m pip install --upgrade mkdocs-git-revision-date-plugin

Sollte das Modul venv nicht installiert sein, muss man das Package python3-venv
installieren.

Auf Debian/Ubuntu/Raspbian geht das mit dem folgenden Kommando

    sudo apt install python3-venv

Liegt die Daten nicht in einem Git Repository, ist die Zeile

    - git-revision-date

aus der Datei _mkdocs.yml_ zu entfernen.


