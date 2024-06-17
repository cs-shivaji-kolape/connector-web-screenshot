## About the connector
Web Screenshot provides a service to take screenshot or thumbnail of any online web page in a couple of second.
<p>This document provides information about the Web Screenshot Connector, which facilitates automated interactions, with a Web Screenshot server using FortiSOAR&trade; playbooks. Add the Web Screenshot Connector as a step in FortiSOAR&trade; playbooks and perform automated operations with Web Screenshot.</p>

### Version information

Connector Version: 1.0.0

Authored By: Fortinet SE

Contributors: Semseddin Aksoy

Certified: No
## Installing the connector
<p>Use the <strong>Content Hub</strong> to install the connector. For the detailed procedure to install a connector, click <a href="https://docs.fortinet.com/document/fortisoar/0.0.0/installing-a-connector/1/installing-a-connector" target="_top">here</a>.</p><p>You can also use the <code>yum</code> command as a root user to install the connector:</p>
<pre>yum install cyops-connector-web-screenshot</pre>

## Prerequisites to configuring the connector
- You must have the credentials of Web Screenshot server to which you will connect and perform automated operations.
- The FortiSOAR&trade; server should have outbound connectivity to port 443 on the Web Screenshot server.

## Minimum Permissions Required
- Not applicable

## Configuring the connector
For the procedure to configure a connector, click [here](https://docs.fortinet.com/document/fortisoar/0.0.0/configuring-a-connector/1/configuring-a-connector)
### Configuration parameters
<p>In FortiSOAR&trade;, on the Connectors page, click the <strong>Web Screenshot</strong> connector row (if you are in the <strong>Grid</strong> view on the Connectors page) and in the <strong>Configurations</strong> tab enter the required configuration details:</p>
<table border=1><thead><tr><th>Parameter</th><th>Description</th></tr></thead><tbody><tr><td>Path</td><td>The Chrome binary path refers to the specific location on a computer's file system where the executable file for the Google Chrome web browser is stored</td>
</tr><tr><td>Width</td><td>Specify a horizontal dimension of the viewport or window in which a web page is displayed within a web browser.</td>
</tr><tr><td>Height</td><td>Specify a vertical dimension of the viewport or window in which a web page is displayed within a web browser.</td>
</tr><tr><td>Thumbnail Width</td><td>Specify the horizontal measurement of a small image or preview of a larger images</td>
</tr><tr><td>Thumbnail Height</td><td>Specify a vertical measurement of a small image or preview of a larger images</td>
</tr></tbody></table>

## Actions supported by the connector
The following automated operations can be included in playbooks and you can also use the annotations to access operations:
<table border=1><thead><tr><th>Function</th><th>Description</th><th>Annotation and Category</th></tr></thead><tbody><tr><td>Take Screenshot</td><td>Take a screenshot of a provided URL or web page</td><td>take_screenshot <br/>Investigation</td></tr>
</tbody></table>

### operation: Take Screenshot
#### Input parameters
<table border=1><thead><tr><th>Parameter</th><th>Description</th></tr></thead><tbody><tr><td>URL</td><td>Specify the URL of the web page you want to take a screenshot of.
</td></tr></tbody></table>

#### Output
The output contains the following populated JSON schema:

<pre>{
    "@content": "",
    "@id": "",
    "@type": "",
    "name": "",
    "description": "",
    "file": {}
}</pre>
