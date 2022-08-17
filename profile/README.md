# Automatic Controls Equipment Systems, Inc.

WebCTRL is a trademark of Automated Logic Corporation.  Any other trademarks mentioned herein are the property of their respective owners.

## About

Founded in 1978 by Robert Vogt Sr., [Automatic Controls](https://automaticcontrols.net/) is a second-generation family business that started by providing support and installation of pneumatic controls. As building technology changed, we evolved our focus to DDC controls systems. And in 1990, we became the Automated Logic Dealer for Eastern Missouri and are thrilled to be continuing our partnership moving forward. We serve the eastern half of Missouri including the greater St. Louis area, Columbia, Ste. Genevieve, Cape Girardeau, and Jefferson City.

We control and optimize energy consumption in commercial properties, such as schools, universities, hospitals, data centers, and office buildings. Our innovative, user friendly automation system combined with our industry leading customer service has served to sustain our reputation as a leader in the industry.

As an independent dealer, Automatic Controls is backed by Automated Logic’s industry-leading technology, while providing you with local, on the ground service.

WebCTRL is the software used to interface with building automation systems we provide. Most of the repositories in this organization contain source code for add-ons to extend WebCTRL's functionality. Another software package, EIKON, is used to build logic which is downloaded directly into building controllers. EIKON has a scripting API which is leveraged in a couple of our repositories. Another few of our repositories contain batch files utilized for various purposes.

## Repository Index

### Status Indicators

- ✔ Development Completed
- 🛠 Currently Under Development
- 🔥 Development Expected Soon
- ❄ Development Paused

### [aces-equipment-builder](https://github.com/automatic-controls/aces-equipment-builder)
Desktop application that interfaces with WebCTRL to generate EIKON scripts using custom *.logicsymbol* libraries. Each library can be set to synchronize with a shared network drive. Additional capabilities include maintaining a shared set of favorite *.logicsymbol* and *.logic-script* files.

✔ v2.0.4

### [vscode-aces-equipment-builder](https://github.com/automatic-controls/vscode-aces-equipment-builder)
Extension for [Visual Studio Code](https://code.visualstudio.com/) that provides language support for ACES EB configuration files.

✔ v1.0.2

### [addon-dev-script](https://github.com/automatic-controls/addon-dev-script)
Batch script used to automate certain aspects of WebCTRL add-on development. Features include automated keystore management and dependency collection.

✔ v1.1.0

### [commissioning-scripts](https://github.com/automatic-controls/commissioning-scripts)
WebCTRL add-on which executes scripts uploaded by administrators for the purpose of testing equipment functionality.

🛠 v0.1.0-beta

### [terminal-unit-script](https://github.com/automatic-controls/terminal-unit-script)
Commissioning script which evaluates performance of fans, dampers, and heating components in terminal units.

🛠 v0.1.0-beta

### [geo-xml-export-addon](https://github.com/automatic-controls/geo-xml-export-addon)
WebCTRL add-on that exports structural geographic tree data as an XML file intended for use in Inkscape to create SVG graphics. An optional regular expression transform can be used to preprocess display names for Inkscape label-text.

✔ v1.0.0

### [report-ftp-addon](https://github.com/automatic-controls/report-ftp-addon)
WebCTRL add-on that can be configured to send scheduled reports to a remote server using the FTP, FTPS, or SFTP protocols.

✔ v0.1.1-beta

### [centralizer-for-webctrl](https://github.com/automatic-controls/centralizer-for-webctrl)
Database application that runs as a Windows service and a WebCTRL add-on that communicates with the database. Synchronizes operator credentials and/or files across all connected WebCTRL servers. Additional capabilities include automatic file retrieval and scheduled script execution.

❄ v0.1.0-beta

### [cert-manager-for-webctrl](https://github.com/automatic-controls/cert-manager-for-webctrl)
Batch script which provides commands to assist with the management of SSL certificates for WebCTRL.

✔ v1.0.0

### pid-tuner-addon
WebCTRL add-on that evaluates PID performance and auto-tunes parameters. PID evaluation can be scheduled to recur at regular intervals. When performance ratings drop below acceptable standards, parameters may be auto-tuned.

❄

### graphics-provider-addon
WebCTRL add-on that dynamically generates graphics pages using HTML template files with extended syntax to query and modify nodes on the geographic tree.

❄
