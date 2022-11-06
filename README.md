# Masayoshi Mizutani

![mizutani-photo](https://user-images.githubusercontent.com/605953/71606352-7036c780-2bb3-11ea-92d9-a07a84da76a7.jpg)

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.anuraghazra1.vercel.app/api?username=m-mizutani&show_icons=true&include_all_commits=true&count_private=true" alt="Bogdan's github stats" />
</a>

## Overview

Masayoshi Mizutani is a security engineer. In university, he was studying and researching about network-based intrusion detection system and malware analysis. After graduation, he worked for various projects, e.g. SIEM (Security Information & Event Manager) integration, SOC (Security Operation Center) Analyst. Now he is working to build security monitoring system, DevSecOps architecture and various security mechanism at Ubie inc (for <a href="https://ubie.app/">jp</a> / <a href="https://ubiehealth.com/">us</a>).

## ToC

- Experience
  - [Career](https://github.com/m-mizutani/#career)
  - [Education](https://github.com/m-mizutani/#education)
- [Open source activities]()
- [Presentations](https://github.com/m-mizutani/#presentations)
- [Publications](https://github.com/m-mizutani/#publications)
- [Contacts and Social Services](https://github.com/m-mizutani/#contacts-and-social-services)


## Experience

### Career

#### Security Engineer in Ubie Inc. (2021.9-)

- Product security engineering
- Design & implementation of authentication infrastructure in Ubie

#### Security Engineer in Cookpad Inc. (2017.11 - 2021.8)

- Design & Implementation of Security Monitoring System on AWS
  - Security log collection
    - [gsuite-log-exporter](https://github.com/m-mizutani/gsuite-log-exporter): Export G Suite audit logs and save them to AWS S3
    - [guardduty-log-forwarder](https://github.com/m-mizutani/guardduty-log-forwarder): Serverless Application of AWS GuardDuty Log Uploader to S3
    - [flowlogconf](https://github.com/m-mizutani/flowlogconf): Enable AWS flow logs for your all vpc
    - [aws-vpcflowlogs-parquet](https://github.com/m-mizutani/aws-vpcflowlogs-parquet): AWS Lambda based VPC Flow Logs converter to Parquet format
  - Security log search engine with Amazon Athena ( [detail](https://techlife.cookpad.com/entry/2019/11/21/073000) )
    - [minerva](https://github.com/m-mizutani/minerva): Security Log Search Engine
    - [strix](https://github.com/m-mizutani/strix): Web UI of minerva
  - Security alert detection
    - [rlogs](https://github.com/m-mizutani/rlogs): A framework to load remote log files in Go
- Deploy monitoring software and integration (e.g. Endpoint Detection & Response tool)
  - [falconstream](https://github.com/m-mizutani/falconstream): Event forwarder for CrowdStrike Falcon via API
  - [gofalcon](https://github.com/m-mizutani/gofalcon): CrowdStrike Falcon API client in Go
  - [aws-falcon-data-forwarder](https://github.com/m-mizutani/aws-falcon-data-forwarder): CrowdStrike Falcon log forwarder from falcon S3 bucket to your S3 bucket

#### Research Staff / Security Analyst in IBM Japan (2011.4 - 2017.10)
- Research Tokyo (2011.4-2015.3, 2016.10-2017.10)
  - Design and implementation of audit log management system
  - Develop extention and solution of integration for Security Information & Event Manager (QRadar)
  - Deploy Security Information & Event Manager into cloud environment
  - Develop system to collect security information of container system
- Security Operation Centor (2015.4-2016.9)
  - Detect and analyze security alerts and report to customer
  - Write biannual SOC trend analysis reports
  - Security operation improvement by automation and tool development

#### Engineer (Internship) in Internet Systems Consortium (2010.12-2011.3)

- Develop monitoring dashboard for Security Information Exchange

### Education

- Ph.D. in Media and Governance, 2010, Keio University
- Master of Media and Governance, 2008, Keio University
- Bachelor of Arts in Environment and Information Studies, 2006, Keio University

## Open source activities

Major own OSS repositories.

- Security
  - [Octovy](https://github.com/m-mizutani/octovy): [trivy](https://github.com/aquasecurity/trivy) based vulnerability management service
  - [triview](https://github.com/m-mizutani/triview): CLI tool to view [trivy](https://github.com/aquasecurity/trivy) DB
  - [falconstream](https://github.com/m-mizutani/falconstream): Event forwarder for [CrowdStrike Falcon](https://www.crowdstrike.jp/falcon-platform/)
  - [logptn](https://github.com/m-mizutani/logptn): Generate Log Format from real text-based log data
- Go language utilities
  - [goast](https://github.com/m-mizutani/goast): Go AST based static analysis tool with [Rego](https://www.openpolicyagent.org/docs/latest/policy-language/)
  - [goerr](https://github.com/m-mizutani/goerr): More contextual error handling in Go
  - [gots](https://github.com/m-mizutani/gots): Simple and easy, but tedious function set in Go.
  - [zlog](https://github.com/m-mizutani/zlog): Secure logger in Go to avoid output sensitive data in log
- CLI utility
  - [zenv](https://github.com/m-mizutani/zenv): Enhanced env command to set environment variable by various method
- OPA/Rego
  - [opac](https://github.com/m-mizutani/opac): Rego evaluation API for OPA server, local Rego file and in-memory Rego data
  - [opaq](https://github.com/m-mizutani/opaq): Generic inquiry tool to OPA server for CI process, such as GitHub Actions
  - [ghnotify](https://github.com/m-mizutani/ghnotify): General GitHub event notification tool to Slack with Open Policy Agent and Rego
  - [ghaudit](https://github.com/m-mizutani/ghaudit): CLI audit tool for GitHub organization with OPA/Rego
  - [regolint](https://github.com/m-mizutani/regolint): Custom Rego linter with policy written by Rego
- AWS
  - [vxcap](https://github.com/m-mizutani/vxcap): Capture and dump VXLAN encapsulated traffic
  - [golambda](https://github.com/m-mizutani/golambda): A suite of Go utilities for AWS Lambda functions to ease adopting best practices
- GCP
  - [fbdump](https://github.com/m-mizutani/fbdump): Dump a massive amount of Firebase Auth user records
- Network
  - [lurker](https://github.com/m-mizutani/lurker): Scalable security network sensor as low interaction honeypot
  - [goblin](https://github.com/m-mizutani/goblin): Packet capture & TCP session reset tool in C language
  - [dnshive](https://github.com/m-mizutani/dnshive): Gathering name resolution protocol traffic, such as DNS forward lookup query/result and show IP traffic based on looked up names
  - [packetmachine](https://github.com/m-mizutani/packetmachine): Fast network packet decoding library in C++

## Presentations

- 2022.8 [Policy as Code 入門](https://docs.google.com/presentation/d/1dk4l50A9G7L4wYRmnC-93CLw9cBLjoE1m_9zp4BNTt0/edit#slide=id.gc6f73a04f_0_0) in [セキュリティ・キャンプ2022](https://www.ipa.go.jp/jinzai/camp/2022/zenkoku2022_index.html)
- 2020.11 [リモートワークを支える 社内セキュリティ基盤の構築と運用](https://speakerdeck.com/mizutani/secueiry-for-wfh) in [Internet Week 2020](https://www.nic.ad.jp/iw2020/program/detail/#c15)
- 2020.10 [SOARによるセキュリティ監視業務の効率化とSecOps](https://speakerdeck.com/mizutani/soar-and-secops) in [CODE BLUE 2020](https://codeblue.jp/2020/talks/?content=talks_8)
- 2020.10 [Cookpad: Security Architecture to Monitor and Analyze Secure Logs using AWS](https://youtu.be/qN5-v4NlKac?did=ta_card&trk=ta_card) in [AWS This is My Architecture](https://aws.amazon.com/this-is-my-architecture/?nc1=h_ls&tma.sort-by=item.additionalFields.airDate&tma.sort-order=desc)
- 2020.1 [Amazon Athena を使った セキュリティログ検索基盤の構築](https://speakerdeck.com/mizutani/seclog-athena) in [ログ分析勉強会 vol.2](https://loganalytics.connpass.com/event/157354/)
- 2019.7 [AWS re:Inforce recap 2019](https://speakerdeck.com/mizutani/aws-re-inforce-recap-2019) in AWS re:Inforce 2019 re:Cap Seminar
- 2019.2 [スケーラブルなセキュリティ監視基盤の作り方](https://speakerdeck.com/mizutani/techconf2019-mizutani) in Cookpad TechConf 2019
- 2018.12 [Webサービス事業会社におけるEDRの検討と導入の事例](https://speakerdeck.com/mizutani/falconday201812) in 第4回 Falcon DAY
- 2018.12 [クックパッドのセキュリティログ検索基盤の紹介](https://speakerdeck.com/mizutani/security-log-search) in Scramble! #2 Security
- 2018.7 [オフィス・AWS環境をセキュリティ監視するためのログ収集](https://speakerdeck.com/mizutani/ohuisuawshuan-jing-wosekiyuritei-jian-shi-surutamefalserokushou-ji)
- 2018.5 [セキュリティログ分析基盤の構築 on AWS](https://speakerdeck.com/mizutani/sekiyuriteirogufen-xi-ji-pan-falsegou-zhu-on-aws) in Security JAWS 【第9回】

## Publications

- [AWS の This is My Architecture でS3を中心としたセキュリティログ基盤の紹介をしました](https://techlife.cookpad.com/entry/aws-tma-2019), 2020.12, Cookpad Developers' Blog
- [Trivy + AWSによるコンテナイメージ脆弱性検査パイプラインの構築](https://techlife.cookpad.com/entry/catbox), 2020.7, Cookpad Developers' Blog
- [サーバーレスで作るセキュリティアラート自動対応フレームワーク](https://techlife.cookpad.com/entry/2020/03/18/073000), 2020.3, Cookpad Developers' Blog
- [Amazon Athena を使ったセキュリティログ検索基盤の構築](https://techlife.cookpad.com/entry/2019/11/21/073000), 2019.11, Cookpad Developers' Blog
- [オフィス・AWS環境をセキュリティ監視するためのログ収集](https://techlife.cookpad.com/entry/2018/05/31/080000), 2018.5, Cookpad Developers' Blog
- Masayoshi Mizutani. システムログ書式の構造に着目したシステム異常検出手法の検討. IPSJ Computer Security Symposium 2018, 2018.
- Masayoshi Mizutani. [Method for estimating format of log message and computer and computer program therefor](https://patents.google.com/patent/US9858168B2). US9858168B2, 2018.
- IBM Tokyo SOC. [IBM Tokyo SOC 情報分析レポート 2016年下半期](https://www.ibm.com/blogs/tokyo-soc/wp-content/uploads/2017/04/tokyo_soc_report2016_h2.pdf). [Column4] コマンド&コントロールサーバーのドメイン名は いかにして悪用されるか, 2017.
- IBM Tokyo SOC. [IBM Tokyo SOC 情報分析レポート 2016年上半期](https://www.ibm.com/blogs/tokyo-soc/wp-content/uploads/2016/02/tokyo_soc_report2016_h1.pdf). [Column2] 2016年上半期におけるメールを利用した攻撃の変遷, 2016.
- IBM Tokyo SOC. IBM Tokyo SOC 情報分析レポート 2015年下半期. 2.3.2 今期確認された不特定多数を 狙ったメールを悪用する攻撃の検知状況, 3.2 Joomlaに対する攻撃, 2016.
- IBM Tokyo SOC. IBM Tokyo SOC 情報分析レポート 2015年上半期. [Column3] 攻撃元 IP アドレスからみる ShellShock 脆弱性を利用した攻撃の分析, 2015.
- IBM Tokyo SOC. IBM Tokyo SOC 情報分析レポート 2014年下半期. [Column3] ドメイン名ブラックリストの有効性, 2015.
- Masayoshi Mizutani. Incremental Mining of System Log Format. SCC ‘13 Proceedings of the 2013 IEEE International Conference on Services, 2013.
- Masayoshi Mizutani, Keiji Takeda, Jun Murai. An Analysis of Web Distributed Malwares and A Proposal of Their Detection Method. IEICE TRANSACTIONS Volume J92-B No.10, pp.1631-1642, 2009.
- Masayoshi Mizutani, Akira Kanai, Keiji Takeda, Jun Murai. A Malware Detection Method based on Communication Commonality – Implementation and Evaluation. IPSJ 2009. Vol.50 No.9, 2009.
- Masayoshi Mizutani, Shin Shirahata, Masaki Minami, Jun Murai. The Design and Implementation of Session Based IDS. IEICE Transactions on Communications (Japanese Edition), IEICE, Vol.89, No.3, pp.46-58, 2005.

## Contacts and Social Services

- Mail: mizutani@hey.com
- Twitter: https://twitter.com/m_mizutani
- Mastodon: https://mstdn.jp/@m_mizutani
- Github: https://github.com/m-mizutani
- Dev: https://dev.to/mizutani
- Blog: https://mztn.hatenablog.com
- Google Scholar: https://scholar.google.co.uk/citations?user=pX7ttVoAAAAJ

NOTE: Contact me by email (mizutani@hey.com) or Twitter usually. Please mention about your favorite alchohol drink or sweet in the message if you want to talk for hiring purpose.
採用に関するお話につきましては、あなたの好きなお酒かお菓子の話を添えてメールをお送りください
