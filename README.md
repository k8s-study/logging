<div align="center">
  <a href="https://github.com/k8s-study/logging" title="Logging in Kubernetes">
    <img alt="Logging in Kubernetes" src="http://arveknudsen.com/wp-content/uploads/2017/07/logo_with_border-1024x994.png" width="240px" />
  </a>
  <br />
  <h1>Logging in Kubernetes</h1>
</div>

<p align="center">
  Document to describe how to centrally gather the microservices's log data in k8s-study's Kubernetes cluster.
</p>

<div align="center">
  <a href="https://opensource.org/licenses/mit-license.php">
    <img alt="MIT Licence" src="https://badges.frapsoft.com/os/mit/mit.svg?v=103" />
  </a>
  <a href="https://github.com/ellerbrock/open-source-badge/">
    <img alt="Open Source Love" src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" />
  </a>
</div>

<br />

**This** is a highly opinionated logging method for Kubernetes cluster.

This method has the following logging pipeline:

- Filebeat
- Logstash
- Elasticsaerch
- Kibana

---


## Getting Started

To be updated.
```zsh
$ git clone https://github.com/k8s-study/logging
$ cd logging
```


## Tech Stack

- [Filebeat](https://www.elastic.co/products/beats/filebeat) - Easily ship log file data to Logstash and Elasticsearch to centralize your logs.
- [Logstash](https://www.elastic.co/products/logstash) - The central dataflow engine in the Elastic Stack for gathering, enriching, and unifying all of your data regardless of format or schema.
- [Elasticsearch](https://www.elastic.co/products/elasticsearch) - A search engine based on Lucene. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents.
- [Kibana](https://www.elastic.co/products/kibana) - An analytics and visualization platform designed to work with Elasticsearch.


## References

### Logging in Docker

- [Kubernetes: Logging Architecture](https://kubernetes.io/docs/concepts/cluster-administration/logging/)

### ELK Stack

- [AWS ELK Best Practices](https://www.elastic.co/guide/en/elasticsearch/plugins/current/cloud-aws-best-practices.html)
- [Elasticsearch: The definitive guide](https://www.elastic.co/guide/en/elasticsearch/guide/current/index.html)
- [Logstash: Do you grok grok?](https://www.elastic.co/blog/do-you-grok-grok)


## Contributing

This project follows the [**Contributor Covenant**](http://contributor-covenant.org/version/1/4/) Code of Conduct.

#### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/k8s-study/logging/issues) to report any bugs or ask feature requests.


## License

Provided under the terms of the [MIT License](https://github.com/k8s-study/logging/blob/master/LICENSE).

Copyright © 2018, [Byungjin Park](http://www.posquit0.com).
