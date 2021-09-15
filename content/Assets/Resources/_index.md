---
title: "Resources"
weight: 20
---

Export, import, and update resource elements.<br> 

[Workflows](/Library/Worflows/) can use objects that you create independently of [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) as attributes. To use external objects as attributes in workflows, you import them into the server as resource elements.

Objects that [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) [workflows](/Library/Worflows/) can use as resource elements include image files, scripts, XML templates, HTML files, and so on. Any [workflows](/Library/Worflows/)  that run in the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server can use any resource elements that you import into [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html).

{{< img src="/Assets/Resources/resources-view.png" alt="Resources List" >}}

After you import an object into [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) as a resource element, you can make changes to the object in a single location, and propagate those changes automatically to all the [workflows](/Library/Worflows/) that use this resource element.

The maximum size for a resource element is 16 MB.

You can import, export, restore, update, and delete a resource element.

{{< img src="/Assets/Resources/resources-sysprep.png" alt="Resources sample sysprep.inf" >}}

For learning more about [managing resource elements](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID-90E3781B-7B37-4F3E-ADED-81A73BC22EE5.html)