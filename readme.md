# 仓库简介

开发者将开源软件工具、开源应用和开源组件与华为云对象存储OBS、数仓DWS、云容器CCE等云服务对接，同时基于Terraform模板，上架到华为云云商店，支持其他开发者一键部署使用开源组件 ，我们称为“开源xxx for HuaweiCloud”。
参与贡献的开发者将有计划会获得华为云开源政策支持，如果您有意愿参与，请在issues留下您的邮箱或者主动发送到邮件到hwcdtse@huawei.com，我们会尽快联系您，感谢关注！



# 项目总览

## Java

| 仓库                                                         | 简介                                                         | Committer                                       | 状态   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- | ------ |
| [Huawei-Presto](https://gitee.com/HuaweiCloudDeveloper/obs-presto-plugin) | 本项目将基于Presto的扩展式connector机制，完成对华为云OBS，DataArts，DWS的支持 | [ysxyao](https://gitee.com/ysxyao)              | 开发中 |
| [Huawei-Logstash](https://gitee.com/HuaweiCloudDeveloper/obs-logstash-plugins) | 利用Logstash的数据源扩展机制，使Logstash可以使用OBS作为输入，输出数据源 | [peng](https://gitee.com/pengcss)               | 完成   |
| [Huawei-Jenkins](https://gitee.com/HuaweiCloudDeveloper/obs-jenkins-plugins) | jenkins对接华为云OBS插件                                     | [zangxinshan](https://gitee.com/zangxinshan)    | 开发中 |
| [Huawei-Flink](https://gitee.com/HuaweiCloudDeveloper/obs-flink-plugins) | 利用flink的扩展机制，对接华为云 OBS，DLI，CDM等服务。        | [@xfanonymous](https://gitee.com/xfanonymous)   | 开发中 |
| [Huawei-Datax](https://gitee.com/HuaweiCloudDeveloper/obs-datax-plugins) | datax对接华为云OBS插件                                       | [鬼画符](https://gitee.com/mail_osc)            | 完成   |
| [Huawei-Druid](https://gitee.com/HuaweiCloudDeveloper/obs-druid-plugins) | Druid对接OBS，DLI插件                                        | [鹧鸪](https://gitee.com/zhegu123)              | 待分配 |
| [Huawei-Kettle](https://gitee.com/HuaweiCloudDeveloper/Huawei-Kettle-plugins) | 提供OBS，DWS，CDM，DLI，SMN，DataArts等云服务插件扩展        | [acewuye](https://gitee.com/acewuye)            | 待分配 |
| [Huawei-NiFi](https://gitee.com/HuaweiCloudDeveloper/huawei-nifi-bundle) | 提供OBS，DWS，CDM，DLI，SMN，DataArts等云服务插件扩展        | [招财猫](https://gitee.com/li-lianglong_admin)  | 开发中 |
| [Huawei-Sqoop](https://gitee.com/HuaweiCloudDeveloper/huawei-sqoop-plugins) | Sqoop对接华为云OBS插件                                       | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Crate.io](https://gitee.com/HuaweiCloudDeveloper/huawei-crate.io-plugins) | Crate.io对接华为云OBS插件                                    | 待分配                                          | 待分配 |
| [Huawei-Heron](https://gitee.com/HuaweiCloudDeveloper/huawei-heron-plugins) | Heron对接华为云OBS插件                                       | 待分配                                          | 待分配 |
| [Huawei-Hudi](https://gitee.com/HuaweiCloudDeveloper/huawei-hudi-plugins) | Hudi对接华为云OBS，CES，NoSql，DataArts等云服务，进行代码扩展 | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Iceberg](https://gitee.com/HuaweiCloudDeveloper/huawei-iceberg-plugins) | Iceberg对接华为云OBS，Nosql，DataArts等云服务，进行代码扩展  | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Seatunnel](https://gitee.com/HuaweiCloudDeveloper/huawei-seatunnel-plugins) | Seatunnel对接华为云服务                                      | [ludihu](https://gitee.com/ludihu)              | 待分配 |
| [Huawei-Hazel IMDG](https://gitee.com/HuaweiCloudDeveloper/huawei-hazel-imdg-plugins) | Hazel对接华为云OBS，DLI，ECS等云服务                         | 待分配                                          | 待分配 |
| [Huawei-Zeppelin](https://gitee.com/HuaweiCloudDeveloper/huawei-zeppelin-plugins) | Zeppelin对接华为云服务                                       | 待分配                                          | 待分配 |
| [Huawei-Alluxio](https://gitee.com/HuaweiCloudDeveloper/huawei-alluxio-plugins) | Alluxio对接华为云OBS，DataArts等云服务                       | 待分配                                          | 待分配 |
| [Huawei-Beam](https://gitee.com/HuaweiCloudDeveloper/huawei-beam-plugins) | Beam对接华为云OBS，Nosql，DMS，SMN，DLI等云服务              | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Storm](https://gitee.com/HuaweiCloudDeveloper/huawei-storm-plugins) | Beam对接华为云DataArts                                       | 待分配                                          | 待分配 |
| [Huawei-GoCD](https://gitee.com/HuaweiCloudDeveloper/huawei-go-cd-plugins) | GoCD对接华为云OBS，ECS等云服务                               | 待分配                                          | 待分配 |
| [Huawei-Doris](https://gitee.com/HuaweiCloudDeveloper/huawei-doris-plugins) | Doris对接华为云OBS，DataArts，DWS等云服务                    | doris团队                                       | 开发中 |
| [Huawei-DolphinScheduler](https://gitee.com/HuaweiCloudDeveloper/huawei-dolphin-scheduler-plugins) | DolphinScheduler对接华为云OBS，DLI，DWS，CCE，MRS等云服务    | [Iuge](https://gitee.com/ChuangHuLiDeShuangYan) | 开发中 |
| [Huawei-Pulsar](https://gitee.com/HuaweiCloudDeveloper/huawei-pulsar-plugins) | Pulsar对接华为云OBS，DLI，DWS等云服务                        | momimi1234                                      | 开发中 |
| [Huawei-Druid](https://gitee.com/HuaweiCloudDeveloper/Huaweicloud-Druid-plugin) | Druid对接华为云OBS，DLI，RDS等云服务                         | 待分配                                          | 待分配 |



## Go

| 仓库                                                         | 简介                                      | Committer                         | 状态   |
| ------------------------------------------------------------ | :---------------------------------------- | --------------------------------- | ------ |
| [Huawei-Thanos](https://gitee.com/HuaweiCloudDeveloper/obs-thanos-plugins) | 本项目的目的是扩展Thanos，使其支持OBS存储 | [peng](https://gitee.com/pengcss) | 完成   |
| [Huawei-Vault](https://gitee.com/HuaweiCloudDeveloper/huawei-vault-plugins) | Vault对接华为云服务                       | [peng](https://gitee.com/pengcss) | 开发中 |



## Python

| 仓库                                                         | 简介                                                         | Committer                                    | 状态   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------- | ------ |
| [Huawei-Airflow](https://gitee.com/HuaweiCloudDeveloper/huawei-airflow-provider) | 提供OBS，DWS，CDM，DLI，SMN，DataArts等云服务插件扩展        | [chenweikai](https://gitee.com/chen_xuanwen) | 已完成 |
| [Huawei-Prefect](https://gitee.com/HuaweiCloudDeveloper/huawei-prefect-plugins) | Prefect对接华为云服务, 提供VPC，ECS，OBS，FunctionGraph，AS，BMS，DNS，ELB，NAT，安全组等云服务插件扩展 | 待分配                                       | 待分配 |
| [Huawei-Ansible](https://gitee.com/HuaweiCloudDeveloper/huawei-ansible) | Ansible对接华为云服务                                        | 待分配                                       | 待分配 |
| [Huawei-Emissary-Ingress](https://gitee.com/HuaweiCloudDeveloper/huawei-emissary-ingress) | Emissary-Ingress对接华为云服务                               | 待分配                                       | 待分配 |
| [Huawei-Cloud-Custodian](https://gitee.com/HuaweiCloudDeveloper/huawei-cloud-custodian) | Cloud-Custodian对接华为云服务                                | 待分配                                       | 待分配 |
| [Huawei-CDK8s](https://gitee.com/HuaweiCloudDeveloper/huawei-cdk8s) | CDK for Kubernetes(CDK8s)对接华为云服务                      | 待分配                                       | 待分配 |
| [Huawei-SaltStack](https://gitee.com/HuaweiCloudDeveloper/huawei-salt-stack) | SaltStack对接华为云服务                                      | 待分配                                       | 待分配 |
| [Huawei-Checkov](https://gitee.com/HuaweiCloudDeveloper/huawei-checkov) | Checkov对接华为云服务                                        | 待分配                                       | 待分配 |
| [Huawei-Kube-hunter](https://gitee.com/HuaweiCloudDeveloper/huawei-kube-hunter) | Kube-hunter对接华为云服务                                    | 待分配                                       | 待分配 |

## C & C++

| 仓库                                                         | 简介                                                         | Committer | 状态   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | --------- | ------ |
| [Huawei-Tensorflow](https://gitee.com/HuaweiCloudDeveloper/obs-tensorflow-plugins) | 本项目是在[TensorFlow I/O](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Ftensorflow%2Fio)添加对HuaweiCloud OBS的存储支持 | 待分配    | 待分配 |
| [Huawei-Clickhouse](https://gitee.com/HuaweiCloudDeveloper/obs-clickhouse-plugins) | clickhouse对接华为云OBS插件                                  | 待分配    | 待分配 |



## 其他

| 仓库                                                         | 简介                        | Committer | 状态   |
| ------------------------------------------------------------ | --------------------------- | --------- | ------ |
| [Huawei-Deepstream](https://gitee.com/HuaweiCloudDeveloper/huawei-deepstream-plugins) | Deepstream对接华为云OBS插件 | 梁剑      | 开发中 |
| [Huawei-Backstage](https://gitee.com/HuaweiCloudDeveloper/huawei-backstage-plugins) | Backstage对接华为云服务     | 袁俊波    | 开发中 |



[^备注]: 开发者可以通过issues和邮件认领状态为待分配的项目，社区确认后将有专人联系对接。