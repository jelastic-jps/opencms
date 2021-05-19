[![OpenCms](images/logo_opencms.gif)](../../../opencms)

## OpenCms

The JPS package deploys [OpenCms](http://www.opencms.org/) that initially contains 1 application server and 1 database container. 

### Highlights
This package is designed to deploy OpenCms environment, a professional, easy to use website content management system from Alkacon Software.<br />
OpenCMS helps content managers worldwide to create and maintain beautiful websites fast and efficiently.<br />
It has a fully browser based user interface with configurable editor for structured content with well defined fields. Alternatively, content can be created using an integrated WYSIWYG editor similar to well known office applications. A template engine enforces a site-wide corporate layout and W3C standard compliance for all content.

OpenCms is based on Java and XML technology. It can be deployed in an open source environment (e.g. Linux, Apache, Tomcat, MariaDB) as well as on commercial components (e.g.  Windows NT, IIS, BEA Weblogic, Oracle).

### Environment Topology

![opencms-environment-topology](images/opencms-environment-topology.png)

### Specifics

Layer                |     Server    | Number of CTs <br/> by default | Cloudlets per CT <br/> (reserved/dynamic) | Options
-------------------- | --------------| :----------------------------: | :---------------------------------------: | :-----:
AS                   | Tomcat Java |       1                        |           1 / 32                          | -
DB                   |    MariaDB      |       1                        |           1 / 8                           | -

* AS - Application server 
* DB - Database 
* CT - Container

**OpenCms Version**: 11.0.2<br/>
**Tomcat Version**: 9<br/>
**Java Engine Version**: 11<br/>
**MariaDB Database Version**: 10

### Deployment

In order to get this solution instantly deployed, click the "DEPLOY TO JELASTIC" button, specify your email address within the widget, choose one of the [Jelastic Public Cloud providers](https://jelastic.cloud) and press Install.

[![GET IT HOSTED](https://raw.githubusercontent.com/jelastic-jps/jpswiki/master/images/getithosted.png)](https://jelastic.com/install-application/?manifest=https%3A%2F%2Fgithub.com%2Fjelastic-jps%2Fopencms%2Fraw%2Fmaster%2Fmanifest.jps)

To deploy this package to Jelastic Private Cloud, import [this JPS manifest](../../raw/master/manifest.jps) within your dashboard ([detailed instruction](https://docs.jelastic.com/environment-export-import#import)).

More information about Jelastic JPS package and about installation widget for your website can be found in the [Jelastic JPS Application Package](https://github.com/jelastic-jps/jpswiki/wiki/Jelastic-JPS-Application-Package) reference.
