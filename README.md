# RugLens

High-performance rugpull market analysis client powered by RugPlay.

## Overview
RugLens is a real-time market analysis and rugpull detection interface that leverages the RugPlay API to analyze token behavior, liquidity dynamics, wallet clustering, and contract risk to surface actionable trading intelligence.

No installation. No accounts. Just plug in your RugPlay API key and query.

## How It Works
RugLens acts as a lightweight analysis layer on top of RugPlay’s on-chain intelligence infrastructure, transforming raw API signals into clean, actionable outputs for traders and researchers.

## Getting Started

1. Obtain a RugPlay API key.
2. Insert your API key into the configuration.
3. Query the RugLens analyzer.

## Configuration

```js
const API_KEY = "YOUR_RUGPLAY_API_KEY";
````

## Example Usage

```js
import { analyzeToken } from "./ruglens.js";

const result = await analyzeToken("0xTOKEN_ADDRESS");
console.log(result);
```

## Output

* Rug probability score
* Liquidity safety rating
* Insider wallet exposure
* Contract risk flags
* Market manipulation signals

## Features

* Real-time rugpull analysis
* Market risk scoring
* Clean intelligence outputs
* Zero infrastructure overhead
* Simple API-based integration

## Roadmap

* Multi-token batch scanning
* Telegram & Discord alerts
* Browser extension
* Web UI dashboard

## Disclaimer

RugLens is an analytical interface built on RugPlay data and is not financial advice. Always verify independently.
