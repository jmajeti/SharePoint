# Introduction 

<img src="https://dev.azure.com/MWProductSupport/OnPrem%20Diag/_apis/build/status/SharePoint?branchName=master" />

The **O**n **P**remise **D**iagnostic (**OPD**) for SharePoint is a collection of diagnostic scenarios, analyzers, rules, and insights for
diagnosing common issues in the SharePoint 2016 and 2019 On Premise environments.

<table>
    <td> Supported Products </td>
    <td>
      <img src="https://img.shields.io/static/v1?label=SharePoint&message=2016&color=%231777D6&style=plastic" /> <img src="https://img.shields.io/static/v1?label=SharePoint&message=2019&color=%231777D6&style=plastic" />
    </td>
  </tr>
  <tr>
    <td>Downloads </td>
    <td>
      <img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/onpremdiag/sharepoint/total?color=green&label=Total%20Downloads&style=plastic" /> <br>
    </td>
  </tr>
  <tr>
    <td> Download latest release </td>
    <td> <a href="https://github.com/onpremdiag/SharePoint/releases/download/2.1.1910.08006/2.1.1910.08006.zip"><img src="https://img.shields.io/github/v/release/onpremdiag/sharepoint?label=latest%20version&style=plastic" /></a> </td>
  </tr>
</table>

# Getting Started
The following is required for successful operation
1.	PowerShell **5.0** (or greater) installed on the host machine. Click [here](https://github.com/powershell/powershell) for details
on how to get the latest version for your computer.  
2.	A connection to the internet (*required for update checks and telemetry upload*).
3.	OPD for SharePoint requires Farm and Machine administrative permissions to perform all checks.

# Installation Instructions
Detailed instructions on how to install/upgrade the latest version of OPD can be found [here](https://github.com/onpremdiag/SharePoint/blob/master/docs/Installation.md).

# Operational Instructions
Detailed instruction on how to operate OPD can be found [here](https://github.com/onpremdiag/SharePoint/blob/master/docs/HowToUse.md).

# Telemetry Information
To understand exactly what information is recorded and *potentially uploaded to Microsoft*, click [here](https://github.com/onpremdiag/SharePoint/blob/master/docs/TelemetryData.md).

# Development Instructions
Detail instruction on how to develop diagnostics leveraging the OPD framework cane be
found here:

- [Creating a new project hierarchy](https://github.com/onpremdiag/SharePoint/blob/master/docs/NewProduct.md).
- [Creating your first insight/rule/analyzer/scenario](https://github.com/onpremdiag/SharePoint/blob/master/docs/DevelopmentReadme.md).

# Support
If you encounter an issue with OPD for SharePoint, please select the appropriate link below:
- <a href="mailto:opd-support@microsoft.com?subject=[OPD QUESTION] General Questions">General questions</a>
- <a href="mailto:opd-support@microsoft.com?subject=[OPD BUG] Encountered an exception/bug during use">Bug/Exception</a>
  - Please include the following in your bug/exception report
    - Version of OPD for SharePoint - this can be found in the title bar of the console window
    - Screen shot of error/exception
    - Steps to reproduce the error/exception
- <a href="mailto:opd-support@microsoft.com?subject=[OPD REQUEST] New Scenario">New scenario/feature</a>
  - Please include the following in scenario/feature request
    - How does the issue present itself to an end user (*scenario*)
    - How do we determine that the specific issue exists (*rules*)
    - What should be displayed to the end user when we find a specific issue and how can it be resolved (*insights*)
