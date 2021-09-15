---
title: "Packages"
weight: 10
---

Create, delete, export, and import packages containing [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) objects.<br> 

Use the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) Client to create, export, and import packages. Packages can be used to export workflow objects for use on other [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) instances.

Packages can contain [workflows](/Library/Worflows/), [actions](/Library/Actions/), [policies](/Library/Policies/), [configuration elements](/Assets/Configurations/), or [resources elements](/Assets/Resources/).

{{< img src="/Assets/Packages/packages-view.png" alt="Packages List" >}}

When you add an element to a package, [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) checks for dependencies and adds any dependent elements to the package. For example, if you add a [workflows](/Library/Worflows/) that uses [actions](/Library/Actions/) or other [workflows](/Library/Worflows/), [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) adds those actions and [workflows](/Library/Worflows/) to the package.

{{< img src="/Assets/Packages/packages-content.png" alt="Packages Content" >}}

When you import a package, the server compares the versions of the different elements of its contents to matching local elements. The comparison shows the differences in versions between the local and imported elements. The user can decide whether to import the package, or can select specific elements to import.

For most objects created in the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) Client, aside from resource elements, packages are the only way to export and import these objects.

Packages use digital rights management to control how the receiving server can use the contents of the package. [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) signs packages and encrypts the packages for data protection. Packages can track which users export and redistribute elements by using X509 certificates.

For learning more about [managing packages](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID-CCCC435B-C083-4E2E-B553-7D1DAF517488.html)