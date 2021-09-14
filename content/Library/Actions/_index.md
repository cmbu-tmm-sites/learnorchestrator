---
title: "Actions"
weight: 10
---

Create, edit, and delete actions. The action editor supports automatic completion for common script elements included in the [vRealize Orchestrator API Explorer](/API-Explorer/).<br> 

You can modify your [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) workflows by adding actions scripts.

The [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) Client provides libraries of predefined actions and an action editor for custom action scripts. Actions represent individual functions that you use as building blocks in [workflows](/Library/Worflows/).

{{< img src="/Library/Actions/actions-view.png" alt="Action Views" >}}

Actions are JavaScript, Python, NodeJs or PowerShell functions. Actions can take multiple input parameters and have a single return value. Actions can call on any object in the [vRealize Orchestrator API Explorer](/API-Explorer/), or objects in any API that you import into [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) by using a [plug-in](/plugins/).

{{< img src="/Library/Actions/actions-getnic.png" alt="Action Get Nic" >}}

For learning more about [managing actions](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID-02662EDA-2CDA-4287-9124-C2B177E9C000.html)