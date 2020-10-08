﻿# What is RudderStack?

**Short answer:** 
Rudder is an open-source Segment alternative written in Go, built for the enterprise. .

**Long answer:** 
Rudder is a platform for collecting, storing and routing customer event data to dozens of tools. Rudder is open-source, can run in your cloud environment (AWS, GCP, Azure or even your data-centre) and provides a powerful transformation framework to process your event data on the fly.

## Getting Started with Python SDK

Install `rudder-sdk-python` using `pip`
```
pip install rudder-sdk-python
```

## Initialize the ```Client```
```
import rudder_analytics

rudder_analytics.write_key = <WRITE_KEY>
rudder_analytics.data_plane_url = <DATA_PLANE_URL>
```

## Send Events
```
rudder_analytics.track('developer_user_id', 'Simple Track Event', {
  'key1': 'val1'
})
```

## Contact Us
If you come across any issues while configuring or using RudderStack, please feel free to [contact us](https://rudderstack.com/contact/) or start a conversation on our [Discord](https://discordapp.com/invite/xNEdEGw) channel. We will be happy to help you.
