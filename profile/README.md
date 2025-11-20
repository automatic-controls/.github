# Automatic Controls Equipment Systems

WebCTRL is a trademark of Automated Logic Corporation.  Any other trademarks mentioned herein are the property of their respective owners.

## About

Founded in 1978 by Robert Vogt Sr., [Automatic Controls](https://automaticcontrols.net/) is a second-generation family business that started by providing support and installation of pneumatic controls. As building technology changed, we evolved our focus to DDC controls systems. And in 1990, we became the Automated Logic Dealer for Eastern Missouri and are thrilled to be continuing our partnership moving forward. We serve the eastern half of Missouri including the greater St. Louis area, Columbia, Ste. Genevieve, Cape Girardeau, and Jefferson City.

We control and optimize energy consumption in commercial properties, such as schools, universities, hospitals, data centers, and office buildings. Our innovative, user friendly automation system combined with our industry leading customer service has served to sustain our reputation as a leader in the industry.

As an independent dealer, Automatic Controls is backed by Automated Logic’s industry-leading technology, while providing you with local, on the ground service.

WebCTRL is the software used to interface with building automation systems we provide. Most of the repositories in this organization contain source code for add-ons to extend WebCTRL's functionality. Another software package, EIKON, is used to build logic which is downloaded directly into building controllers. EIKON has a scripting API which is leveraged in a couple of our repositories. Another few of our repositories contain batch files utilized for various purposes.

## Repository Index

### [aces-equipment-builder](https://github.com/automatic-controls/aces-equipment-builder)
Desktop application that interfaces with WebCTRL to generate EIKON scripts using custom *.logicsymbol* libraries. Each library can be set to synchronize with a shared network drive. Additional capabilities include maintaining a shared set of favorite *.logicsymbol* and *.logic-script* files.

### [vscode-aces-equipment-builder](https://github.com/automatic-controls/vscode-aces-equipment-builder)
Extension for [Visual Studio Code](https://code.visualstudio.com/) that provides language support for ACES EB configuration files.

### [postgresql-connect](https://github.com/automatic-controls/postgresql-connect)
WebCTRL add-on which periodically synchronizes operators, add-ons, and other data to an external PostgreSQL database.

### [addon-dev-script](https://github.com/automatic-controls/addon-dev-script)
Batch script used to automate certain aspects of WebCTRL add-on development. Features include automated keystore management and dependency collection.

### [addon-dev-refresh](https://github.com/automatic-controls/addon-dev-refresh)
Streamlines add-on development by automatically removing and adding add-ons from a local WebCTRL server as they are developed.

### [geo-xml-export-addon](https://github.com/automatic-controls/geo-xml-export-addon)
WebCTRL add-on that exports structural geographic tree data as an XML file intended for use in Inkscape to create SVG graphics. An optional regular expression transform can be used to preprocess display names for Inkscape label-text.

### [mfa-addon](https://github.com/automatic-controls/mfa-addon)
WebCTRL add-on that emails one-time MFA security codes to users upon login. Alternatively, an authenticator app can be configured.

### [cli-addon](https://github.com/automatic-controls/cli-addon)
WebCTRL add-on that provides a web interface to access the server's shell (command prompt or bash).

### [rest-api-addon](https://github.com/automatic-controls/rest-api-addon)
WebCTRL add-on that exposes a REST API with a variety of endpoints.

### [scheduled-download-addon](https://github.com/automatic-controls/scheduled-download-addon)
WebCTRL add-on that adds a new manual command to schedule device downloads for a later time.

### [lock-history-addon](https://github.com/automatic-controls/lock-history-addon)
WebCTRL add-on that can be used to analyze locked point history parsed from the auditlog.

### [wireshark-addon](https://github.com/automatic-controls/wireshark-addon/)
WebCTRL add-on that monitors and analyzes traffic on BACnet/IP networks.

### [report-ftp-addon](https://github.com/automatic-controls/report-ftp-addon)
WebCTRL add-on that can be configured to send scheduled reports to a remote server using the FTP, FTPS, or SFTP protocols.

### [bbmd-manager](https://github.com/automatic-controls/bbmd-manager)
WebCTRL add-on that assists with management of manual BBMDs.

### [trend-service-monitor](https://github.com/automatic-controls/trend-service-monitor)
WebCTRL add-on that monitors the queue size of the TrendHistorianService over time.

### [time-sync-addon](https://github.com/automatic-controls/time-sync-addon)
WebCTRL add-on which synchronizes time across controllers at regularly scheduled intervals (configured with [Cron expressions](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/scheduling/support/CronExpression.html#parse-java.lang.String-)).

### [garbage-collect-addon](https://github.com/automatic-controls/garbage-collect-addon)
A simple WebCTRL add-on which invokes System.gc() every 5 minutes.

### [cookie-addon](https://github.com/automatic-controls/cookie-addon)
WebCTRL add-on that allows scripts to bypass a limitation of headless chrome so that certain login cookies may be specified in query string parameters.

### [commissioning-scripts](https://github.com/automatic-controls/commissioning-scripts)
WebCTRL add-on which executes scripts uploaded by administrators for the purpose of testing equipment functionality.

### [terminal-unit-script](https://github.com/automatic-controls/terminal-unit-script)
Commissioning script which evaluates performance of fans, dampers, and heating/cooling components in terminal units.

### [cert-manager-for-webctrl](https://github.com/automatic-controls/cert-manager-for-webctrl)
Batch script which provides commands to assist with the management of SSL certificates for WebCTRL.
