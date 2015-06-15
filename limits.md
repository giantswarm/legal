# Quotas and Limits

In general, we currently allow

* an unlimited number of applications
* an unlimited number of services per application
* an unlimited number of components per service

However, we enforce these restrictions:

* any application older than 7 days (from creation time) will be deleted
  * except if you have configured any [custom domain name](https://docs.giantswarm.io/reference/swarm-json/#own-domain-name)
* a maximum of 10 instances (containers) per component
* a memory (RAM) limit of 512 MB per instance (container)
* a storage size limit of 100 GB per volume
* a log retention time limit of 14 days

Please [contact us](/contact/) if you have any questions regarding this.
