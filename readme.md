# Readme for the 70-535 Exam

Preamble, installing the _Azure PS_ tools.  [From _Microsoft_](https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps?view=azurermps-6.8.1&viewFallbackFrom=azurermps-5.6.0)

Set up the profile so that the `posh-git` and `azureRM` modules are imported when the session is started.  I guess as a reasonably good idea a number of shell launch scripts be created to launch PS with different configuration.

These [notes on creating a profile](https://www.howtogeek.com/50236/customizing-your-powershell-profile/) are straight forward.

Added the `$profile` and added the import modules code.

## Doing Things

From _PowerShell_:

```powershell
Import-Module AzureRM
Connect-AzureRMAccount
```

This pops open a dialog box where credentials can be added to login to _Azure_.

## Source Material

### Books

- [Exam Ref 70-535 Architecting Microsoft Azure Solutions, First Edition](https://www.safaribooksonline.com/library/view/exam-ref-70-535/9781509304769/)
- [Architecting Microsoft Azure Solutions - Exam Guide 70-535](https://www.safaribooksonline.com/library/view/architecting-microsoft-azure/9781788991735/)
- [Architecting Microsoft Azure Solutions Study & Lab Guide Part 1: Exam 70-535](https://www.amazon.ca/gp/product/B07DVCBZ8R)
- [Architecting Microsoft Azure Solutions Study & Lab Guide Part 2: Exam 70-535](https://www.amazon.ca/gp/product/B07FRXZRKR)

### Web Site

- [Companion to the Study Guides](https://mykloud.wordpress.com/2018/06/29/70-535-exam-experience/)
- [Microsoft Quick Start VM](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/)

## Daily Log

### 2018-08-30

Determined plan and purchased the two work books, pursued the [MeasureUp]() people about the currency of the the exam, it was updated in January and they expect to update it again in a "few weeks".  Discussed the plan to proceed with the architecting course with Lise, the take awy is "this technology has no value to _CaseWare_ outside of the certification requirements for the _Microsoft Gold Partnership_".

### 2018-08-31

Confirmed that my [MSDN Azure](https://portal.azure.com/#@waltspeelmancaseware.onmicrosoft.com/dashboard/private/1df9e861-7c08-4642-aec3-1e4bef73a017) site was active and for some reason configured under *waltspeelman@outlook.com*.  

This is the username - password set to use on all _Azure_ resources: *walt*`0I3t!!lD#sPC`

### 2018-09-01

I had started with the _Microsoft Press_ book, but it is tough going.  I'm jumping over to the _Packt>_ book to see if it's better reading.  Hoping to get to the first lab tonight, I suspect I will need multiple monitors.

### 2018-09-02

Jumped on the first lab: yikes, time to learn networking for developers.  Heading over to _udacity_ [Networking for Web Developers](https://classroom.udacity.com/courses/ud256) to learn basic networking.  There's also a _PluralSight_ ([TCP/IP Networking for Developers](https://app.pluralsight.com/library/courses/tcp-ip-networking-for-devs)) video on this.