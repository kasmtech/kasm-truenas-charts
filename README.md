# Kasm TrueNAS charts

This repository contains the charts needed to deploy Kasm Workspaces in the TrueNAS SCALE platform.

To add this Catalog to TrueNAS SCALE click on Apps -> Manage Catalogs -> Add Catalog and set the following vbariables:

* Catalog Name - kasm
* Repository - https://github.com/kasmtech/kasm-truenas-charts.git
* Preffered Trains - stable
* Branch - develop

![](https://kasm-ci.s3.amazonaws.com/truenas/add_catalog.png)

Once added go to the Available Applications tab and click on install for the kasm entry:

![](https://kasm-ci.s3.amazonaws.com/truenas/install.png)

Enter your desired settings:

![](https://kasm-ci.s3.amazonaws.com/truenas/install_settings.png)

Once deployed you will be presented with two endpoints Admin and Web:

![](https://kasm-ci.s3.amazonaws.com/truenas/card.png)

Click on Admin first and follow the instructions for the web installation wizard. Once completed click on the Web button and login with the credentials you setup during the installation process.
