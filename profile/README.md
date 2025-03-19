## Welcome 👋

Welcome to the GitHub of the CAMARA technical project. General information about the project you can find within the [Wiki](https://lf-camaraproject.atlassian.net/wiki/x/AgDe), on the [Website](https://camaraproject.org) and within the [Governance](https://github.com/camaraproject/Governance) repository. Please read the [Project Charter](https://github.com/camaraproject/Governance/blob/main/ProjectCharter.md) if you want to know what CAMARA and its APIs are about.

The work of CAMARA is happening within the [Sub Projects](https://lf-camaraproject.atlassian.net/wiki/x/NQ7e) with their [Incubating API Repositories](https://github.com/search?q=topic%3Aincubating-api-repository+org%3Acamaraproject&type=Repositories), in [Sandbox API Repositories](https://github.com/search?q=topic%3Asandbox-api-repository+org%3Acamaraproject&type=Repositories),
the [Working Groups](https://github.com/search?q=topic%3Aworkinggroup+org%3Acamaraproject&type=Repositories) and the [Technical Steering Committee](https://wiki.camaraproject.org/display/CAM/Technical+Steering+Committee).

To engage in CAMARA subscribe to our [Mailing Lists](https://lists.camaraproject.org/g/all/subgroups), join the [Community Meetings](https://zoom-lfx.platform.linuxfoundation.org/meetings/telcoapi?view=week) and
[contribute here in GitHub](https://github.com/camaraproject/Governance/blob/main/CONTRIBUTING.md) in the repositories with issues, reviews, pull requests or just your questions in the discussions.

## Second meta-release of CAMARA APIs now available - Spring25 🚀

A CAMARA meta-release combines a set of CAMARA API versions into a consistent release. All API versions in the meta-release fulfill [defined quality criteria](https://github.com/camaraproject/ReleaseManagement/blob/main/documentation/API-Readiness-Checklist.md) and are aligned with the current CAMARA guidelines in [Commonalities](https://github.com/camaraproject/Commonalities), [Identity and Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement), and [Release Management](https://github.com/camaraproject/ReleaseManagement). There will be two meta-releases per year (March and September).

We are happy to announce that with the **CAMARA meta-release Spring25** we have now 9 stable, 16 updated initial APIs, and 13 new (initial) APIs available in CAMARA, which can be implemented and offered by API providers:

<!-- ![Overview of the 25 APIs within the CAMARA Fall24 meta-release](/profile/images/CAMARA_Meta-release_Fall24.png) -->

<table>
    <thead>
        <tr>
            <th>(1)</th>
            <th>API Name</th>
            <th>Spring25<br>Version (Release)</th>
            <th>Fall24<br>Version (Release)</th>
            <th>Repository</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=9>Stable<br>CAMARA APIs</td>
            <td>device-reachability-status</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.6.1 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.6.1 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>location-verification</td>
            <td>2.0.0 (<a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">r2.2</a>)</td>
            <td>1.0.0 (<a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>number-verification</td>
            <td>1.1.0 ( <a href="https://github.com/camaraproject/NumberVerification/releases/tag/r2.3">r2.3</a>)</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/NumberVerification/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/NumberVerification">NumberVerification</a></td>
        </tr>
        <tr>
            <td>one-time-password-sms</td>
            <td>1.1.0 ( <a href="https://github.com/camaraproject/OTPValidation/releases/tag/r2.3">r2.3</a>)</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/OTPValidation/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/OTPValidation">OTPValidation</a></td>
        </tr>
        <tr>
            <td>qos-profiles</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.11.1 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>quality-on-demand</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.11.1 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>sim-swap</td>
            <td>2.0.0 ( <a href="https://github.com/camaraproject/SimSwap/releases/tag/r2.2">r2.2</a>)</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap</a></td>
        </tr>
        <tr>
            <td>simple-edge-discovery</td>
            <td>-</td>
            <td>1.0.0 ( <a href="https://github.com/camaraproject/SimpleEdgeDiscovery/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/SimpleEdgeDiscovery">SimpleEdgeDiscovery</a></td>
        </tr>
        <tr>
            <td rowspan=16>Updated initial<br>CAMARA APIs</td>
            <td>application-profiles</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>call-forwarding-signal</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal">CallForwardingSignal</a></td>
        </tr>
        <tr>
            <td>carrier-billing</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>carrier-billing-refund</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>connectivity-insights</td>
            <td>0.5.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>connecitivity-insights-subscriptions</td>
            <td>0.5.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>device-reachability-status-subscriptions</td>
            <td>0.7.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.6.1 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status-subscriptions</td>
            <td>0.7.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">r2.2</a>)</td>
            <td>0.6.1 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>geofencing-subscriptions</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation ">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>home-devices-qod</td>
            <td>-</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/HomeDevicesQoD/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/HomeDevicesQoD">HomeDevicesQoD</a></td>
        </tr>
        <tr>
            <td>kyc-fill-in</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.4">r1.4</a>)</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer">KnowYourCustomer</a></td>
        </tr>
        <tr>
            <td>kyc-match</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.2.1 ( <a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.4">r1.4</a>)</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer">KnowYourCustomer</a></td>
        </tr>
        <tr>
            <td>location-retrieval</td>
            <td>0.4.0 ( <a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.3.0 ( <a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>population-density-data</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.1.1 ( <a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r1.2">r1.2</a>)</td>
            <td><a href="https://github.com/camaraproject/PopulationDensityData">PopulationDensityData</a></td>
        </tr>
        <tr>
            <td>qod-provisioning</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r2.2">r2.2</a>)</td>
            <td>0.1.1 ( <a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>sim-swap-subscriptions</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.3">r2.2</a>)</td>
            <td>0.1.1 ( <a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.3">r1.3</a>)</td>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap </a></td>
        </tr>
        <tr>
            <td rowspan=12>New Initial<br>CAMARA APIs</td>
            <td>connected-network-type</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">r2.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>connecitivity-insights-subscriptions</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r2.2">r2.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>customer-insights</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/CustomerInsights/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/CustomerInsights">CustomerInsights</a></td>
        </tr>
        <tr>
            <td>device-identifier</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/DeviceIdentifier/releases/tag/r1.3">r1.3</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceIdentifier">DeviceIdentifier</a></td>
        </tr>
        <tr>
            <td>device-swap</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/DeviceSwap/releases/tag/r2.2">r2.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/DeviceSwap">DeviceSwap</a></td>
        </tr>
        <tr>
            <td>kyc-age-verification</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r2.2">r2.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer">KnowYourCustomer</a></td>
        </tr>
        <tr>
            <td>kyc-tenure</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/Tenure/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/Tenure">Tenure</a></td>
        </tr>
        <tr>
            <td>number-recycling</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/NumberRecycling/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/NumberRecycling">NumberRecycling</a></td>
        </tr>
        <tr>
            <td>region-device-count</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/RegionDeviceCount/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/RegionDeviceCount">RegionDeviceCount</a></td>
        </tr>
        <tr>
            <td>webrtc-call-handling</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
        <tr>
            <td>webrtc-events</td>
            <td>0.1.0 ( <a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
        <tr>
            <td>webrtc-registration</td>
            <td>0.2.0 ( <a href="https://github.com/camaraproject/WebRTC/releases/tag/r1.2">r1.2</a>)</td>
            <td>-</td>
            <td><a href="https://github.com/camaraproject/WebRTC">WebRTC</a></td>
        </tr>
    </tbody>
</table>

(1) We try to keep this table up-to-date. Before using an API for your implementation check if there is a newer (patch) release available within the repository. Look for the latest public release.

Visit our [Wiki](https://lf-camaraproject.atlassian.net/wiki/spaces/CAM/overview?mode=global) for more details about the [meta-release Spring25](https://lf-camaraproject.atlassian.net/wiki/x/US7e) and the [Release Management in CAMARA](https://lf-camaraproject.atlassian.net/wiki/x/US7e). Please note that there are more APIs in work - see the complete list of [Sandbox API Repositories](https://github.com/search?q=topic%3Asandbox-api-repository+org%3Acamaraproject&type=Repositories) which follows also below.
