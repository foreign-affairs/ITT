## False Positives

We understand being listed on a Phishing Database like this can be frustrating
and embarrassing for many web site owners. The first step is to remain calm.
The second step is to rest assured one of our maintainers will address your
issue as soon as possible.

Please make sure you have provided as much information as possible to help
speed up the process.

### Send a Pull Request for faster removal

Users who understand git can creat a Pull Requests, an assist us for faster
removals by sending a PR to the manual repository of 
[Mitchell Krogza Phishing + Whitelist][MP] repository and add the FP domain
one of the whitelists:

  - [falsepositive.list][MPFL] matches `1 on 1`
  - [falsepositive_regex.list][MPFLRGX] matches against regex.
  - [falsepositive_rzd.list][MPFLRZD] This list will tell the system to 
    explicitly check for the given string plus all possible TLD.

Please include the same information as above to help speed up the whitelisting
process.

You should note that you should not expect merges are done in [MP] until
the issue have been solved here, this is because those who can merge do
not have access to the logs for why your domain got listed.

## Open Source Project domain reporting tools'
My Privacy DNS have 2 option for you to quickly add new phishing domains:

1. By using the web, support anonymously reporting: [My Privacy DNS Webreporter][MyPDNSR]    
2. By installing one of the cool [Firefox add-ons, GUI, CLI tools][MYPDNSFF]


[MP]: https://github.com/mitchellkrogza/phishing "Mitchell Krogza Phishing + Whitelist"
[MPFL]: https://github.com/mitchellkrogza/phishing/blob/main/falsepositive.list
[MPFLRGX]: https://github.com/mitchellkrogza/phishing/blob/main/falsepositive_regex.list
[MPFLRZD]: https://github.com/mitchellkrogza/phishing/blob/main/falsepositive_rzd.list
[MyPDNSR]: https://mypdns.eu.org/matrix/reporter/ "My Privacy DNS Webreporter"
[MYPDNSFF]: https://0xacab.org/my-privacy-dns/matrix/-/blob/master/tools/client_addon.md "My Privacy DNS Firefox Add-ons for easy domain reporting"
