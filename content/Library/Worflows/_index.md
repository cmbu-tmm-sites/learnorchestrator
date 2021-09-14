---
title: "Workflows"
weight: 5
---

Create, edit, schedule, run, and delete workflows.<br> 

[vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) provides a standard library of [workflows](/Library/Worflows/) that you can use to automate operations in your virtual infrastructure. 
The [workflows](/Library/Worflows/) in the standard library are locked in the read-only state. 

{{< img src="/Library/Worflows/workflows-view.png" alt="Workflows Views" >}}

A workflow is a series of actions and decisions that you run sequentiall

Workflows combine actions, decisions, and results that, when performed in a particular order, finish a specific task or a specific process in a virtual environment. Workflows perform tasks such as provisioning virtual machines, backing up, performing regular maintenance, sending emails, performing SSH operations, managing the physical infrastructure, and other general utility operations. Workflows accept inputs according to their function. You can create workflows that run according to defined schedules, or that run if certain anticipated events occur. Information can be provided by you, by other users, by another workflow or [action](/Library/Actions/), or by an external process such as a Web service call from an application. Workflows perform some validation and filtering of information before they run.

Workflows can call upon other workflows. For example, you can have workflow that calls up another workflow to create a new virtual machine.

{{< img src="/Library/Worflows/workflows-createSnapshot.png" alt="Create Snapshot" >}}

You create workflows by using the [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) Client interface’s integrated development environment (IDE), that provides access to the workflow library and the ability to run workflows on the workflow engine. The workflow engine can also take objects from external libraries that you plug in to [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html). This feature allows you to customize processes or implement functions that third-party applications provide.

For learning more about [managing worklflows](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID7D2CBABB-700E-4AFA-83B0-BF2E1419C3A7.html)