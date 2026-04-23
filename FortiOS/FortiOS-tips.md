# MyFortiLinks - [FortiOS](https://docs.fortinet.com/product/fortigate/) -  [Back to Root](../readme.md)

### FortiGate CheatSheets

- [External] [Boll.ch: CheatSheet FOS 7.6](https://blog.boll.ch/cheatsheet-fortios-v7-6/)
- [External] [InfosecMonkey.com: CLI Bible](https://infosecmonkey.com/my-fortigate-fortios-cli-bibleish/)
- [My CLI Cheatsheet](./FortiOS-cli.md)




### Recommended versions & Best practice

- [Technical Tip: Recommended Release for FortiOS](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Recommended-Release-for-FortiOS/ta-p/227178)
- [Technical Tip: Recommended Release for FortiManager and FortiAnalyzer](https://community.fortinet.com/t5/FortiManager/Technical-Tip-Recommended-Release-for-FortiManager-and/ta-p/231910)
- [Technical Tip: Best practices for firewall policy configuration](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Best-practices-for-firewall-policy-configuration/ta-p/193255)



### Management Access

- [Doc: FortiOS Hardening](https://docs.fortinet.com/document/fortigate/latest/best-practices/555436/hardening)
- [Doc: Local-in policies](https://docs.fortinet.com/document/fortigate/latest/administration-guide/363127/local-in-policy)
    Note that since 7.6.1 a [default Local-In](https://docs.fortinet.com/document/fortigate/7.6.6/administration-guide/363127/local-in-policy#Default) is applied blocking known Malicious servers
- [Doc: Virtual patching on the local-in management interface](https://docs.fortinet.com/document/fortigate/7.6.6/administration-guide/393161/virtual-patching-on-the-local-in-management-interface)
- [External] [blog.guenay.at: Using Local-in policies to restrict access to Management interface](https://github.com/KevinGuenay/fortigate-baseline/blob/main/baseline.md#use-local-in-policies-to-restrict-access-to-management-services)



### Logging

- [Technical Tip: How to configure logging to disk on the FortiGate using the GUI or the CLI](https://community.fortinet.com/t5/FortiGate/Technical-Tip-How-to-configure-logging-to-disk-on-the-FortiGate/ta-p/216995)
- [Technical Tip: Hard disk utilization by the FortiGate](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Hard-disk-utilization-by-the-FortiGate/ta-p/195481)
- [Troubleshooting Tip: FortiGate to FortiAnalyzer connectivity](https://community.fortinet.com/t5/FortiAnalyzer/Troubleshooting-Tip-FortiGate-to-FortiAnalyzer-connectivity/ta-p/191833)
- [Technical Tip: Null device logging - allow to estimate the logging amount per day easily](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Null-device-logging/ta-p/338478)


### Access internal ressources from Outside

- [Technical Tip: Using Virtual IPs to configure port forwarding](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Using-Virtual-IPs-to-configure-port-forwarding/ta-p/198195)
- [Technical Tip: How to configure SAML authentication for firewall policy with Virtual IP (VIP)](https://community.fortinet.com/t5/FortiGate/Technical-Tip-How-to-configure-SAML-authentication-for-firewall/ta-p/243639)


### VPN Ressources
- [Technical Tip: FortiGate IPsec VPN resource list](https://community.fortinet.com/t5/FortiGate/Technical-Tip-FortiGate-IPsec-VPN-resource-list/ta-p/213560)
- [Technical Tip: FortiGate SAML authentication resource list](https://community.fortinet.com/t5/FortiGate/Technical-Tip-FortiGate-SAML-authentication-resource-list/ta-p/213924)
- [Technical Tip: Overview of compatible IKE versions, user authentication methods, and FortiGate/FortiClient firmware versions](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Overview-of-compatible-IKE-versions-user/ta-p/420733)
- [Technical Tip: Increasing email Token expiry time](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Increasing-email-Token-expiry-time/ta-p/190638)
- [Technical Tip: How to block IPsec fail connection attempts over a blacklist (ESP IKEv1 or IKEv2, Phase 1 mismatch config and authentication failure)](https://community.fortinet.com/t5/FortiGate/Technical-Tip-How-to-block-IPsec-fail-connection-attempts-over-a/ta-p/411328)
- [Doc: Windows IKEv2 native VPN with user certificate](https://docs.fortinet.com/document/fortigate/latest/administration-guide/726232)
- [Doc: Trusted Endpoint SSO](https://docs.fortinet.com/document/fortiauthenticator/8.0.0/iam-architecture-guide/713052/trusted-endpoint-sso)
- [External] [Andrew Travis: IPSec VPN with SAML auth](https://www.andrewtravis.com/blog/ipsec-vpn-with-saml)

### GenAI & LLM related Features

- [Technical Guide: Selective control & monitoring of GenAI / LLM application traffic with Fortinet Security Fabric](https://community.fortinet.com/t5/FortiGate/Technical-Guide-Selective-control-amp-monitoring-of-GenAI-LLM/ta-p/405240)
- [Doc: Application control support for generative AI 7.6.4](https://docs.fortinet.com/document/fortigate/latest/new-features/679448/application-control-support-for-generative-ai-7-6-4)
    <details>
    <summary>Check Version/updates of App Control GenAI DB</summary>
    
        (FGT)# diagnose autoupdate versions | grep -A 6 GenAI

    Note : if GenAI DB is not up to date, reason could be you have no app control profile enabled on any FW Policy : enable at least one FW rule with App control profile enabled
    </details>
- [Technical Tip: Blocking Chat GPT](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Blocking-Chat-GPT/ta-p/255020)
- [Doc: AI and ML-based IPS detection (7.6.3+)](https://docs.fortinet.com/document/fortigate/7.6.0/new-features/408891/ai-and-ml-based-ips-detection-7-6-3)

### 802.1x

- [Doc: Using 802.1X on FortiGate interface](https://docs.fortinet.com/document/fortigate/latest/administration-guide/100999/hardware-switch#:~:text=Example%20of%20using%20802.1X%20on%20virtual%20switches)


### Fortilink NAC

- [Troubleshooting Tip: FortiSwitch port flap with laptop connected with wifi/wired using FortiClient EMS tags](https://community.fortinet.com/t5/FortiSwitch/Troubleshooting-Tip-FortiSwitch-port-flap-with-laptop-connected/ta-p/360109)


### FSSO

- [Technical Tip: A detailed guide to FSSO Mobility Agent](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-A-detailed-guide-to-FSSO-Mobility-Agent/ta-p/428712)
- [Doc: FortiAuthenticator SSOMA for native Microsoft Entra ID joined workstation](https://docs.fortinet.com/document/fortiauthenticator/latest/examples/669124)

### VDOM

- [Doc: Enable Vdom on FortiGate](https://docs.fortinet.com/document/fortigate/latest/administration-guide/32293/general-configurations)
    <details>
    <summary>Example of VDOM</summary>
        
        (FGT)# 
        config system global
            set vdom-mode multi-vdom
            set edit-vdom-prompt enable
        end
    </details>


- [Doc: Multitenancy, VDOMS and Fortiswitches](https://docs.fortinet.com/document/fortiswitch/latest/fortilink-guide/801172)



### Virtual Firewall Tips
- [Doc: Microsegmentation (L2 proxy ARP) with virtual FortiGate and VMware vCenter](https://docs.fortinet.com/document/fortigate-private-cloud/7.6.0/vmware-esxi-administration-guide/793933/microsegmentation-l2-proxy-arp-with-virtual-fortigate-and-vmware-vcenter)
- [Doc: Optimizing FortiGate-VM performance](https://docs.fortinet.com/document/fortigate-private-cloud/7.6.0/vmware-esxi-administration-guide/965486/optimizing-fortigate-vm-performance)


### System optimisation

- [Technical Tip: Low-end FortiGate models with RAM ≤ 2GB entering conserve mode due to increased ISDB database](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Low-end-FortiGate-models-with-RAM-2GB-entering/ta-p/295489)
- [Technical Tip: How to optimize memory consumption for smaller FortiGates (<200F)](https://community.fortinet.com/t5/FortiGate/Technical-Tip-How-to-optimize-memory-consumption-for-smaller/ta-p/192323)
- [Technical Tip: Memory Optimization Script for FortiGate Desktop Devices](https://community.fortinet.com/t5/FortiGate/Technical-Tip-Memory-Optimization-Script-for-FortiGate-Desktop/ta-p/285711)
- [Doc: Inspection mode feature comparison](https://docs.fortinet.com/document/fortigate/latest/administration-guide/922096/inspection-mode-feature-comparison)


### SDWAN
- [Technical Tip: Fortinet SD-WAN Remote SLAs](https://community.fortinet.com/fortigate-3/technical-tip-fortinet-sd-wan-remote-slas-197784)


### IPS 
- [AI and ML-based IPS detection](https://docs.fortinet.com/document/fortigate/7.6.6/administration-guide/408891/ai-and-ml-based-ips-detection)
- [AI and ML-based IPS detection - New feature 7.6.3+](https://docs.fortinet.com/document/fortigate/7.6.3/fortios-release-notes/743723/new-features-or-enhancements#:~:text=enable%20%7C%20disable%7D%0Aend-,1091818,-As%20cyber%20threats)