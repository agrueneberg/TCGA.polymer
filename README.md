TCGA.polymer
============

This playground demonstrates the use of [Polymer](http://www.polymer-project.org) to create two Web Components: a patient dashboard and an RPPA browser. Both components are working together: selecting a patient in the patient dashboard will filter for antibody expressions in the RPPA browser.

You can use the Web Components on their own or in different contexts (without the worry of overwriting global variables and such) by loading the Polymer polyfill, importing the custom elements, and adding an HTML tag such as `<patient-dashboard />`.

Note: Not all patients appear in the RPPA data, i.e. some selections won't do anything. Try `TCGA-02-0003`, `TCGA-02-0004`, or `TCGA-02-0011` to get an idea of what this tool is doing.
