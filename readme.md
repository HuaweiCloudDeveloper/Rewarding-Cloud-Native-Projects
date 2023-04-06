# 仓库简介

开发者将开源软件工具、开源应用和开源组件与华为云对象存储OBS、数仓DWS、云容器CCE等云服务对接，同时基于Terraform模板，上架到华为云云商店，支持其他开发者一键部署使用开源组件 ，我们称为“开源xxx for HuaweiCloud”。
参与贡献的开发者将有计划会获得[华为云沃土云创计划](https://developer.huaweicloud.com/programs/dev-program.html)激励，如果您有意愿参与，请在issues留下您的邮箱或者主动发送到邮件到hwcdtse@huawei.com，我们会尽快联系您，感谢关注！



# 项目总览
## Dromara社区

| 仓库                                                         | 简介                                                         | Committer                                       | 状态   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- | ------ |
| [Hertzbeat](https://gitee.com/dromara/hertzbeat) | 完成对华为云OBS，GaussDB For Influx，SMN，EulerOS，CCE，DataArts，DWS的支持 | [tomsun28](https://gitee.com/tomsun28)              | 开发中 |
| [Jpom](https://gitee.com/dromara/Jpom) | 完成对华为云OBS，ECS，GaussDB，SMN，FunctionGraph，CCE的支持 | [不忘初心](https://gitee.com/bwcx-jzy)              | 开发中 |
| [MaxKey](https://gitee.com/dromara/MaxKey) | 完成对华为云SMN的支持 | [MaxKeyTop](https://gitee.com/maxkeytop_admin)              | 开发中 |
| [Neutrino-Proxy](https://gitee.com/dromara/neutrino-proxy) | 完成对华为云EIP，DNS，ECS的支持 | [傲世孤尘](https://gitee.com/asgc)              | 开发中 |
| [Northstar](https://gitee.com/dromara/northstar) | 完成对华为云CSS，DWS的支持 | [Huangwl](https://gitee.com/kevinhuangwl)              | 开发中 |
| [Open-capacity-platform](https://gitee.com/dromara/open-capacity-platform) | 完成对华为云CSE，RDS，DCS，OBS，APM，AOM，LTS的支持 | [owen](https://gitee.com/jeecp)              | 开发中 |
| [Zyplayer-doc](https://gitee.com/dromara/zyplayer-doc) | 完成对华为云OBS，CSS的支持 | [暮光：城中城](https://gitee.com/zyplayer)              | 开发中 |

## Java

| 仓库                                                         | 简介                                                         | Committer                                       | 状态   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- | ------ |
| [Huawei-Presto](https://gitee.com/HuaweiCloudDeveloper/obs-presto-plugin) | 本项目将基于Presto的扩展式connector机制，完成对华为云OBS，DataArts，DWS的支持 | [ysxyao](https://gitee.com/ysxyao)              | 开发中 |
| [Huawei-Logstash](https://gitee.com/HuaweiCloudDeveloper/obs-logstash-plugins) | 利用Logstash的数据源扩展机制，使Logstash可以使用OBS作为输入，输出数据源 | [peng](https://gitee.com/pengcss)               | 完成   |
| [Huawei-Jenkins](https://gitee.com/HuaweiCloudDeveloper/obs-jenkins-plugins) | jenkins对接华为云OBS插件                                     | [zangxinshan](https://gitee.com/zangxinshan)    | 开发中 |
| [Huawei-Flink](https://gitee.com/HuaweiCloudDeveloper/obs-flink-plugins) | 利用flink的扩展机制，对接华为云 OBS，DLI，CDM等服务。        | [@xfanonymous](https://gitee.com/xfanonymous)   | 开发中 |
| [Huawei-Datax](https://gitee.com/HuaweiCloudDeveloper/obs-datax-plugins) | datax对接华为云OBS插件                                       | [鬼画符](https://gitee.com/mail_osc)            | 完成   |
| [Huawei-Druid](https://gitee.com/HuaweiCloudDeveloper/obs-druid-plugins) | Druid对接OBS，DLI插件                                        | [鹧鸪](https://gitee.com/zhegu123)              | 待分配 |
| [Huawei-Kettle](https://gitee.com/HuaweiCloudDeveloper/Huawei-Kettle-plugins) | 提供OBS，DWS，CDM，DLI，SMN，DataArts等云服务插件扩展        | [acewuye](https://gitee.com/acewuye)            | 开发中 |
| [Huawei-NiFi](https://gitee.com/HuaweiCloudDeveloper/huawei-nifi-bundle) | 提供OBS，DWS，CDM，DLI，SMN，DataArts等云服务插件扩展        | [招财猫](https://gitee.com/li-lianglong_admin)  | 开发中 |
| [Huawei-Sqoop](https://gitee.com/HuaweiCloudDeveloper/huawei-sqoop-plugins) | Sqoop对接华为云OBS插件                                       | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Crate.io](https://gitee.com/HuaweiCloudDeveloper/huawei-crate.io-plugins) | Crate.io对接华为云OBS插件                                    | 待分配                                          | 待分配 |
| [Huawei-Heron](https://gitee.com/HuaweiCloudDeveloper/huawei-heron-plugins) | Heron对接华为云OBS插件                                       | 待分配                                          | 待分配 |
| [Huawei-Hudi](https://gitee.com/HuaweiCloudDeveloper/huawei-hudi-plugins) | Hudi对接华为云OBS，CES，NoSql，DataArts等云服务，进行代码扩展 | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Iceberg](https://gitee.com/HuaweiCloudDeveloper/huawei-iceberg-plugins) | Iceberg对接华为云OBS，Nosql，DataArts等云服务，进行代码扩展  | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Seatunnel](https://gitee.com/HuaweiCloudDeveloper/huawei-seatunnel-plugins) | Seatunnel对接华为云服务                                      | 待分配              | 待分配 |
| [Huawei-Hazel IMDG](https://gitee.com/HuaweiCloudDeveloper/huawei-hazel-imdg-plugins) | Hazel对接华为云OBS，DLI，ECS等云服务                         | 待分配                                          | 待分配 |
| [Huawei-Zeppelin](https://gitee.com/HuaweiCloudDeveloper/huawei-zeppelin-plugins) | Zeppelin对接华为云服务                                       | 待分配                                          | 待分配 |
| [Huawei-Alluxio](https://gitee.com/HuaweiCloudDeveloper/huawei-alluxio-plugins) | Alluxio对接华为云OBS，DataArts等云服务                       | 已完成                                          | 已完成 |
| [Huawei-Beam](https://gitee.com/HuaweiCloudDeveloper/huawei-beam-plugins) | Beam对接华为云OBS，Nosql，DMS，SMN，DLI等云服务              | [鬼画符](https://gitee.com/mail_osc)            | 开发中 |
| [Huawei-Storm](https://gitee.com/HuaweiCloudDeveloper/huawei-storm-plugins) | Storm对接华为云DataArts                                       | 待分配                                          | 待分配 |
| [Huawei-Doris](https://gitee.com/HuaweiCloudDeveloper/huawei-doris-plugins) | Doris对接华为云OBS，DataArts，DWS等云服务                    | doris团队                                       | 开发中 |
| [Huawei-DolphinScheduler](https://gitee.com/HuaweiCloudDeveloper/huawei-dolphin-scheduler-plugins) | DolphinScheduler对接华为云OBS，DLI，DWS，CCE，MRS等云服务    | [Iuge](https://gitee.com/ChuangHuLiDeShuangYan) | 开发中 |
| [Huawei-Pulsar](https://gitee.com/HuaweiCloudDeveloper/huawei-pulsar-plugins) | Pulsar对接华为云OBS，DLI，DWS等云服务                        | momimi1234                                      | 开发中 |
| [Huawei-Druid](https://gitee.com/HuaweiCloudDeveloper/Huaweicloud-Druid-plugin) | Druid对接华为云OBS，DLI，RDS等云服务                         | 待分配                                          | 待分配 |
| Huawei-Drill | Drill对接华为云服务                         | 待分配                                          | 待分配 |
| Huawei-Flume | Flume对接华为云服务                         | 完成                                          | 完成 |
| Huawei-Starrocks | Starrocs对接华为云服务                         | 待分配                                          | 待分配 |
| Huawei-Hive | Hive对接华为云服务                         | 完成                                          | 完成 |
| Huawei-Camel | Camel对接华为云服务                         | 待分配                                          | 待分配 |
| Huawei-confluentinc | confluentinc对接华为云服务                         | 待分配                                          | 待分配 |
| Huawei-Ranger | Ranger对接华为云OBS                         | 待分配                                          | 待分配 |





## Go

| 仓库                                                         | 简介                                      | Committer                         | 状态   |
| ------------------------------------------------------------ | :---------------------------------------- | --------------------------------- | ------ |
| [Huawei-Thanos](https://gitee.com/HuaweiCloudDeveloper/obs-thanos-plugins) | 本项目的目的是扩展Thanos，使其支持OBS存储 | [peng](https://gitee.com/pengcss) | 完成   |
| [Huawei-Vault](https://gitee.com/HuaweiCloudDeveloper/huawei-vault-plugins) | Vault对接华为云服务                       | [peng](https://gitee.com/pengcss) | 开发中 |
| [Huawei-MinIO](https://gitee.com/HuaweiCloudDeveloper/huawei-min-io-plugins) | minio对接华为云OBS插件                    | 待分配                            | 待分配 |
| [Huawei-CockroachDB](https://gitee.com/HuaweiCloudDeveloper/huawei-cockroach-db-plugins) | CockroachDB对接华为云OBS插件              | 待分配                            | 待分配 |
| [Huawei-Drone](https://gitee.com/HuaweiCloudDeveloper/huawei-drone-plugins) | Drone对接华为云OBS插件                    | 待分配                            | 待分配 |
| [Huawei-Consul](https://gitee.com/HuaweiCloudDeveloper/huawei-consul-plugins) | Consul对接华为云CA、ECS云服务             | 待分配                            | 待分配 |
| [Huawei-Trivy](https://gitee.com/HuaweiCloudDeveloper/huawei-trivy-plugins) | Trivy对接华为云SWR、ECS等云服务           | 待分配                            | 待分配 |
| [Huawei-Vitess](https://gitee.com/HuaweiCloudDeveloper/huawei-vitess-plugins) | Vitess对接华为云OBS插件                   | 待分配                            | 待分配 |
| [Huawei-Cilium](https://gitee.com/HuaweiCloudDeveloper/huawei-cilium-plugins) | Cilium对接华为云VPC插件                   |  [鬼画符](https://gitee.com/mail_osc)  | 开发中 |
| [Huawei-Teleport](https://gitee.com/HuaweiCloudDeveloper/huawei-teleport-plugins) | Teleport对接华为云OBS、DDS等云服务        | [鬼画符](https://gitee.com/mail_osc) | 开发中 |
| [Huawei-Kaniko](https://gitee.com/HuaweiCloudDeveloper/huawei-kaniko-plugins) | Kaniko对接华为云OBS云服务                 | 待分配                            | 待分配 |
| [Huawei-CoreDNS](https://gitee.com/HuaweiCloudDeveloper/huawei-core-dns-plugins) | CoreDNS对接华为云DNS云服务                | 待分配                            | 待分配 |
| [Huawei-Cert-Manager](https://gitee.com/HuaweiCloudDeveloper/huawei-cert-manager-plugins) | cert-manager对接华为云DNS云服务           | 待分配                            | 待分配 |
| [Huawei-Dolt](https://gitee.com/HuaweiCloudDeveloper/huawei-dolt-plugins) | Dolt对接华为云OBS云服务                   | 待分配                            | 待分配 |
| [Huawei-Distribution](https://gitee.com/HuaweiCloudDeveloper/huawei-distribution-plugins) | Distribution对接华为云OBS服务             | 待分配                            | 待分配 |
| [Huawei-Velero](https://gitee.com/HuaweiCloudDeveloper/huawei-velero-plugins) | Velero对接华为云OBS云服务                 | [鬼画符](https://gitee.com/mail_osc)  | 开发中 |
| [Huawei-Cadence](https://gitee.com/HuaweiCloudDeveloper/huawei-cadence-plugins) | Cadence对接华为云OBS云服务                | [鬼画符](https://gitee.com/mail_osc)  | 开发中 |
| [Huawei-Crossplane](https://gitee.com/HuaweiCloudDeveloper/huawei-crossplane-plugins) | Crossplane对接华为云OBS、DCS、RDS等云服务 |  [鬼画符](https://gitee.com/mail_osc) | 开发中 |
| [Huawei-Kraken](https://gitee.com/HuaweiCloudDeveloper/huawei-kraken-plugins) | Kraken对接华为云OBS云服务                 | 待分配                            | 待分配 |
| [Huawei-Easegress](https://gitee.com/HuaweiCloudDeveloper/huawei-easegress-plugins) | Easegress对接华为云DNS云服务              | 待分配                            | 待分配 |
| [Huawei-Bytebase](https://gitee.com/HuaweiCloudDeveloper/huawei-bytebase-plugins) | Bytebase对接华为云OBS服务                 | 待分配                            | 待分配 |
| [Huawei-Flux](https://gitee.com/HuaweiCloudDeveloper/huawei-flux-plugins) | Flux对接华为云SWR云服务                   | 待分配                            | 待分配 |
| [Huawei-Flagger](https://gitee.com/HuaweiCloudDeveloper/huawei-flagger-plugins) | Flagger对接华为云CES云服务                | 待分配                            | 待分配 |
| [Huawei-Terrascan](https://gitee.com/HuaweiCloudDeveloper/huawei-terrascan-plugins) | Terrascan对接华为云SWR云服务              | 待分配                            | 待分配 |
| [Huawei-Gloo](https://gitee.com/HuaweiCloudDeveloper/huawei-gloo-plugins) | Gloo对接华为云ECS等云服务                 | 待分配                            | 待分配 |
| [Huawei-Werf](https://gitee.com/HuaweiCloudDeveloper/huawei-werf-plugins) | Werf对接华为云SWR云服务                   | 待分配                            | 待分配 |
| [Huawei-Pomerium](https://gitee.com/HuaweiCloudDeveloper/huawei-pomerium-plugins) | Pomerium对接华为云OBS服务                 | 待分配                            | 待分配 |
| [Huawei-Weaviate](https://gitee.com/HuaweiCloudDeveloper/huawei-weaviate-plugins) | Weaviate对接华为云OBS服务                 | 待分配                            | 待分配 |



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
| Huawei-ArangoDB | ArangoDB对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-Impala | Impala对接华为云华为云服务                                | 待分配    | 待分配 |
| Huawei-FoundationDB | FoundationDB对接华为云服务                                | 待分配    | 待分配 |
| Huawei-RethinkDB | RethinkDB对接华为云服务                                 | 待分配    | 待分配 |
| Huawei-ScyllaDB | ScyllaDB对接华为云服务                                 | 待分配    | 待分配 |
| Huawei-YugabyteDB | YugabyteDB对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-Redpanda | Redpanda对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-Ceph | Ceph对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-CubeFS | CubeFS对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-Gluster | Gluster对接华为云服务                                  | 待分配    | 待分配 |
| Huawei-WasmEdge Runtime| WasmEdge Runtime对接华为云服务                                 | 待分配    | 待分配 |
| Huawei-Falco | Falco对接华为云服务                                  | 待分配    | 待分配 |



## 其他

| 仓库                                                         | 简介                        | Committer | 状态   |
| ------------------------------------------------------------ | --------------------------- | --------- | ------ |
| 【TypeScript】[Huawei-Deepstream](https://gitee.com/HuaweiCloudDeveloper/huawei-deepstream-plugins) | Deepstream对接华为云OBS插件 | 梁剑      | 开发中 |
| 【TypeScript】[Huawei-Backstage](https://gitee.com/HuaweiCloudDeveloper/huawei-backstage-plugins) | Backstage对接华为云服务     | 待分配    | 待分配 |
| 【TypeScript】Huawei-supabase | Backstage对接华为云服务     | 待分配    | 待分配 |
| 【TypeScript】Huawei-Apache Camel Karavan | Backstage对接华为云服务     | 待分配    | 待分配 |
| 【Html】Huawei-Contour | Contour对接华为云服务     | 待分配    | 待分配 |
| 【Scala】Huawei-Spark | Spark对接华为云服务     | 完成    | 完成 |
| 【Scala】Huawei-Delta | Delta对接华为云服务     | 待分配    | 待分配 |
| 【Scala】Huawei-CarbonData | CarbonData对接华为云服务     | 待分配    | 待分配 |
| 【Rust】Huawei-TiKV | TiKV对接华为云服务     | 待分配    | 待分配 |
| 【Rust】Huawei-Firecracker | Firecracker对接华为云服务     | 待分配    | 待分配 |
| 【Clujore】Huawei-Crux | Crux对接华为云服务     | 待分配    | 待分配 |
| 【Rust】Huawei-Databend | Databend对接华为云服务     | 待分配    | 待分配 |
| 【Lua】Huawei-Tarantool | Tarantool对接华为云服务     | 待分配    | 待分配 |
| 【Shell】Huawei-Spinnaker | Spinnaker对接华为云服务     | 待分配    | 待分配 |
| 【Yaml】Huawei-OpenEBS | OpenEBS对接华为云服务     | 待分配    | 待分配 |
| 【Ruby】Huawei-Chef Infra | Chef Infra对接华为云服务     | 待分配    | 待分配 |
| 【Groovy】Huawei-Rundeck | Rundeck对接华为云服务     | 待分配    | 待分配 |


[^备注]: 开发者可以通过issues和邮件认领状态为待分配的项目，社区确认后将有专人联系对接。