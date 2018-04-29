# redirection-banned
很多时候，出于某些原因，我们会在站点上实施站内跳转政策，或是搭建一个短链平台。然而由于有时没有对跳转目标做出限制，这些平台会可能会被利用来进行恶意跳转。

这个项目旨在收集一些在跳转时应多加注意的域名，以防受到牵连的惩罚。

本项目中的域名区分子域和根域，即 `root.com` 和 `subdomain.root.com` 可能会同时出现。

## 来源申明
`hostnames.txt` 中的域名收集自投向 WordPress 的垃圾评论；

`shortlinks.txt` 中的域名为常见短链接服务域名，收集自互联网公开信息；

`tmp-mail.txt` 中的域名为常见临时邮箱服务域名，来自 [neoFelhz/various_domain_list](https://github.com/neoFelhz/various_domain_list/)

## 误判声明
`hostnames.txt` 中的域名为程序自动收集，原则上不再进行 Review ；对于不认可的可以提出 issue。

`shortlinks.txt` 和 `tmp-mail.txt` 不接受任何不认可意见。

## 帮助这个项目
你可以通过提出 PR 来帮助本项目。在提出 PR 之前请仔细检查提交的域名。
