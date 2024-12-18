<!-- TOC -->
  * [Phishing domain(s)](#phishing-domains)
  * [Q&A](#qa)
  * [False Positives](#false-positives)
      * [Please do also notify](#please-do-also-notify)
  * [Create a Pull Request for faster handling](#create-a-pull-request-for-faster-handling)
  * [Bug reporting](#bug-reporting)
  * [Document revision](#document-revision)
<!-- TOC -->

## Phishing domain(s)
If you would like to report a single or a bunch of phishing, there are a
coupe of options, but none of them goes into this repository.

Therefore, we recommending you to report to following projects:

Among the most solid and reliable projects you can report to is:

1. [Mitchell Krogza Phishing + Whitelist][PD]
2. [My Privacy DNS][MYPDNS]
3. Phistank
4. OpenPhish

## Q&A

Q: Why are you recommending these projects over others?

A: Well Let's be honest, @spirillen are among the moderators on PD's
**Phishing** and **My Privacy DNS** projects and probably the most active and
online avatar on both blacklists.

While both @funilrys and @mitchellkrogza are all GitHub and less active online.

If you ask me (@spirillen) I would go for [My privacy DNS][MYPDNS] when
it comes for reporting any item to be blacklisted, while for whitelisting
(Not FalsePositives) your should 100% go for
[Mitchell Krogza Phishing + Whitelist][PD].

For reporting false-positive you should absolutely ensure all projects, mentioned
above, get informed.

## False Positives

We understand being listed on a Phishing Database like this one can be 
frustrating and embarrassing for many domain owners. The first step is to 
remain calm.

The second step is to rest assured, one of our maintainers will address your
issue as soon as possible.

To speed up the handling of your issue, do fill out the issue template in 
full, and please make sure you have provided as much information as possible 
to help speed up the process. If information are left out, your issue might 
become stalled as unimportant and in time closed without any other handling 
on your problem.

#### Please do also notify

You should please also inform [My Privacy DNS][MYPDNS], as they maintain the 
big "Why" library, for any blacklisted domains.

## Create a Pull Request for faster handling

Users who understand git, can creat a Pull Requests, an assist us for faster
removals by sending a PR to the manual repository [Mitchell Krogza Phishing 
+ Whitelist][PD] and add the FP domain one of the whitelists:

  - [falsepositive.list][PDFL] matches `1 on 1`
  - [falsepositive_regex.list][PDFLRGX] matches against regex.
  - [falsepositive_rzd.list][PDFLRZD] This list will tell the system to 
    explicitly check for the given string plus all possible TLD.

Please include the same information as above to help speed up the whitelisting
process.

> [!NOTE]
> You should note that you can not expect merges are done in
> [Mitchell Krogza Phishing + Whitelist][PD] until any issue have been solved
> here, this is because those who can merge do not have access to the logs for
> why your domain got listed.

## Bug reporting
When you are commiting bug reports please be as precise as possible and narrow
down the issue as much as you possible can.

If you have any questions regarding one of the PD's phishing or phishing DB
projects, please either just ask in the Bug report issue template and change
the title to `[Question]`


[//]: # (URI list)

[PD]: https://github.com/Phishing-Database/phishing "Mitchell Krogza Phishing + Whitelist"
[PDFL]: https://github.com/Phishing-Database/phishing/blob/main/falsepositive.list
[PDFLRGX]: https://github.com/Phishing-Database/phishing/blob/main/falsepositive_regex.list
[PDFLRZD]: https://github.com/Phishing-Database/phishing/blob/main/falsepositive_rzd.list
[MYPDNS]: https://www.mypdns.org/ "My Privacy DNS Let no one spy on you online"
[MyPDNSR]: https://mypdns.eu.org/matrix/reporter/ "My Privacy DNS Webreporter"
[MYPDNSFF]: https://0xacab.org/my-privacy-dns/matrix/-/blob/master/tools/client_addon.md "My Privacy DNS Firefox Add-ons for easy domain reporting"
[MYPDNSTL]: https://github.com/mypdns/matrix/blob/master/README.md "My Privacy DNS easy issue commiting tools"

## Document revision

This is revision 0.2b

Last updated by @spirillen changed 18th of December 2024
