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

### ✔ [aces-equipment-builder](https://github.com/automatic-controls/aces-equipment-builder) v2.0.4
Desktop application that interfaces with WebCTRL to generate EIKON scripts using custom *.logicsymbol* libraries. Each library can be set to synchronize with a shared network drive. Additional capabilities include maintaining a shared set of favorite *.logicsymbol* and *.logic-script* files.

### ✔ [vscode-aces-equipment-builder](https://github.com/automatic-controls/vscode-aces-equipment-builder) v1.0.2
Extension for [Visual Studio Code](https://code.visualstudio.com/) that provides language support for ACES EB configuration files.

### 🛠 [postgresql-connect](https://github.com/automatic-controls/postgresql-connect) v0.3.2-beta
WebCTRL add-on which periodically synchronizes operators, add-ons, and other data to an external PostgreSQL database.

### ✔ [addon-dev-script](https://github.com/automatic-controls/addon-dev-script) v1.1.3
Batch script used to automate certain aspects of WebCTRL add-on development. Features include automated keystore management and dependency collection.

### ✔ [addon-dev-refresh](https://github.com/automatic-controls/addon-dev-refresh) v1.0.1
Streamlines add-on development by automatically removing and adding add-ons from a local WebCTRL server as they are developed.

### ✔ [commissioning-scripts](https://github.com/automatic-controls/commissioning-scripts) v0.1.4-beta
WebCTRL add-on which executes scripts uploaded by administrators for the purpose of testing equipment functionality.

### ✔ [terminal-unit-script](https://github.com/automatic-controls/terminal-unit-script) v0.2.3-beta
Commissioning script which evaluates performance of fans, dampers, and heating/cooling components in terminal units.

### ✔ [geo-xml-export-addon](https://github.com/automatic-controls/geo-xml-export-addon) v1.0.0
WebCTRL add-on that exports structural geographic tree data as an XML file intended for use in Inkscape to create SVG graphics. An optional regular expression transform can be used to preprocess display names for Inkscape label-text.

### ✔ [report-ftp-addon](https://github.com/automatic-controls/report-ftp-addon) v0.1.1-beta
WebCTRL add-on that can be configured to send scheduled reports to a remote server using the FTP, FTPS, or SFTP protocols.

### ✔ [time-sync-addon](https://github.com/automatic-controls/time-sync-addon) v1.0.0
WebCTRL add-on which synchronizes time across controllers at regularly scheduled intervals (configured with [Cron expressions](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/scheduling/support/CronExpression.html#parse-java.lang.String-)).

### ✔ [garbage-collect-addon](https://github.com/automatic-controls/garbage-collect-addon) v1.0.0
A simple WebCTRL add-on which invokes System.gc() every 5 minutes.

### ✔ [cert-manager-for-webctrl](https://github.com/automatic-controls/cert-manager-for-webctrl) v1.0.0
Batch script which provides commands to assist with the management of SSL certificates for WebCTRL.

### ❄ pid-tuner-addon
WebCTRL add-on that evaluates PID performance and auto-tunes parameters. PID evaluation can be scheduled to recur at regular intervals. When performance ratings drop below acceptable standards, parameters may be auto-tuned.

### ❄ graphics-provider-addon
WebCTRL add-on that dynamically generates graphics pages using HTML template files with extended syntax to query and modify nodes on the geographic tree.
