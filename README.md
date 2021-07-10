# Cisco ESA Mailtext
----

The purpose of this pack is to provide extensive regex extraction for Cisco ESA mailtext logs. By definition ESA mailtext logs tend to be very verbose with small event sizes. This pack provides a comprehensive fields extraction. At the end of the pipeline, we suggest some events to drop, but you need to match this to your needs. Using the example sample file we are able to achieve 14% reduction



## Pack details:

* 1.**Pipelines**: cisco_esa_mailtext.
* 2.**Samples**: Cisco_ESA_mailtext_clean_sample.log (1000 event sanitized version of real-world example)
* 3.**Routes**: None included. Should match your target destination in production


The following **lookup** files are included in the pipeline for further use:
* cisco_esa_email_action_lookup.csv
* cisco_esa_proxy_status_action_lookup.csv
* cisco_esa_authentication_action_lookup.csv
* cisco_esa_vendor_info_lookup.csv

Before you begin, ensure that you have met the following requirements:

* Bullet point one showing example of formatted `monospaced text`.
* Bullet point two showing examples of formatted _italic_ and **bold** text


## Vendor documentation

Further details on the vendor log format can be found here: <https://www.cisco.com/c/en/us/td/docs/security/esa/esa11-1/user_guide/b_ESA_Admin_Guide_11_1/b_ESA_Admin_Guide_chapter_0100110.html>


```
example of a code block here
```

## Using The Pack

To use install this Pack, follow the normal PACKS installation instructions in this link: <https://docs.cribl.io/docs/packs#controls>




## Release Notes

### Version 0.0.1 - 2021-07-08
Initial releaase!





## Contact
Pack developer email <mo@cribl.io>.


## License
This Pack uses the following license: [`<Apache 2.0>`](https://www.apache.org/licenses/LICENSE-2.0).
