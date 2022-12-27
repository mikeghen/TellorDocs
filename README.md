---
cover: .gitbook/assets/Tellor DocsG.png
coverY: 0
---

# Welcome

## What is Tellor? <a href="#what-is-tellor" id="what-is-tellor"></a>

Tellor is an immutable decentralized oracle protocol that incentivizes an open, permissionless network of data reporting and data validation, ensuring that data can be provided by anyone and checked by everyone.

Built for any [data type](https://tellor.io/blog/how-to-query-custom-data-with-tellor/), our network of [reporters](https://docs.tellor.io/tellor/reporting-data/becoming-a-reporter) supports your basic spot prices, more sophisticated pricing specs (TWAP/VWAP), Snapshot Vote Results, or any custom data needs you have. If your data can be verified, Tellor can [bring it on-chain](https://feed.tellor.io).

{% hint style="info" %}
**Before you get started**

* [Learn Tellor's Fundamental Concepts](the-basics/fundamentals.md)
* [Read the FAQ](the-basics/fundamentals.md#faq)
* [Read the Whitepaper](https://tellor.io/whitepaper/)
* [Review the Contracts Overview](the-basics/contracts-overview.md)
{% endhint %}

## Get started <a href="#get-started" id="get-started"></a>

{% tabs %}
{% tab title="I want a price feed" %}
1. [Get a QueryID](getting-data/creating-a-query.md#getting-a-query-id-and-query-data)
2. [Check if Telliot can currently report it](https://github.com/tellor-io/telliot-feeds/tree/main/src/telliot\_feeds/feeds)
   * if yes, go to step 3
   * if no, [request a new spotPrice asset](https://github.com/tellor-io/dataSpecs/issues/24)
3. [Get your data](https://docs.tellor.io/tellor/getting-data/reading-data)
{% endtab %}

{% tab title="I want custom data" %}
**Tellor is built to bring practically any data on chain**

* [More information on how to add new data types](getting-data/creating-a-query.md#creating-a-new-query-type)
{% endtab %}

{% tab title="I want to report data" %}
**Learn more about becoming a reporter**

* [Reporter Documentation](https://docs.tellor.io/tellor/reporting-data/becoming-a-reporter)
{% endtab %}

{% tab title="I am testing" %} 
* [The Tellor Playground](https://github.com/tellor-io/TellorDocs/blob/brenda/getting-data/reading-data/tellor-playground.md) is a simplified Tellor (and not a real oracle) that aims to help anyone building to quickly test and implement ideas. 
{% endtab %}


{% endtabs %}

### Quicklinks

#### Developer tools

[Tellor Github](https://github.com/tellor-io)

[Data Specs](https://github.com/tellor-io/dataSpecs)

[Live Feeds](https://feed.tellor.io/)

[QueryID Builder](https://queryidbuilder.herokuapp.com/)

[Get Testnet TRB](https://twitter.com/trbfaucet)

#### Educational

[Dev Calls](https://www.youtube.com/playlist?list=PLuJHbmh0kCXXA6XrTM6dgYgz-RXiFNmRF)

[Reporter Calls](https://www.youtube.com/playlist?list=PLuJHbmh0kCXX1L2V5Bn3Qe-zlMmg5L4yG)

[Tellor School](https://www.youtube.com/playlist?list=PLuJHbmh0kCXVPHDA2Q3J3TfatBRGrOsm-)

[Weekly Updates](https://www.youtube.com/playlist?list=PLuJHbmh0kCXWRe-QPxaqcThzmj743ercz)

### Get Help

[Ask us anything](https://discord.com/channels/461602746336935936/794270931630948432)

#### Looking to use Tellor?

[Tell us what you're building and we'll get in touch](https://docs.google.com/forms/d/e/1FAIpQLSc5YEerq5y5\_YBiQg7ZwDVw76o\_1KmRmqXvzjeZlfshNKTvaQ/viewform)
