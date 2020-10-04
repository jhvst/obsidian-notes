The following steps explain a general eSIM profile provisioning procedure defined in GSMA RSP technical specification (SGP.22 Phase 1). Refer to the SGP.22 for the details and variations.

1. Profile Preparation
When a user subscribes to the operator's service (ESop interface), the operator prepares a profile in the SM-DP+ (ES2+ interface). As a result, the operator and SM-DP+ shares a code that identifies the generated profile in the SM-DP+. The operator provides the code and the SM-DP+ address to the user (ESop interface).

2. Profile download
The user launches the LPA in the device, and inputs the code and the SM-DP+ address (ESeu interface). The LPA contacts the SM-DP+ (ES8+ interface), and augments the eUICC to establish a secure channel (ES8+ interface) to the SM-DP+. If the eUICC and SM-DP+ successfully completes mutual authentication, then the LPA downloads a ‘bound profile package’ (ES9+ interface) from the SM-DP+.

3. Profile installation and report
The LPA delivers the ‘bound profile package’ to the eUICC (ES10b interface). The eUICC unpacks and installs the profile, and returns the installation result, i.e., success or failure, to the LPA. The LPA relays the profile installation result to the SM-DP+, and eventually to the operator. If the profile is successfully installed, then the operator provides communication service to the user. https://web.archive.org/web/20181011212431/https://developer.samsung.com/tech-insights/eSIM/esim-profile-provisioning-procedure [[Wireless]]


https://github.com/bagyenda/njiwa [[open-source]] [[Github]]

https://github.com/Truphone/LPAd_SM-DPPlus_Connector 

How do SIM Cards work? - SIMtrace https://www.youtube.com/watch?v=iJFnYBJJiuQ [[video]]