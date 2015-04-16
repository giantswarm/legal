# Quotas and Limits

In general, we currently allow

* an unlimited number of applications
* an unlimited number of services per application
* an unlimited number of components per service

However, we enforce these restrictions:

* any application older than 7 days (from creation time) needs a custom domain name to keep running, otherwise it will be deleted
* a maximum of 10 instances (containers) per component
* a memory (RAM) limit of 512 MB per instance (container)
* a storage size limit of 100 GB per volume

Please [contact us](/contact/) if you have any questions regarding this.
