## WingtipSaaS-StandaloneApp
A sample Web application plus management scripts, built on Azure SQL Database. This is a standalone single-tenant application that might be installed in the tenant's subscription   

This project provides a sample Web application and management scripts that embody common patterns that can be used with Azure SQL Database.  The app is a simple event-management and ticket-selling app for an independent venue that could be customized for each venue.  As a standalone app, it could be installed in the ISV's or the venue's subscription.  It uses a single database that holds the venue's data.  As a stand-alone application, the patterns used are the same as those that might be used if the venue wrote the application for themselves.    

The application, which includes sample data for a single venue, can be installed in your Azure subscription within a single ARM resource group.  To uninstall the application, delete the resource group using the Azure Portal. 

NOTE: if you install the application you will be charged for the Azure resources created.  Actual costs incurred are based on your subscription offer type but are nominal if the application is not scaled up unreasonably and is deleted promptly after you have finished exploring the tutorials.

More information about the sample app and the associated tutorials is here: [https://aka.ms/sqldbsaastutorial](https://aka.ms/sqldbsaastutorial)

To deploy the app to Azure, click the link below.  Deploy the app in a new resource group, and provide a short *user* value that will be appended to several resource names to make them globally unique.  Your initials and a number is a good pattern to use.


<a href="https://aka.ms/deploywingtipsa" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


After deployment completes, launch the app by browsing to ```http://events.contosoconcerthall.USER.trafficmanager.net```, substituting *USER* with the value you set during deployment. 

**IMPORTANT:** If you download and extract the repo or [Learning Modules](https://github.com/Microsoft/WingtipSaaS/tree/master/Learning%20Modules) from a zip file, make sure you unblock the .zip file before extracting. Executable contents (scripts, dlls) may be blocked by Windows when zip files are downloaded from an external source and extracted.

To avoid scripts from being blocked by Windows:

1. Right click the zip file and select **Properties**.
1. On the **General** tab, select **Unblock** and select **OK**.


## License
Microsoft Wingtip SaaS sample application and tutorials are licensed under the MIT license. See the [LICENSE](https://github.com/Microsoft/WingtipSaaS/blob/master/license) file for more details.

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
