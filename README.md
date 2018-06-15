# cheatsheet-uaac-A4
Cloudfoundry UAAC CheatSheets In A4

<a href="https://github.com/DennyZhang?tab=followers"><img align="right" width="200" height="183" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/fork_github.png" /></a>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[![LinkedIn](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/linkedin_icon.png)](https://www.linkedin.com/in/dennyzhang001) <a href="https://www.dennyzhang.com/slack" target="_blank" rel="nofollow"><img src="http://slack.dennyzhang.com/badge.svg" alt="slack"/></a> [![Github](https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/github.png)](https://github.com/DennyZhang)

File me [tickets](https://github.com/DennyZhang/cheatsheet-uaac-A4/issues) or star [the repo](https://github.com/DennyZhang/cheatsheet-uaac-A4).

Printable version on A4 page: [cheatsheet-uaac-A4.pdf](cheatsheet-uaac-A4.pdf)

<a href="https://www.dennyzhang.com"><img align="right" width="185" height="37" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>

See more CheatSheets from Denny: [here](https://github.com/topics/denny-cheatsheets)

- Common Commands

| Name              | Command                                                                        |
| :--------------   | -----------------------------------------------------------------------------  |
| Run command       | `uaac apt-install ruby ruby-dev build-essential rubygems; gem install uaac-cf` |
|                   | `uaac target https://$domain_name:$port --skip-ssl-validation`                 |
| Get token         | `uaac token client get admin -s sg-xxx`                                        |
| Add user          | `uaac user add $username --emails $email -p $password`                         |
| Add user to group | `uaac member add $user $group`                                                 |
| Get user          | `uaac user get pks-admin`                                                      |

<a href="https://www.dennyzhang.com"><img align="right" width="201" height="268" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/denny_201706.png"></a>

<a href="https://www.dennyzhang.com"><img align="right" src="https://raw.githubusercontent.com/USDevOps/mywechat-slack-group/master/images/dns_small.png"></a>
# License
- Code is licensed under [MIT License](https://www.dennyzhang.com/wp-content/mit_license.txt).
