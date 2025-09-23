## Welcome 👋

Welcome to the GitHub of the CAMARA technical project. General information about the project can be found within the [Wiki](https://lf-camaraproject.atlassian.net/wiki/x/AgDe), on the [Website](https://camaraproject.org) and within the [Governance](https://github.com/camaraproject/Governance) repository. Please read the [Project Charter](https://github.com/camaraproject/Governance/blob/main/ProjectCharter.md) if you want to know what CAMARA and its APIs are about.

The work of CAMARA is happening within the [Sub Projects](https://lf-camaraproject.atlassian.net/wiki/x/NQ7e) with their [Incubating API Repositories](https://github.com/search?q=topic%3Aincubating-api-repository+org%3Acamaraproject&type=Repositories), in [Sandbox API Repositories](https://github.com/search?q=topic%3Asandbox-api-repository+org%3Acamaraproject&type=Repositories),
the [Working Groups](https://github.com/search?q=topic%3Aworkinggroup+org%3Acamaraproject&type=Repositories) and the [Technical Steering Committee](https://wiki.camaraproject.org/display/CAM/Technical+Steering+Committee).

To engage in CAMARA subscribe to our [Mailing Lists](https://lists.camaraproject.org/g/all/subgroups), join the [Community Meetings](https://zoom-lfx.platform.linuxfoundation.org/meetings/telcoapi?view=week) and
[contribute here in GitHub](https://github.com/camaraproject/Governance/blob/main/CONTRIBUTING.md) in the repositories with issues, reviews, pull requests or just your questions in the discussions.

## Fall25 meta-release: Major expansion with 60 CAMARA APIs now available 🚀

A CAMARA meta-release combines a set of CAMARA API versions into a consistent release. All API versions in the meta-release fulfill [defined quality criteria](https://github.com/camaraproject/ReleaseManagement/blob/main/documentation/API-Readiness-Checklist.md) and are aligned with the current CAMARA guidelines in [Commonalities](https://github.com/camaraproject/Commonalities), [Identity and Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement), and [Release Management](https://github.com/camaraproject/ReleaseManagement). There are two meta-releases planned per year (March and September).

We are happy to announce that with the **CAMARA Fall25 meta-release** we have now 10 stable APIs, 27 updated initial APIs, and 23 new (initial) APIs available in CAMARA, which can be implemented and offered by API providers:

<table>
    <thead>
        <tr>
            <th>(1)(2)</th>
            <th>API Name</th>
            <th>Fall25<br>Version</th>
            <th>Spring25<br>Version</th>
            <th>Fall24<br>Version</th>
            <th>Repository</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=10>Stable<br>CAMARA APIs</td>
            <td>device-reachability-status</td>
            <td><b><a href="https://github.com/camaraproject/DeviceReachabilityStatus/releases/tag/r1.2">1.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">0.6.1</a></td>
            <td><a href="https://github.com/camaraproject/DeviceReachabilityStatus">DeviceReachabilityStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status</td>
            <td><b><a href="https://github.com/camaraproject/DeviceRoamingStatus/releases/tag/r1.2">1.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">0.6.1</a></td>
            <td><a href="https://github.com/camaraproject/DeviceRoamingStatus">DeviceRoamingStatus</a></td>
        </tr>
        <tr>
            <td>location-verification</td>
            <td><b><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r3.2">3.0.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">2.0.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>number-verification</td>
            <td><b><a href="https://github.com/camaraproject/NumberVerification/releases/tag/r3.2">2.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/NumberVerification/releases/tag/r2.4">2.0.0</a></td>
            <td><a href="https://github.com/camaraproject/NumberVerification/releases/tag/r1.3">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/NumberVerification">NumberVerification</a></td>
        </tr>
        <tr>
            <td>one-time-password-sms</td>
            <td><b><a href="https://github.com/camaraproject/OTPValidation/releases/tag/r3.2">1.1.1</a></b></td>
            <td><a href="https://github.com/camaraproject/OTPValidation/releases/tag/r2.3">1.1.0</a></td>
            <td><a href="https://github.com/camaraproject/OTPValidation/releases/tag/r1.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/OTPValidation">OTPValidation</a></td>
        </tr>
        <tr>
            <td>qos-profiles</td>
            <td><b><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r3.2">1.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">0.11.1</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>quality-on-demand</td>
            <td><b><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r3.2">1.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">0.11.1</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>sim-swap</td>
            <td><b><a href="https://github.com/camaraproject/SimSwap/releases/tag/r3.2">2.1.0</a></b></td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r2.2">2.0.0</a></td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.4">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap</a></td>
        </tr>
        <tr>
            <td>simple-edge-discovery</td>
            <td><b><a href="https://github.com/camaraproject/SimpleEdgeDiscovery/releases/tag/r2.2">2.0.0</a></b></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/SimpleEdgeDiscovery/releases/tag/r1.3">1.0.0</a></td>
            <td><a href="https://github.com/camaraproject/SimpleEdgeDiscovery">SimpleEdgeDiscovery</a></td>
        </tr>
        <tr>
            <td>device-swap</td>
            <td><b><a href="https://github.com/camaraproject/DeviceSwap/releases/tag/r3.2">1.0.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceSwap/releases/tag/r2.2">0.2.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceSwap">DeviceSwap</a></td>
        </tr>
        <tr>
            <td rowspan=27>Updated initial<br>CAMARA APIs</td>
            <td>application-profiles</td>
            <td><b><a href="https://github.com/camaraproject/ApplicationProfiles/releases/tag/r1.2">0.5.0</a></b></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/ApplicationProfiles">ApplicationProfiles</a></td>
        </tr>
        <tr>
            <td>call-forwarding-signal</td>
            <td><b><a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r3.3">0.4.0</a></b></td>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r2.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r1.3">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal">CallForwardingSignal</a></td>
        </tr>
        <tr>
            <td>carrier-billing</td>
            <td><b><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r3.2">0.5.0</a></b></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r2.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.3">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>carrier-billing-refund</td>
            <td><b><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r3.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r2.2">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.3">0.1.0</a></td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>connectivity-insights</td>
            <td><b><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r3.2">0.6.0</a></b></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">0.5.0</a></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>connectivity-insights-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r3.2">0.6.0</a></b></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">0.5.0</a></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>device-reachability-status-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/DeviceReachabilityStatus/releases/tag/r1.2">0.8.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">0.7.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">0.6.1</a></td>
            <td><a href="https://github.com/camaraproject/DeviceReachabilityStatus">DeviceReachabilityStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/DeviceRoamingStatus/releases/tag/r1.2">0.8.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">0.7.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">0.6.1</a></td>
            <td><a href="https://github.com/camaraproject/DeviceRoamingStatus">DeviceRoamingStatus</a></td>
        </tr>
        <tr>
            <td>geofencing-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r3.2">0.5.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation ">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>kyc-fill-in</td>
            <td><b><a href="https://github.com/camaraproject/KnowYourCustomerFill-in/releases/tag/r1.2">0.4.0</a></b></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.4">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomerFill-in">KnowYourCustomerFill-in</a></td>
        </tr>
        <tr>
            <td>kyc-match</td>
            <td><b><a href="https://github.com/camaraproject/KnowYourCustomerMatch/releases/tag/r1.2">0.4.0</a></b></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.4">0.2.1</a></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomerMatch">KnowYourCustomerMatch</a></td>
        </tr>
        <tr>
            <td>location-retrieval</td>
            <td><b><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r3.2">0.5.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">0.3.0</a></td>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>population-density-data</td>
            <td><b><a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r3.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r2.2">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r1.2">0.1.1</a></td>
            <td><a href="https://github.com/camaraproject/PopulationDensityData">PopulationDensityData</a></td>
        </tr>
        <tr>
            <td>qod-provisioning</td>
            <td><b><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r3.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">0.1.1</a></td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>sim-swap-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/SimSwap/releases/tag/r3.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r2.2">0.2.0</a></td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.4">0.1.2</a></td>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap </a></td>
        </tr>
        <tr>
            <td>blockchain-public-address</td>
            <td><b><a href="https://github.com/camaraproject/BlockchainPublicAddress/releases/tag/r2.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/BlockchainPublicAddress/releases/tag/r1.2">0.2.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/BlockchainPublicAddress">BlockchainPublicAddress</a></td>
        </tr>
        <tr>
            <td>connected-network-type</td>
            <td><b><a href="https://github.com/camaraproject/ConnectedNetworkType/releases/tag/r1.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ConnectedNetworkType">ConnectedNetworkType</a></td>
        </tr>
        <tr>
            <td>connected-network-type-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/ConnectedNetworkType/releases/tag/r1.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ConnectedNetworkType">ConnectedNetworkType</a></td>
        </tr>
        <tr>
            <td>customer-insights</td>
            <td><b><a href="https://github.com/camaraproject/CustomerInsights/releases/tag/r2.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/CustomerInsights/releases/tag/r1.3">0.1.1</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/CustomerInsights">CustomerInsights</a></td>
        </tr>
        <tr>
            <td>device-identifier</td>
            <td><b><a href="https://github.com/camaraproject/DeviceIdentifier/releases/tag/r2.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/DeviceIdentifier/releases/tag/r1.3">0.2.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceIdentifier">DeviceIdentifier</a></td>
        </tr>
        <tr>
            <td>kyc-age-verification</td>
            <td><b><a href="https://github.com/camaraproject/KnowYourCustomerAgeVerification/releases/tag/r1.3">0.2.1</a></b></td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomerAgeVerification">KnowYourCustomerAgeVerification</a></td>
        </tr>
        <tr>
            <td>kyc-tenure</td>
            <td><b><a href="https://github.com/camaraproject/Tenure/releases/tag/r1.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/Tenure/releases/tag/r1.2">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/Tenure">Tenure</a></td>
        </tr>
        <tr>
            <td>number-recycling</td>
            <td><b><a href="https://github.com/camaraproject/NumberRecycling/releases/tag/r2.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/NumberRecycling/releases/tag/r1.3">0.1.1</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/NumberRecycling">NumberRecycling</a></td>
        </tr>
        <tr>
            <td>region-device-count</td>
            <td><b><a href="https://github.com/camaraproject/RegionDeviceCount/releases/tag/r2.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/RegionDeviceCount/releases/tag/r1.3">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/RegionDeviceCount">RegionDeviceCount</a></td>
        </tr>
        <tr>
            <td>webrtc-call-handling</td>
            <td><b><a href="https://github.com/camaraproject/WebRTC/releases/tag/r2.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">0.2.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
        <tr>
            <td>webrtc-events</td>
            <td><b><a href="https://github.com/camaraproject/WebRTC/releases/tag/r2.2">0.2.0</a></b></td>
            <td><a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">0.1.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
        <tr>
            <td>webrtc-registration</td>
            <td><b><a href="https://github.com/camaraproject/WebRTC/releases/tag/r2.2">0.3.0</a></b></td>
            <td><a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">0.2.0</a></td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
        <tr>
            <td rowspan=23>New Initial<br>CAMARA APIs</td>
            <td>application-endpoint-discovery</td>
            <td><b><a href="https://github.com/camaraproject/ApplicationEndpointDiscovery/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ApplicationEndpointDiscovery">ApplicationEndpointDiscovery</a></td>
        </tr>
        <tr>
            <td>application-endpoint-registration</td>
            <td><b><a href="https://github.com/camaraproject/ApplicationEndpointRegistration/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ApplicationEndpointRegistration">ApplicationEndpointRegistration</a></td>
        </tr>
        <tr>
            <td>blockchain-public-address-validation</td>
            <td><b><a href="https://github.com/camaraproject/BlockchainPublicAddress/releases/tag/r2.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/BlockchainPublicAddress">BlockchainPublicAddress</a></td>
        </tr>
        <tr>
            <td>brand-registration</td>
            <td><b><a href="https://github.com/camaraproject/VerifiedCaller/releases/tag/r1.3">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/VerifiedCaller">VerifiedCaller</a></td>
        </tr>
        <tr>
            <td>consent-info</td>
            <td><b><a href="https://github.com/camaraproject/ConsentInfo/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ConsentInfo">ConsentInfo</a></td>
        </tr>
        <tr>
            <td>dedicated-network</td>
            <td><b><a href="https://github.com/camaraproject/DedicatedNetworks/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DedicatedNetworks">DedicatedNetworks</a></td>
        </tr>
        <tr>
            <td>dedicated-network-accesses</td>
            <td><b><a href="https://github.com/camaraproject/DedicatedNetworks/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DedicatedNetworks">DedicatedNetworks</a></td>
        </tr>
        <tr>
            <td>dedicated-network-profiles</td>
            <td><b><a href="https://github.com/camaraproject/DedicatedNetworks/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DedicatedNetworks">DedicatedNetworks</a></td>
        </tr>
        <tr>
            <td>device-data-volume</td>
            <td><b><a href="https://github.com/camaraproject/DeviceDataVolume/releases/tag/r1.3">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceDataVolume">DeviceDataVolume</a></td>
        </tr>
        <tr>
            <td>device-data-volume-subscriptions</td>
            <td><b><a href="https://github.com/camaraproject/DeviceDataVolume/releases/tag/r1.3">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceDataVolume">DeviceDataVolume</a></td>
        </tr>
        <tr>
            <td>energy-footprint-notification</td>
            <td><b><a href="https://github.com/camaraproject/EnergyFootprintNotification/releases/tag/r1.3">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/EnergyFootprintNotification">EnergyFootprintNotification</a></td>
        </tr>
        <tr>
            <td>knowledge-base</td>
            <td><b><a href="https://github.com/camaraproject/ModelAsAService/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ModelAsAService">ModelAsAService</a></td>
        </tr>
        <tr>
            <td>most-frequent-location</td>
            <td><b><a href="https://github.com/camaraproject/MostFrequentLocation/releases/tag/r2.2">0.2.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/MostFrequentLocation">MostFrequentLocation</a></td>
        </tr>
        <tr>
            <td>network-slice-booking</td>
            <td><b><a href="https://github.com/camaraproject/NetworkSliceBooking/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/NetworkSliceBooking">NetworkSliceBooking</a></td>
        </tr>
        <tr>
            <td>optimal-edge-discovery</td>
            <td><b><a href="https://github.com/camaraproject/OptimalEdgeDiscovery/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/OptimalEdgeDiscovery">OptimalEdgeDiscovery</a></td>
        </tr>
        <tr>
            <td>predictive-connectivity-data</td>
            <td><b><a href="https://github.com/camaraproject/PredictiveConnectivityData/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/PredictiveConnectivityData">PredictiveConnectivityData</a></td>
        </tr>
        <tr>
            <td>qa-assistant-manage</td>
            <td><b><a href="https://github.com/camaraproject/ModelAsAService/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ModelAsAService">ModelAsAService</a></td>
        </tr>
        <tr>
            <td>qa-assistant-service</td>
            <td><b><a href="https://github.com/camaraproject/ModelAsAService/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/ModelAsAService">ModelAsAService</a></td>
        </tr>
        <tr>
            <td>qos-booking</td>
            <td><b><a href="https://github.com/camaraproject/QoSBooking/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/QoSBooking">QoSBooking</a></td>
        </tr>
        <tr>
            <td>qos-booking-and-assignment</td>
            <td><b><a href="https://github.com/camaraproject/QoSBooking/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/QoSBooking">QoSBooking</a></td>
        </tr>
        <tr>
            <td>subscription-status</td>
            <td><b><a href="https://github.com/camaraproject/SubscriptionStatus/releases/tag/r1.2">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/SubscriptionStatus">SubscriptionStatus</a></td>
        </tr>
        <tr>
            <td>traffic-influence</td>
            <td><b><a href="https://github.com/camaraproject/TrafficInfluence/releases/tag/r1.3">0.10.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/TrafficInfluence">TrafficInfluence</a></td>
        </tr>
        <tr>
            <td>verified-caller</td>
            <td><b><a href="https://github.com/camaraproject/VerifiedCaller/releases/tag/r1.3">0.1.0</a></b></td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/VerifiedCaller">VerifiedCaller</a></td>
        </tr>
        <tr>
            <td></td>
            <td>home-devices-qod</td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/HomeDevicesQoD/releases/tag/r1.2">0.4.0</a></td>
            <td><a href="https://github.com/camaraproject/HomeDevicesQoD">HomeDevicesQoD</a></td>
        </tr>
    </tbody>
</table>

(1) We try to keep this table up-to-date. Before using an API for your implementation check if there is a newer (patch) release available within the repository. Look for the latest public release.

(2) One additional API, Scam Signal (v0.3.1), was released following the Fall25 meta-release guidelines. This API is developed by and only available on demand through GSMA Open Gateway. For more information, please see the [Scam Signal API description](https://www.gsma.com/solutions-and-impact/gsma-open-gateway/gsma-open-gateway-api-descriptions/).

Visit our [Wiki](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/overview?mode=global) for more details about the [Fall25 meta-release](https://lf-camaraproject.atlassian.net/wiki/x/FQApAg) and the [Release Management in CAMARA](https://lf-camaraproject.atlassian.net/wiki/x/US7e). Please note that there are more APIs in work - see the complete list of [Sandbox API Repositories](https://github.com/search?q=topic%3Asandbox-api-repository+org%3Acamaraproject&type=Repositories) which follows also below.
