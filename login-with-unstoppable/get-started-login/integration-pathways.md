---
title: Login Integration Pathways | Unstoppable Domains Developer Portal
description: This page reviews the integration guides for Login with Unstoppable. This feature works for Polygon and Ethereum domains.
---

# Login Integration Pathways

Login with Unstoppable is a versatile feature with several integration pathways available for developers. This page reviews the integration guides, overall features, and related libraries for each installation option.

<embed src="/snippets/_login-mainnet-warning.md" />

## Step 1: Get Your Client Credentials

To begin the integration process for Login with Unstoppable, you will need to obtain and configure your client credentials using the **My Clients** and **Client Configuration** pages. Please see the [**Login Client Configuration**](../login-integration-guides/login-client-configuration.md) guide for more details.

## Step 2: Choose Your Integration Path

There are several ways to integrate with Login with Unstoppable, which are detailed in the chart below.

| Integration Guide                                                             | Package            | Ethereum Provider | Callback | Front-end UI       |
|-------------------------------------------------------------------------------|:------------------:|:-----------------:|:--------:|:------------------:|
| [Login with Pop-up](../login-integration-guides/login-with-popup.md)          |`@uauth/js`          |     &#10060;     | &#10060; |  Generic, Pop-up   |
| [Login without Pop-up](../login-integration-guides/login-without-popup.md)    |`@uauth/js`          |     &#10060;     | &#9989;  | Generic, no Pop-up |
| [Web3 React](../login-integration-guides/web3-react-guide.md)                 |`@uauth/web3-react`  |     &#9989;      | &#10060; |     `web3-react`   |
| [Web3 Modal](../login-integration-guides/web3-modal-guide.md)                 |`@uauth/web3-modal`  |     &#9989;      | &#10060; |     `web3-modal`   |
| [BNC Onboard](../login-integration-guides/bnc-onboard-guide.md)               |`@uauth/bnc-onboard` |     &#9989;      | &#10060; |     `bnc-onboard`  |
| [Moralis](../login-integration-guides/moralis-guide.md)                       |`@uauth/moralis`     |     &#9989;      | &#10060; |     `moralis`      |
| [Node.js Server](../login-integration-guides/node-js-server-guide.md)         |`@uauth/node`        |     &#10060;     | &#9989;  |          None*     |

**The `@uauth/dom-ui` package is recommended to help with front-end UI.*

:::info
The [UAuth Demo Application](https://uauth-demo.uc.r.appspot.com) is available for developer use along with a [single page sample application](https://github.com/unstoppabledomains/uauth/tree/main/examples/spa/src) to model the flow. Applications can also use Unstoppable Domain’s [UAuth Library](https://github.com/unstoppabledomains/uauth) to simplify the integration.
:::

## Step 3: Configure the Login UI

Login with Unstoppable has UI requirements that must be configured to properly display the authenticated user's domain name after a successful login. Please follow the instructions in the [**Login UI Configuration**](../login-integration-guides/login-ui-configuration.md) guide to complete this final step in the integration process.

## Step 4: Promote Your Application

Once your integration is live, you can [promote your application](/use-cases/promote-ud-integration.md) by submitting it to the official UD [app integrations database](https://unstoppabledomains.com/apps). 

<embed src="/snippets/_discord.md" />