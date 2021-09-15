---
title: "Configurations"
weight: 15
---

Create, run, and delete configuration elements.<br> 

A configuration element is a list of variables, that you can use to configure constants across a whole [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server deployment.

You can use configuration elements to make variables available to all the [workflows](/Library/Worflows/), [actions](/Library/Actions/) and [policies](/Library/Policies/) running on the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server.

{{< img src="/Assets/Configurations/configurations-view.png" alt="Configurations List" >}}

If you create a package containing a [workflows](/Library/Worflows/), [actions](/Library/Actions/) or [policies](/Library/Policies/)that uses a variable from a configuration element, [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) automatically includes the configuration element in the package. If you import a package containing a configuration element into another[vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server, you can import the configuration element variable values as well. 

{{< img src="/Assets/Configurations/configurations-batchaction.png" alt="Configuration sample Batch Action" >}}

For example, if you create a [workflows](/Library/Worflows/) that requires variable values that depend on the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server on which it runs, setting those variables in a configuration element lets you export that [workflows](/Library/Worflows/), so that another [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) server can use it. Configuration elements therefore allow you to exchange [workflows](/Library/Worflows/), [actions](/Library/Actions/) and [policies](/Library/Policies/ between servers more easily.

For learning more about [managing packages](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID-8A67E2A8-236A-4049-9F99-510FC0B0B1A7.html)