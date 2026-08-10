# MyFortiLinks - [FortiAuth](https://docs.fortinet.com/product/fortiauthenticator/) -  [Back to Root](../readme.md)



### Guest portal & Auth
- [Technical Tip: How to configure FortiGate Captive Portal via FortiAuthenticator](https://community.fortinet.com/fortiauthenticator-8/technical-tip-how-to-configure-fortigate-captive-portal-via-fortiauthenticator-99536)
- [Doc: FortiAuthenticator as a Wireless Guest Portal for FortiGate](https://docs.fortinet.com/document/fortiauthenticator/6.6.0/examples/578250/fortiauthenticator-as-a-wireless-guest-portal-for-fortigate)
- [Technical Tip: Configure Guest captive portal with External CA certificate in FortiAuthenticator](https://community.fortinet.com/fortiauthenticator-8/technical-tip-configure-guest-captive-portal-with-external-ca-certificate-in-fortiauthenticator-93026)

### 802.1x Auth
- [Doc: Computer authentication using FortiAuthenticator with MS AD Root CA](https://docs.fortinet.com/document/fortiauthenticator/6.5.0/cookbook/3965/computer-authentication-using-fortiauthenticator-with-ms-ad-root-ca)
- [Technical Tip: FortiAuthenticator 802.1x EAP-TLS with computer authentication](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-FortiAuthenticator-802-1x-EAP-TLS-with-computer/ta-p/212559)
- [Technical Tip: FortiAuthenticator 802.1x EAP-TLS with computer authentication](https://community.fortinet.com/fortiauthenticator-8/technical-tip-fortiauthenticator-802-1x-eap-tls-with-computer-authentication-108478)


### LDAP Tips
- [Technical Tip: LDAP filter syntax for groups and remote user sync rules](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-LDAP-filter-syntax-for-groups-and-remote-user-sync/ta-p/193190)
- [Technical Tip: FortiAuthenticator does not sync the LDAP Tree when in the Load Balancing mode](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-FortiAuthenticator-does-not-sync-the-LDAP-Tree/ta-p/432003)
- [Technical Tip: LDAPS with FortiAuthenticator](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-LDAPS-with-FortiAuthenticator/ta-p/223993)


### SAML Auth
- [Doc: FAC as SAML IdP proxy for Azure](https://docs.fortinet.com/document/fortiauthenticator/6.6.0/examples/374954/saml-idp-proxy-for-azure)
- [Doc: FortiGate Agentless VPN with FortiAuthenticator as the IdP proxy for Azure](https://docs.fortinet.com/document/fortiauthenticator/8.0.0/examples/608970/fortigate-agentless-vpn-with-fortiauthenticator-as-the-idp-proxy-for-azure)
- <details>
        <summary>Check saml debugs on FGT to check groups sent</summary>
        
            (FGT)# diag debug reset
            (FGT)# diag debug application samld -1
            (FGT)# diag debug console timestamp enable
            (FGT)# diag debug enable

    </details>

### FAC as a Root CA & SCEP Server
- [Technical Tip: FortiGate Certificate enrollment and renewal using SCEP](https://community.fortinet.com/fortigate-3/technical-tip-fortigate-certificate-enrollment-and-renewal-using-scep-138545)
- [Doc: Intune Certificate Provisioning with FortiAuthenticator CA](https://docs.fortinet.com/document/fortiauthenticator/8.0.0/examples/481078/intune-certificate-provisioning-with-fortiauthenticator-ca)



### Windows AD
- [Technical Tip: Join FortiAuthenticator to Windows AD with non-administrator account configured with minimum privileges](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-Join-FortiAuthenticator-to-Windows-AD-with-non/ta-p/214599)
- [Technical Tip: How to join FortiAuthenticator to multiple domains](https://community.fortinet.com/t5/FortiAuthenticator/Technical-Tip-How-to-join-FortiAuthenticator-to-multiple-domains/ta-p/433270)
