# MyFortiLinks - [FortiNAC](https://docs.fortinet.com/product/fortinac-f/) -  [Back to Root](../readme.md)

### FortiNAC initial setup
- [Technical Tip: Comprehensive guide for a simple FortiNAC deployment](https://community.fortinet.com/t5/FortiNAC-F/Technical-Tip-Comprehensive-guide-for-a-simple-FortiNAC/ta-p/264051)
- [FortiNAC "Isolation Vlan concepts"](https://docs.fortinet.com/document/fortinac-f/7.2.0/fortinac-deployment-guide/707033/fortinac-isolation-vlans)
- [Doc: Detailed description of Isolation states](https://docs.fortinet.com/document/fortinac-f/7.6.0/configuration-wizard/369359/layer-3-network#_Toc174456391)
- [Doc: Integrate FortiNAC with Fortinet FortiSwitch and FortiGate](https://docs.fortinet.com/document/fortinac-f/latest/fortiswitch-fortilink-integration/365563/overview)
- [Doc: Integrate FortiNAC with Fortinet FortiAP and FortiGate](https://docs.fortinet.com/document/fortinac-f/latest/fortiap-integration/335351/overview)
- [Technical Tip: How to add a license to FortiNAC-F 7.x from the CLI](https://community.fortinet.com/t5/FortiNAC-F/Technical-Tip-How-to-add-a-license-to-FortiNAC-F-7-from-the-CLI/ta-p/271120) | to be done via SSH / The GUI should be available after 10 to 15 minutes
  ~~~~
  execute license add <license file contents>
  execute service stop nacapplication
  execute service start nacapplication
  get system license
  get system status
  ~~~~


### FortiNAC & Entra
- [Doc: microsoft-entra-id remote groups](https://docs.fortinet.com/document/fortinac-f/7.6.5/microsoft-entra-id-authentication-cookbook/913148/example-remote-group-use-with-user-host-profile)

### FortiNAC Guest
- [Technical Tip: FortiNAC Guest Captive Portal configuration and workflow](https://community.fortinet.com/t5/FortiNAC/Technical-Tip-FortiNAC-Guest-Captive-Portal-configuration-and/ta-p/215606)

### Security Fabric & SSO
- [Doc: Integrate FortiNAC with FortiGate to further enhance FortiGate’s Intent-based Segmentation](https://docs.fortinet.com/document/fortinac-f/latest/security-fabric-sso/404237/overview)

- <details>
  <summary>Get FSSO user List on FGT pushed (by FortiNAC)</summary>
  
        (FGT)# diagnose debug authd fsso list
  </details>


### Special use case
- [Doc: Docking Station Management](https://docs.fortinet.com/document/fortinac-f/latest/docking-station-management/685335/docking-station-management)
- [Doc: Voice vlan using FortiNAC](https://docs.fortinet.com/document/fortinac-f/7.2.0/ip-phone-integration/65140/appendix)
