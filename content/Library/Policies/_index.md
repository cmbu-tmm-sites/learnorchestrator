---
title: "Policies"
weight: 15
---

Create, edit, run, and delete policies.<br> 

Policies are event triggers that monitor the activity of the system. Policies respond to predefined events issued by changes in the status or performance of specific [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) objects.

Policies are a series of rules, gauges, thresholds, and event filters that run certain [workflow](Library/Worflows/) or scripts when specific predefined events occur in [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) or in the technologies that [vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) accesses through [plug-ins](/plugins/). 

{{< img src="/Library/Policies/policies-view.png" alt="Policies List" >}}

[vRealize Orchestrator](https://www.vmware.com/products/vrealize-orchestrator.html) constantly evaluates the policy rules while the policy is running. For instance, you can implement policy gauges and thresholds that monitor the behavior of vCenter Server objects of the <i>VC:HostSystem</i> and <i>VC:VirtualMachine</i> types.
 
{{< img src="/Library/Policies/policies-snmptrap.png" alt="Policy SNMP Trap" >}}

For learning more about [managing policies](https://docs.vmware.com/en/vRealize-Orchestrator/8.5/com.vmware.vrealize.orchestrator-using-client-guide.doc/GUID-FF54CCA4-B33F-4643-BE92-963C32BCEB01.html)