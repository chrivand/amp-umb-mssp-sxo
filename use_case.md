Cisco Secure Endpoint MSSP security event handling with SecureX and ServiceNow
=====================================
Which events are high priority? Which should trigger incidents to be created?

## Business Case
Many Managed Security Services Partners (MSSP) strugle in managing their customers' security events as. This use case specifically focusses on Cisco Secure Endpoint (formerly known as AMP), SecureX and ServiceNow. This sample solution can obviously be extrapolated to other solutions too. This sample solution is a working prototype, built in SecureX Orchestration, and is executed when certain high priority events (like when a computer is compromised) occur. It will automatically create a SecureX incident, as well as a ServiceNow incident. Many MSSP's use ServiceNow or some other ticketing system to manage their customers, so now they can keep using that interface. When the incident is handled and closed, this will also automatically close the SecureX incident for auditing purposes. This results in a single pane of glass for the MSSP: they can use SecureX and Secure Endpoint on the background via ServiceNow!

This entire solution is built inside of SecureX orchestation:
* SecureX orchestration provides a no-to-low code approach for building automated workflows. 
* These workflows can interact with various types of resources and systems, whether they’re from Cisco or a third-party. 
* This repository contains workflows that can be imported into SecureX orchestration and are easy to set up, without having to know code syntax.

## Related Code Exchange submission
Please see the workflow installation information [here](https://developer.cisco.com/codeexchange/github/repo/chrivand/amp-mssp-events-to-snow).

## White Paper
Please continue your reading in this [white paper](https://www.cisco.com/c/en/us/products/collateral/security/white-paper-c11-744498.html).

## Related Sandbox
Currently there is no DevNet sandbox yet, however you can find all options to try out SecureX orchestration [here](https://developer.cisco.com/learning/lab/Cisco-SecureX-101-lab/step/1)!

## List of SecureX Learning Labs
* Please try out [this SecureX DevNet learning lab](https://developer.cisco.com/learning/modules/SecureX-orchestration) to try this yourself. 
* Please also check out the [SecureX microsite](https://developer.cisco.com/securex/) on DevNet!

## Solutions on Ecosystem Exchange
Please check out related solutions on [DevNet Ecosystem Exchange](https://developer.cisco.com/ecosystem/solutions/#key=securex).
