TCGA.polymer
============

This playground demonstrates the use of [Polymer](http://www.polymer-project.org) to create a few [TCGA](http://cancergenome.nih.gov)-related Web Components: a cancer type selector, a patient selector and an RPPA browser. All components are working together: selecting a patient in the patient selector will filter for antibody expressions in the RPPA browser, and selecting a cancer type will change the two other elements.

You can use the Web Components on their own or in different contexts (without the worry of overwriting global variables and such) by loading the Polymer polyfill, importing the custom elements, and adding an HTML tag such as `<tcga-dashboard />`.

Note: Not all patients appear in the RPPA data, i.e. some selections won't do anything. Also, some cancer types do not have associated patient data. Try `TCGA-02-0003`, `TCGA-02-0011`, or `TCGA-02-0014` for `GBM` to get an idea of what this tool is doing.


Getting Started
---------------

Clone the repository, run `bower install`, `npm install`, and finally `grunt`.
