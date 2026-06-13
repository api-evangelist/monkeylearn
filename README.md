# MonkeyLearn

Machine learning text analysis platform with REST APIs for sentiment analysis, keyword extraction, topic classification, and custom ML model training on text data. MonkeyLearn was acquired by Medallia in February 2022 and its capabilities are now part of the Medallia experience management platform.

## API

The MonkeyLearn REST API v3 (`https://api.monkeylearn.com/v3/`) provides two primary resource types:

- **Classifiers** (`/v3/classifiers/{model_id}/classify/`) — analyze whole texts and assign categories, sentiments, or topics
- **Extractors** (`/v3/extractors/{model_id}/extract/`) — identify and extract named entities, keywords, and other structured information from text

Authentication uses token-based headers: `Authorization: Token YOUR_API_KEY`.

Official SDKs are available for Python, Ruby, Node.js, PHP, and Java. All SDKs include built-in auto-batching (up to 200 texts per request) and automatic throttle retry handling.

## Links

- **Website:** https://monkeylearn.com/
- **Documentation:** https://monkeylearn.com/api/
- **GitHub:** https://github.com/monkeylearn
- **Blog:** https://monkeylearn.com/blog/
- **Pricing:** https://monkeylearn.com/pricing/
- **Status:** https://status.monkeylearn.com/
- **X (Twitter):** https://twitter.com/monkeylearn
- **LinkedIn:** https://www.linkedin.com/company/monkeylearn

## APIs.json

This repository contains an APIs.json 0.19 profile for MonkeyLearn maintained by [API Evangelist](https://apievangelist.com).
