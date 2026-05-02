# Gigaset XML phonebook editor

A lightweight, browser-based interactive editor for phonebook files used by
Gigaset VoIP and DECT phones. The tool allows users to manage contacts in the
Gigaset "XML Version 2" format without needing specialized software.

No server-side processing; all data handling occurs entirely within the local
browser.

Since this is a single-file web application no installation is required:

1.  Download or clone the repository.
2.  Open `index.html` in any modern web browser.
3.  Click **Import XML** to load an existing file (like the provided
    `example.xml`), or start adding contacts from scratch.
4.  Once finished, click **Export XML** to download your updated directory.

Imported and exported files adhere to the [Gigaset local phonebook XML version
2 specification](https://teamwork.gigaset.com/gigawiki/display/GPPPO/Local+Phonebook+-+XML+version+2+format).

<!-- vim: set sw=2 sts=2 et : -->
