Vaadin QuickTickets Dashboard Demo
==================================

## Psst... Shortcut

### For IntelliJ IDEA
* Clone or fork the repository
* Open the project with intelliJ IDEA and let it do its magic
* Make sure that it has generated a file called ``` quicktickets-dashboard.iml ``` in the root of the project folder.
* [![Get Vaadin Charts 4.0 Licence here](https://vaadin.com/directory#!addon/vaadin-charts)
* Take note of the licence since it will be used for the WigetSets too
* Once intelliJ IDEA has finished downloading the maven dependencies and indexing files, move over to the ``` Edit Run Configurations ``` window. its under ``` Run>Edit Configurations ``` in the toolbar menu
* Click on the + (Add new configuration) and choose Maven.
* Give a name for the new Run Config (Optional)
* In the textbox labeled ``` Command Line ``` paste this in ``` -Dvaadin.charts.developer.license=3f500731-xxxx-0000-1111-a8630e89436c -Pproduction-mode jetty:run ```
* Ps. replace the licence variable with your own
* Save the configurations and run from the ``` Run ``` button in intelliJ IDEA
## Resume...

Responsive application demo/template built using only server-side Java with [Vaadin Framework](https://vaadin.com/framework). Showcasing big data, data visualization, drag 'n' drop and other Vaadin features.

[![View the application](https://vaadin.com/documents/10187/2487938/Dashboard+Demo+2014/a37b2c4d-c941-48fe-97c3-ad5a60586882?t=1412769929183)](http://demo.vaadin.com/dashboard)

Running the App
==
Run 'mvn -Pproduction-mode jetty:run' to run in a local jetty. Open in localhost:8080

Run the Maven 'install' target and deploy the resulting WAR file to your Java application server.

You need a license for Vaadin Charts to compile the widgetset. You can get a free 30 day trial license by going to https://vaadin.com/directory#addon/vaadin-charts and clicking the orange "Free trial key" button. It gives you a trial key. [See the help section](https://vaadin.com/directory/help/installing-cval-license) which shows you how to install the key.

Basically you need to create a file name ".vaadin.charts.developer.license" in your HOME directory, and place the key there.

Run 'mvn -Pproduction-mode verify' to run the Vaadin TestBench tests. 

*Note*: You need a valid [Vaadin TestBench license](https://vaadin.com/add-ons/testbench) and [Firefox browser](https://www.mozilla.org/firefox/) installed to run the tests.

Licenses
==
The source code is released under Apache 2.0.

The application uses the [Vaadin Charts](https://vaadin.com/charts) add-on, which is released under the Commercial Vaadin Addon License: https://vaadin.com/license/cval-3