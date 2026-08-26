---
title: Subprocessors List
slug: dpa-subprocessors
layout: legal
description: >
  A list of Tailscale's data subprocessors and the kinds of data they handle.
---

**Last Updated: 2026-08-26**

| Subprocessor | Applies to | Purpose of Processing | Data processed | Location |
| --- | --- | --- | --- | --- |
| Amazon Web Services, Inc. | All products |Cloud hosting provider; AI model hosting and processing for certain PAM features | Client device and node information; Configuration information; Customer AI Content (1); PAM Data (3) | United States, European Economic Area |
| DigitalOcean, LLC | All products | Cloud hosting provider for DERP servers (2) | Client device and node information; Configuration information | United States, European Economic Area |
| Hetzner Online GmbH | All products | Cloud hosting provider for DERP servers (2) | Client device and node information; Configuration information | United States, European Economic Area |
| Akamai Technologies, Inc. (Linode) | All products | Cloud hosting provider for DERP servers (2) | Client device and node information; Configuration information | United States |
| Snowflake Inc. | All products | Cloud-based data warehouse | Client device and node information; Configuration information | United States |
| The Constant Company, LLC (Vultr) | All products | Cloud hosting provider for DERP servers (2) | Client device and node information; Configuration information | United States, European Economic Area |
| NetActuate, Inc. | All products | Cloud hosting provider for DERP servers (2) | Client device and node information; Configuration information | United States |
| Atlassian Corporation (Jira Service Management) | All products | Troubleshooting | Contact information | United States |
| Vercel Inc. | Aperture only | Cloud hosting provider; AI gateway | Client device and node information; Configuration information; Customer AI Content (1) | United States (requests may transit global edge locations) |
| OpenAI | PAM only | AI model provider for certain PAM features | PAM Data(3) | United States |

(1) **Customer AI Content** is defined in the [Aperture Terms](https://aperture.tailscale.com/terms).

(2) DERP servers relay end-to-end encrypted traffic when a direct connection between devices is unavailable. The operators listed have no access to the contents of relayed traffic.

(3) PAM Data is defined in the [PAM Terms](https://tailscale.com/pam-terms).
