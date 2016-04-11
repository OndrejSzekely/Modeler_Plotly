# Usage of Plotly charts in SPSS Modeler
##### Description:

This extention allows you to create good looking offline(no need pass data or library queries through internet) interactive D3.js charts, which are generated by Plotly R library. Generated graphs are fully interactive and can be shown in any web browser. The main advantage of these graphs is that you can plot additinal information, which can not be done with standard SPSS graphs nodes. In addition you can zoom charts and slide them. 

![Stream](https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/grafy.PNG)
---

##### This extension adds three new nodes:
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/bar1.PNG)" width="120">
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/hist1.PNG" width="120">
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/scatter1.PNG" width="120">

Option tab of these nodes is described in documment protocol_en.pdf stored in docs folder. [Documentation][2]

##### Screenshots of outputs: 
![Output1](https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/bar3.PNG)
![Output2](https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/hist3.PNG)
![Output3](https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/scatter3.PNG)

##### Screenshots of Options tabs: 
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/bar4.PNG" width="320">
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/hist4.PNG" width="320">
<img src="https://raw.githubusercontent.com/OndrejSzekely/Modeler_Plotly/master/screenshots/scatter4.PNG" width="320">
---
---
Requirements
----
- IBM SPSS Modeler v17.1 (Modeler 18 might have problems)
- R Essentials for SPSS Modeler’ plugin
- R 3.1.x

---
Installation instructions
----
1. Download the extension: [Download][5]
2. Close SPSS Modeler. Save the .cfe files in the CDB folder of the IBM SPSS Modeler. The default location of the CDB folder on Windows 7 is ”C:\ProgramData\IBM\SPSS\Modeler\17\CDB”. If the ProgramData folder is hidden type the path manually. All needed R packages are downloaded and installed automatically when SPSS stream is launched.
3. Restart IBM SPSS Modeler, the node will now appear in the Output palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.

- [plotly][7]
- [Psych][8]


---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][2] directory
- There is a sample available in the [Example][3] directory


---
License
----

[MIT][1]


Contributors
----

  - Ondrej Szekely ([email](oszekely@cz.ibm.com))

[1]: https://opensource.org/licenses/MIT
[2]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/docs
[3]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/example
[5]: https://github.com/OndrejSzekely/Modeler_Plotly/tree/master/src
[7]: https://plot.ly
[8]: https://cran.r-project.org/web/packages/psych/index.html
