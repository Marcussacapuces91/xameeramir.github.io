---
layout: post
title: site launch pre-requisites
---

![To do](http://media4.onsugar.com/files/2014/01/16/081/n/1922441/f03ad4c4d1b6bbfb_shutterstock_160289540.jpg.xxxlarge_2x.jpg)

[courtesy](http://www.popsugar.com/smart-living/Career-Money-News-Jan-16-2014-33539493)

I'm writing this post to list all the mistakes I make during ASP.NET [cloud](http://cloud.google.com/) deployments.

 - Get the [database connector](http://dev.mysql.com/downloads/connector/net)
 - Stare that *publish successful* notification on the Visual studio output window
 - Grab that awesome [URL rewrite module](http://stackoverflow.com/a/25317499/2404470)
 - Set [IIS_IUSRS](http://stackoverflow.com/a/18621550/2404470) and [app pool](http://stackoverflow.com/a/7334485/2404470) free
 - Check that your application pool refers to correct version of .NET
 - Get [re-certified](https://in.godaddy.com/help/request-an-ssl-certificate-562) - obviously it's a new server, right?
 - [Import](http://windows.microsoft.com/en-us/windows/import-export-certificates-private-keys#1TC=windows-7) and [install](https://in.godaddy.com/help/installing-an-ssl-certificate-in-microsoft-iis-5-and-6-4875) certificate
 - Import the same in [IIS](https://www.godaddy.com/help/installing-an-ssl-certificate-in-microsoft-iis-8-4951)
 