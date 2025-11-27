# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.3.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/4.2.0...4.3.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`effad64`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/effad6400dd6e30000c604ba6b972185dab99fd2)

## [4.2.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/4.1.0...4.2.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`54eb207`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/54eb207b835333c0f4f671a1e400a02cc4f17624)

## [4.1.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/4.0.0...4.1.0) - 2025-11-06

### Commits

- add oraclelinux10 support + lint and core fixes [`196f74f`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/196f74fbe476faf8a534a1a82ec828b824abcf83)

## [4.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/3.1.0...4.0.0) - 2025-10-29

### Commits

- fix debian13 rsyslog conf [`aa33015`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/aa33015eb9b33c656cb4abd1a8e41a539d86ef45)
- update core, molecule + gitlab-ci [`6ac4835`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/6ac48350dc8a521fdbc5d3183bfe67a4bd117424)
- changes on molecule [`e27fca2`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/e27fca292937720fa61bba4969465a2f9a3c4b50)
- changes on molecule [`1e60087`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/1e6008794c853da6c100af777db28a909f3f972f)
- initial commit [`a758965`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/a7589659b670feaf4062209184056a2ab58e71e9)
- fix lint [`9564ac8`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/9564ac8d75469efc7444aca7daac1a475e52bb77)
- update template [`6ad8e05`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/6ad8e05e16286e3045f3c144a3a3112ae8732c5a)
- update template [`2b428d2`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/2b428d2878b8727e17a18a9e36de0d1375eeba81)
- fix molecule paralelism and little updates [`1187eed`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/1187eedac2d72f38a7d2263788c567b9e5e4242a)

## [3.1.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/3.0.0...3.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`c52c087`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/c52c087955ce24c402aa4791b3510fd2ebb32afb)
- add ufw ack ignore file [`3f69b8b`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/3f69b8be46ec5642cbba13b31b3662fba2158d70)
- add version on molecule play image to maintain support on old release [`6479b7a`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/6479b7ab6253c86ed681e30aa6f7136e82813127)
- remove support for debian10 / ubuntu18 / redhat8 [`7ab48de`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/7ab48dee5ebfde9346c3cda738ffb43a20a294bc)
- update molecule [`565ba26`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/565ba260ff8c9a27ca3688cd38b5576012551756)
- add redhat 9 to default supported distrib [`28bd224`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/28bd224ade77039654b1e1f2fb6019c3daa35799)
- fix redhat8 repo [`4221aa1`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/4221aa124e969ca9da6d007fe91680fe20fedd71)
- remove redhat molecule checks [`96e7188`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/96e718843bf39e8a382beba4ddf2073a9af7d120)
- sort testing distrib to avoid random changes [`f3246cd`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/f3246cd9fe9470fccca8d830fd9ea9783b9a8e09)
- update pre-commit and lint fix [`53edf09`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/53edf0953b4ae4441ca3b608d27a39da5400028f)

## [3.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/2.1.0...3.0.0) - 2023-09-25

### Commits

- update vars [`fa79382`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/fa793828b5564b007e9c740e5a143234994294a1)
- remove precommit gitlab [`16c8bbb`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/16c8bbb523d7a7296408cfb9eb8e13778d955156)
- update readme + precommit + include vars [`45c91b2`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/45c91b227329a4ba90af4fd4bc8d98e19a4f47ca)
- add ansible comment on template files [`05d76b2`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/05d76b2c28c40d18212ea332dad480259633dd4b)
- update molecule playbook order and main include vars [`7eac3dc`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/7eac3dc4e249b15f3e2bd9d10afa415ce7ca43a8)
- update forward options vars [`54b121e`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/54b121e358dfe6a6f72c77a84a2a0430a6d33e25)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/1.0.0...2.0.0) - 2023-06-14

### Commits

- add debian12 support [`561b516`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/561b516dcff1445baaf539578ebc37738cca73cd)
- remove vars files [`e823251`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/e823251c8ea2d1ab167121f3fbe2fe6f7afda0d4)
- change default perm on files [`41b9311`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/41b931187359cdac6cd47d5b78e4e2da6da773c1)
- review rsyslog.conf to default config [`55aa462`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/55aa462d3837126249db7b36e41a48936ccb09c3)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/0.4.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`f3fe936`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/f3fe9362ba5eb74f0350d7a07fe4fb344dd54ca3)
- add precommit for lint [`7d034a3`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/7d034a3a166f9b9c070924bf922c1529f646d28a)
- fix checks [`e9dbf65`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/e9dbf65652c4ec0103c91e5f48ba3e0cc7eecd77)
- add new molecule all scenario [`411be43`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/411be43e61cbb03b842c627f763c0f007effb045)
- split distro for molecule tests on ci [`a367ae1`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/a367ae13eb611c80868e31b9a08489265732aafa)
- change default rules [`47d869d`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/47d869dd596cfd83058994324b15d87e276d72bb)
- add molecule fix for ora9 [`c9993a5`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/c9993a500de5e9f6c64c5ae1f426d34e8d852106)
- add ora9 support [`f768530`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/f76853075cea012d29a72504fa2cb09af70e113b)
- fix checks [`b7f5a43`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/b7f5a4370e725c2630e863c801c2bf1a2c1af3f9)
- add traditionalfileformat optional [`9904bbc`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/9904bbc8f628194f6a4b0390876813ae819e8273)

## [0.4.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/0.3.0...0.4.0) - 2022-07-15

### Commits

- fix test and pipeline [`9f56965`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/9f56965da2fc26a4a778d8e08638ae0133b14048)
- change verify on molecule [`4576cd1`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/4576cd1f5740246614c5e32f3ee447e900b7fa89)
- fix: change dnf to yum for redhat install to support major 7 [`b6fd7ff`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/b6fd7ff79f07e13da40d74adc3134f361e1090e0)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`ab33f58`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/ab33f580860fafa6ee8733362b8a6b26dab08b0f)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/0.1.1...0.2.0) - 2022-06-27

### Commits

- minor: add oracleLinux support + little fixes [`68f82fa`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/68f82fa4f2b3b78ecf843078d687795a9d5dfa48)
- fix: add variables on default config [`67f2e4d`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/67f2e4da926261a314219c21b000d99b2ad1dd7c)
- fix: changes yes to true vars and changes container names on molecule [`500e728`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/500e728177211c4d170db78bcffd5dc50dc39373)
- fix: remove unsupported centos8 [`72c9496`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/72c9496c9bbba91bd8f2b242f2238abf46471f96)

## [0.1.1](https://github.com/lotusnoir/ansible-apps_rsyslog/compare/0.1.0...0.1.1) - 2021-11-17

### Commits

- fix: Changes on README + molecule container names [`de597b6`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/de597b6e15005eda5523ddb9694bff685f7e7da1)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`7b48320`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/7b4832062802507492d030b17280f8d42c8b681b)
- minor: add changelog + automatic files checks [`cccd599`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/cccd5997c7df823f1b027112d808dcd65ae7ef6d)

## 0.1.0 - 2021-11-05

### Commits

- initial commit [`dae7c89`](https://github.com/lotusnoir/ansible-apps_rsyslog/commit/dae7c897f54146e1d022dc641bba73c130b8d1ed)
