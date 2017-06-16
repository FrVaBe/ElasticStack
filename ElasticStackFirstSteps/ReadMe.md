# Open Source Elastic Stack First Steps

## Preface

This document is about my first steps with the _Elastic Stack_ which I attend to use for the management of logging data. The most important reason for this document is the documentation of the setup work I did (and the pitfalls) and not the introduction to the Elastic Stack.

Thus to understand this document you should know about the basic concepts of the Elastic Stack and its components. You can find a lot of information on these topics in the links I provided below.

## Documentation

When it comes to dealing with a new technology, I always like to read some basic concepts about the technology first - before trying out the first application examples. 

Fortunately the Elastic Stack is well documented. These are the links I used a lot

* [Open Source Elastic Stack](https://www.elastic.co/products) product start page
  * [Elasticsearch](https://www.elastic.co/products/elasticsearch) - The Heart of the Elastic Stack ([RefDoc](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html))
  * [Logstash](https://www.elastic.co/products/logstash) - Centralize, Transform & Stash Your Data ([RefDoc](https://www.elastic.co/guide/en/logstash/current/index.html))
  * [Kibana](https://www.elastic.co/products/kibana) - Your Window into the Elastic Stack ([RefDoc](https://www.elastic.co/guide/en/kibana/current/index.html))
  * [X-Pack](https://www.elastic.co/products/x-pack) - One Pack. Loads of Possibilities. ([RefDoc](https://www.elastic.co/guide/en/x-pack/current/index.html))
  * [Beats](https://www.elastic.co/products/beats) - Lightweight Data Shippers ([RefDoc](https://www.elastic.co/guide/en/beats/libbeat/current/index.html))
    * [Filebeat](https://www.elastic.co/products/beats/filebeat) - Lightweight Shipper for Logs ([RefDoc](https://www.elastic.co/guide/en/beats/filebeat/current/index.html))

The product entry pages provide some overview information and on my first visit I wondered where to find the reference (product) documentation. Once noticed it is really obvious. Each product page has a litte link bar at the right side with _Docs_, _Forum_ and _GitHub_ links (seel below).

![Elasticsearch product page](img/ElasticsearchProductPage.png)

## Start / Installation

I did my first steps on Windows and the installation was mostly about extracting the archives and - after configuration - starting a batch script.

So please take a look at the [Get Started](https://www.elastic.co/start) page which will guide you through the downloads of all Elastic Stack components and follow the installation instructions of the each component as described in their reference documentation (see links above)

