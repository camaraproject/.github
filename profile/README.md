## Welcome 👋

Welcome to the GitHub of the CAMARA technical project. General information about the project you can find within the [Wiki](https://wiki.camaraproject.org), on the [Website](https://camaraproject.org) and within the [Governance](https://github.com/camaraproject/Governance) repository. Please read the [Project Charter](https://github.com/camaraproject/Governance/blob/main/ProjectCharter.md) if you want to know what CAMARA and its APIs are about.

The work of CAMARA is happening within the [Sub Projects](https://wiki.camaraproject.org/display/CAM/Sub+Projects) and their [API Repositories](https://github.com/search?q=topic%3Aapi-repository+org%3Acamaraproject&type=Repositories), 
the [Working Groups](https://github.com/search?q=topic%3Aworkinggroup+org%3Acamaraproject&type=Repositories) and the [Technical Steering Committee](https://wiki.camaraproject.org/display/CAM/Technical+Steering+Committee).

To engage in CAMARA subscribe to our [Mailing Lists](https://lists.camaraproject.org/g/all/subgroups), join the [Community Meetings](https://zoom-lfx.platform.linuxfoundation.org/meetings/telcoapi?view=week) and 
[contribute here in GitHub](https://github.com/camaraproject/Governance/blob/main/CONTRIBUTING.md) in the repositories with issues, reviews, pull requests or just your questions in the discussions. 

## First meta-release of CAMARA APIs now available - Fall24 🚀

A CAMARA meta-release combines a set of CAMARA API versions into a consistent release. All API versions in the meta-release fulfill [defined quality criteria](https://github.com/camaraproject/ReleaseManagement/blob/main/documentation/API-Readiness-Checklist.md) and are aligned with the current CAMARA guidelines in [Commonalities](https://github.com/camaraproject/Commonalities) and [Identity and Consent Management](https://github.com/camaraproject/IdentityAndConsentManagement). There will be two meta-releases per year (March and September).

We are happy to announce the **CAMARA meta-release Fall24** with the following APIs:

![Overview of the 25 APIs within the CAMARA Fall24 meta-release](/profile/images/CAMARA_Meta-release_Fall24.png)

<table>
    <thead>
        <tr>
            <th></th>
            <th>API Name</th>
            <th>Version (1)</th>
            <th>Release Tag (1)</th>
            <th>Repository</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Stable CAMARA APIs</td>
            <td>location-verification</td>
            <td>1.0.0</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>number-verification</td>
            <td>1.0.0</td>
            <td><a href="https://github.com/camaraproject/NumberVerification/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/NumberVerification">NumberVerification</a></td>
        </tr>
        <tr>
            <td>one-time-password-sms</td>
            <td>1.0.0</td>
            <td><a href="https://github.com/camaraproject/OTPValidation/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/OTPValidation">OTPValidation</a></td>
        </tr>
        <tr>
            <td>simple-edge-discovery</td>
            <td>1.0.0</td>
            <td><a href="https://github.com/camaraproject/SimpleEdgeDiscovery/releases/tag/r1.3">r1.3</a>
            <td><a href="https://github.com/camaraproject/SimpleEdgeDiscovery">SimpleEdgeDiscovery</a></td>
        </tr>
        <tr>
            <td>sim-swap</td>
            <td>1.0.0</td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap</a></td>
        </tr>
        <tr>
            <td rowspan=9>Updated initial CAMARA APIs</td>
            <td>carrier-billing</td>
            <td>0.3.0</td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>device-reachability-status</td>
            <td>0.6.0</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceStatusv">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status</td>
            <td>0.6.0</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>home-devices-qod</td>
            <td>0.4.0</td>
            <td><a href="https://github.com/camaraproject/HomeDevicesQoD/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/HomeDevicesQoD">HomeDevicesQoD</a></td>
        </tr>
        <tr>
            <td>kyc-fill-in</td>
            <td>0.2.0</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.3">r1.3</a>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer">KnowYourCustomer</a></td>
        </tr>
        <tr>
            <td>kyc-match</td>
            <td>0.2.1</td>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer/releases/tag/r1.3">r1.3</a>
            <td><a href="https://github.com/camaraproject/KnowYourCustomer">KnowYourCustomer</a></td>
        </tr>
        <tr>
            <td>location-retrieval</td>
            <td>0.3.0</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceLocation">DeviceLocation</a></td>
        </tr>
        <tr>
            <td>qos-profiles</td>
            <td>0.11.0</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td>quality-on-demand</td>
            <td>0.11.0</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td rowspan=6>New Initial APIs</td>
            <td>application-profiles</td>
            <td>0.3.0</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>call-forwarding-signal</td>
            <td>0.2.0</td>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal/releases/tag/r1.3">r1.3</a>
            <td><a href="https://github.com/camaraproject/CallForwardingSignal">CallForwardingSignal</a></td>
        </tr>
        <tr>
            <td>carrier-billing-refund</td>
            <td>0.1.0</td>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/CarrierBillingCheckOut">CarrierBillingCheckOut</a></td>
        </tr>
        <tr>
            <td>connectivity-insights</td>
            <td>0.4.0</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
            <tr>
            <td>population-density-data</td>
            <td>0.1.1</td>
            <td><a href="https://github.com/camaraproject/PopulationDensityData/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/PopulationDensityData">PopulationDensityData</a></td>
        </tr>
        <tr>
            <td>qod-provisioning</td>
            <td>0.1.0</td>
            <td><a href="https://github.com/camaraproject/QualityOnDemand/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/QualityOnDemand">QualityOnDemand</a></td>
        </tr>
        <tr>
            <td rowspan=5>New initial APIs to subscribe<br>for event notifications<br>in CloudEvents format</td>
            <td>connecitivity-insights-subscriptions</td>
            <td>0.4.0</td>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/ConnectivityInsights">ConnectivityInsights</a></td>
        </tr>
        <tr>
            <td>device-reachability-status-subscriptions</td>
            <td>0.6.0</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>device-roaming-status-subscriptions</td>
            <td>0.6.0</td>
            <td><a href="https://github.com/camaraproject/DeviceStatus/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceStatus">DeviceStatus</a></td>
        </tr>
        <tr>
            <td>geofencing-subscriptions</td>
            <td>0.3.0</td>
            <td><a href="https://github.com/camaraproject/DeviceLocation/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/DeviceLocation ">DeviceLocation </a></td>
        </tr>
        <tr>
            <td>sim-swap-subscriptions</td>
            <td>0.3.0</td>
            <td><a href="https://github.com/camaraproject/SimSwap/releases/tag/r1.2">r1.2</a>
            <td><a href="https://github.com/camaraproject/SimSwap">SimSwap </a></td>
        </tr>
    </tbody>
</table>            

(1) We try to keep this table up-to-date. Before using an API for your implementation check if there is a newer (patch) release available within the repository. Look for the latest public release.

Visit our [Wiki](https://wiki.camaraproject.org/display/CAM/CAMARA+Project+Home) for more details about the [meta-release Fall24](https://wiki.camaraproject.org/display/CAM/Meta-release+Fall24) and the [Release Management in CAMARA](https://wiki.camaraproject.org/display/CAM/Release+Management+Working+Group). Please note that there more than 20 further APIs in work - see the complete list of [API Repositories](https://github.com/search?q=topic%3Aapi-repository+org%3Acamaraproject&type=Repositories) which follows also below.

