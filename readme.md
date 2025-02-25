# Power Automate Utils

This repository contains a set of Power Automate workflow providing various basic functionality that may prove useful when implementing Power Platform solutions:

- [Get SharePoint information from Data Source Environment Variables](./Parse%20List%20Data%20Source%20Info/README.md)
- [Get Team Channel Library info from MS Teams context](./Get%20Teams%20Channel%20Library%20Info/README.md)
- [Get Localized choice values for Dataverse record](./Get%20Localized%20choice%20values%20for%20record/README.md)
- [ Get SharePoint information for Dataverse record](./Get%20Dataverse%20record%20SPO/README.md)
- [Xpath transformations - cheatsheet](./xPath%20101/README.md)


## Installation

1. To use the workflow, import either **managed or unmanaged solution** available under [Releases](https://github.com/kkazala/Power-Automate-Utils/releases). If you want to be able to edit the flow, choose **unmanaged**.
1. During the import process, update the connection references and environment variables, as required.
1. After the solution is imported, configure the flows, if necessary, to be executed as a child flow.
1. Add a [service principal](https://learn.microsoft.com/en-us/power-automate/service-principal-support) as an additional owner to ensure business continuity.

## Additional resources

[Helpful tips for using Child Flows](https://www.microsoft.com/en-us/power-platform/blog/power-automate/helpful-tips-for-using-child-flows/?msockid=3f7882d233bd676f193e961932e66616)

[Support for service principal owned flows](https://learn.microsoft.com/en-us/power-automate/service-principal-support)

[Service principal application users can own and run flows](https://learn.microsoft.com/en-us/power-platform/release-plan/2023wave1/power-automate/enable-flows-that-are-owned-service-principals)
