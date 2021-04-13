---
    layout: post
    title: Remotely monitor and service equipment with Connected Field Service for Dynamics 365 and Azure IoT  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/remotely-monitor-and-service-customer-equipment/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/remotely-monitor-and-service-customer-equipment.svg">
####  1. Out of the box, which Dynamics 365 record type can be registered as an IoT device?


<i class='far fa-square'></i> &nbsp;&nbsp;IoT Alert

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Customer Asset

<i class='far fa-square'></i> &nbsp;&nbsp;Work Order

<i class='far fa-square'></i> &nbsp;&nbsp;Product

<i class='far fa-square'></i> &nbsp;&nbsp;Case
<br />
<br />
<br />

####  2. You have a device that has triggered an alert.  You want to remotely reset the device from Dynamics 365.  What should you create?


<i class='far fa-square'></i> &nbsp;&nbsp;Command Definition

<i class='far fa-square'></i> &nbsp;&nbsp;Property Definition

<i class='far fa-square'></i> &nbsp;&nbsp;Device Property

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Command

<i class='far fa-square'></i> &nbsp;&nbsp;Customer Asset
<br />
<br />
<br />

####  3. You have an IoT device that has registered a temperature reading above 70 degrees and triggered an alert.  You need to find the exact reading value to determine what range it falls into to determine the next course of action.  What should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Create a workflow that pulls the reading value directly from the alert data field on the IoT alert.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a workflow that pulls the reading value from the title field on the IoT alert.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a workflow that calls the JSON-Based Field Value Get Boolean action to pull the reading value from the alert data field.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a workflow that calls the JSON-Based Field Value Get Number action to pull the reading value from the alert data field.
<br />
<br />
<br />

####  4. You have an IoT device that has generated a temperature alert in Connected Field Service.  If the temperature is above 70 but below 80, the issue is first attempted to be resolved by a case, and then a work order if the case cannot be resolved.  If the temperature is above 80 degrees, a work order is created.  There are specific items that need to be captured for both the case and work order.   How would you accomplish this?


<i class='far fa-square'></i> &nbsp;&nbsp;Create a non-branching business process flow that starts on the IoT alert entity.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a non-branching business process flow that starts on the case entity.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a non-branching business process flow that starts on the work order entity.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a branching business process flow that starts on the IoT alert entity.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a branching business process flow that starts on the case entity.
<br />
<br />
<br />
