# BeyondTrust Privilege Management Cloud

## How To Connect your BeyondTrust Privilege Management Cloud to Cyclops

To connect **BeyondTrust Privilege Management Cloud** to Cyclops, you need to prepare the necessary credentials according to this document, and enter them in the **Cyclops Connection Wizard** for **BeyondTrust Privilege Management Cloud**.

**Follow these steps:**

1. **What should I prepare** before creating a connection + required permissions
2. [**How to create a connection**](https://docs.cyclops.security/docs/integrations/getting-started/Create-Cyclops-Connection) to BeyondTrust Privilege Management Cloud in the "Cyclops Connection Wizard"

---

## What should I prepare

| Number | Connection Input Parameters        | Required / Optional | Default value |
| ------ | ---------------------------------- | ------------------- | ------------- |
| 1      | [Client ID](#1--client-id)         | Required            | \_            |
| 2      | [Client Secret](#2--client-secret) | Required            | \_            |
| 3      | [Base URL](#3--base-url)           | Required            | \_            |

---

### 1 - Client ID

The **Client ID** is part of the OAuth credentials used to authenticate to the BeyondTrust public API.\
To obtain the Client ID and Client Secret, see Configure Access to the Management API.
For more info please refet to https://docs.beyondtrust.com/bips/docs/api

---

### 2 - Client Secret

## The **Client Secret** is used together with the Client ID to generate a valid access token.\
To obtain the Client ID and Client Secret, see Configure Access to the Management API.
For more info please refet to https://docs.beyondtrust.com/bips/docs/api

### 3 - Base URL

Host Name or IP Address (required) - The hostname or IP address of the BeyondTrust Privilege Management Cloud server. This should be in the format of : https://\[yourProductionSub-domainName\]-services.pm.beyondtrustcloud.com