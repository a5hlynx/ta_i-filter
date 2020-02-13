# Add-on for i-Filter

Add-on to interpret Digital Arts' i-Filter access log. Compatible with i-Filter ver 8 and 9.

# Installation

1. Logon to your Splunk and go to "Manage Apps".
2. Click either "Install app from file" or "Browse more apps".
3. "Install app from file"
  * Upload this app's tar.gz, which you should have gotten either from splunkbase or github beforehand.
4. "Browse More Apps"
      * Search this app using the keywords like "i-Filter" to find "Add-on for i-Filter", and then follow the instruction shown in the modal.

# Usage

## Ingest access logs

Just specify either i-filter:v8 or i-filter:v9 as sourcetype depending on the i-Filter version in ingesting its access logs.


## Generate sample logs

The Add-on automatically generates i-Filter access logs in both ver 8 and 9 if [Eventgen](https://splunkbase.splunk.com/app/1924/) is installed and enabled on your Splunk. The generated data is indexized into main by default, which can be changed by modifying eventgen.conf. See also [Eventgen Documentation](http://splunk.github.io/eventgen/).
