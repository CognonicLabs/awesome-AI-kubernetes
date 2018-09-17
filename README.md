# :snowflake: :whale: Awesome AI, ML and Data Science on Kubernetes
Tools for AI, DL, ML, CV, DS, Analytics baked in the oven to be Native on [Kubernetes](http://kubernetes.io/)

*"The wind and the waves are always on the side of the ablest navigator."* [Edmund Gibbon, Historian](http://www.seasky.org/quotes/sea-quotes-ocean-ships-sailing.html)

---

**Introduction**

The entire computing industry has adopted Kubernetes as the way forward to running distibuted computing loads from on-premise servers to large multi-cloud deployments.

For Machine Learning and Data Science workloads that are often prototyped on informal tools like JupyterLab, the awareness of Kubernetes has lagged somewhat. 

**Kubernetes Advantages for ML**

- almost infinite and flexible automatic scaling of processing resources
- almost universal runtime flexibility to deploy to any cloud
- incredible and complete industry adoption, check out every Titan of the Tech Industry here: https://www.cncf.io/about/members/ (and to a large extent, "Cloud Native" means "anything designed to work with Kubernetes")
- finally the promise of self-healing applications can be realized

**Kubernetes Issues to Consider for ML**

- every application is organized in one or more Docker containers (or other compatible containers) and those containers need to be light weight if scaling is to be a realistic consideration
- containers are immutable which allows the self-healing ability of Kubernetes as well as efficient scaling and placement of containers where they can be efficiently slotted into a server cluster
- for Data Scientists new to Kubernetes it may not be obvious that provisioning of Kubernetes persitent storage is a key item for your data pipelines - take a look at [Rook](https://rook.io) to see one good approach to this issue.
- for Data Scientists new to Kubernetes it may not be obvious that the fluid movement and destruction of containers means that talking to your own application takes on a whole new meaning. The rise of the "Service Mesh" can be very helpful here: http://layer5.io/service-meshes/

---

For this list, I am focused on AI/ML/Data Science OSS Tools that run in an infinitely scaleable Kubernetes environment. Another list that shares some scaling orchestration resources in a more general way is [Awesome Machine Learning Operations](https://github.com/axsauze/awesome-machine-learning-operations)

You might also be looking for something far less specific and here are some suggestions:

**Kubernetes** 

- a general purpose Kubernetes list, [awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)
- [Awesome Helm](https://github.com/cdwv/awesome-helm)
- [Awesome Operators](https://github.com/operator-framework/awesome-operators)
- [Awesome Docker](https://github.com/veggiemonk/awesome-docker)
- [container-security-awesome](https://github.com/kai5263499/container-security-awesome)
- [Awesome Linux Containers](https://github.com/Friz-zy/awesome-linux-containers)

**Spark**

- [Awesome Spark](https://github.com/awesome-spark/awesome-spark)
- [Awesome Apache Spark Packages](https://github.com/Mageswaran1989/awesome-ApacheSpark-collections)
- [Awesome Scala](https://github.com/lauris/awesome-scala)

**AI/ML**

- [awesome-AIOps](https://github.com/linjinjin123/awesome-AIOps)
- [Awesome Julia](https://github.com/greister/Awesome-Julia)
- [Awesome R](https://github.com/qinwf/awesome-R)
- [Awesome Bioinformatics](https://github.com/shenwei356/awesome/blob/master/bioinformatics.md)
- [Awesome Recurrent Neural Networks](https://github.com/kjw0612/awesome-rnn)
- [Awesome Reinforcement Learning](https://github.com/aikorea/awesome-rl)
- [Awesome Artificial Intelligence](https://github.com/owainlewis/awesome-artificial-intelligence)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [Awesome StarCraft AI](https://github.com/SKTBrain/awesome-starcraftAI)
- [Awesome Quantum Machine Learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning)
- [Awesome AI](https://github.com/hades217/awesome-ai)
- [Awesome Feature Engineering for Machine Learning](https://github.com/aikho/awesome-feature-engineering)
- [Awesome WindowsML ONNX Models](https://github.com/ChangweiZhang/Awesome-WindowsML-ONNX-Models)
- [Awesome-ONNX-Models](https://github.com/ChangweiZhang/Awesome-ONNX-Models)
- [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow)
- [Awesome Blockchain AI](https://github.com/steven2358/awesome-blockchain-ai)
- [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
- [Awesome Deep Learning Resources](https://github.com/guillaume-chevalier/Awesome-Deep-Learning-Resources)
- [awesome-nlp](https://github.com/keon/awesome-nlp)
- [Awesome-Pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list)
- [awesome-ai-services](https://github.com/sekwiatkowski/awesome-ai-services)
- [awesome_list_ai_bot_programming](https://github.com/stuffyjumpy/awesome_list_ai_bot_programming)
- [Machine Learning & Deep Learning Tutorials](https://github.com/ujjwalkarn/Machine-Learning-Tutorials)
- [Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code)
- [awesome-machine-learning-interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)
- [Awesome Interpretable Machine Learning](https://github.com/lopusz/awesome-interpretable-machine-learning)
- [Awesome-AutoML](https://github.com/hibayesian/awesome-automl-papers)
- [Awesome H2O](https://github.com/h2oai/awesome-h2o)
- [Awesome MXNet](https://github.com/chinakook/Awesome-MXNet)
- [Awesome Bots](https://github.com/hackerkid/bots)
- [Awesome ChatOps](https://github.com/exAspArk/awesome-chatops)



**Other**

- [Awesome Apache Airflow](https://github.com/jghoman/awesome-apache-airflow)
- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
- [Awesome-BigData](https://github.com/Harshakvarma/Awesome-BigData)
- [awesome-datasets](https://github.com/datasciencethgrp/awesome-datasets)
- [Awesome Analytics](https://github.com/onurakpolat/awesome-analytics)
- [Awesome Data Science](https://github.com/bulutyazilim/awesome-datascience)
- [Awesome Pipeline](https://github.com/pditommaso/awesome-pipeline)
- [Awesome Nextflow](https://github.com/nextflow-io/awesome-nextflow)
- [awesome-etl](https://github.com/pawl/awesome-etl)
- [Awesome Business Intelligence](https://github.com/thenaturalist/awesome-business-intelligence)



---

**Note:** Although many OSS projects are another octopus arm of mega-tech-corps like Google and Microsoft, we all benefit and in particular many smaller OSS projects represent a lot of volunteer effort by many individuals supporting OSS represented in this list. If you agree and when you can, please consider giving feedback to the authors, perhaps even testing their code and filing issue reports/feature requests and it is pretty easy to hit the Star button for their project. If your favorite project is missing from this list, please let me know.

---

Kubernetes means **Helmsman** and originated with Google's Borg:

> "Its development and design are heavily influenced by Google's Borg system, and many of the top contributors to the project previously worked on Borg. The original codename for Kubernetes within Google was Project Seven, a reference to Star Trek character Seven of Nine that is a 'friendlier' Borg. The seven spokes on the wheel of the Kubernetes logo is a nod to that codename."  https://en.wikipedia.org/wiki/Kubernetes

**Note:** I will attempt to sprinkle in various salty sea references in this document with perhaps some borg ones as well to stay with the spirit of the Kubernetes naming genesis...

### Helmsman of a Great Ship

*"The duties of the ruler are like those of the helmsman of a great ship. From his lofty position, he makes slight movements with his hands, and the ship, of itself, follows his desires and moves. This is the way whereby the one may control the ten thousand and by quiescence may regulate activity."* [Han Fei](https://www.brainyquote.com/quotes/han_fei_875664)

---


# ML designed for Kubernetes (i.e. Native Kube)

*"If you want to build a ship, don't drum up the men to gather wood, divide the work and give orders. Instead, teach them to yearn for the vast and endless sea."* [Antoine de Saint Exupery](https://quotabulary.com/famous-quotes-about-sea-sailing)

---

[Kubeflow](http://kubeflow.org/)  Cloud Native platform for machine learning. https://github.com/kubeflow/kubeflow The Kubeflow project is dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable. Our goal is not to recreate other services, but to provide a straightforward way to deploy best-of-breed open-source systems for ML to diverse infrastructures. Anywhere you are running Kubernetes, you should be able to run Kubeflow.
- TensorFlow model training - A TensorFlow Training Controller that can be configured to use either CPU’s or GPUs and be dynamically adjusted to the size of a cluster with a single setting. We also provide a [TensorFlow job operator](https://github.com/kubeflow/tf-operator).
- Model serving - A TensorFlow Serving container to export trained TensorFlow models to Kubernetes. We also integrate with [Seldon Core](https://www.seldon.io/), the open source platform for deploying machine learning models on Kubernetes.
- Multi-framework - Our development plans go beyond TensorFlow, and we are working hard to include [PyTorch](https://github.com/kubeflow/pytorch-operator), [MXNet](https://github.com/kubeflow/mxnet-operator), [Chainer](https://github.com/kubeflow/chainer-operator), and more. We also integrate with [Ambassador](https://www.getambassador.io/) for ingress and [Pachyderm](http://pachyderm.io/)  for managing your data science pipelines.

[Kubeflow Labs](https://github.com/Azure/kubeflow-labs) Train and Serve TensorFlow Models at Scale with Kubernetes and Kubeflow on Azure

[H2O + Kubeflow](https://github.com/h2oai/h2o-kubeflow) H2O + Kubeflow Integration. This is a project for the integration of H2O.ai and Kubeflow. The integration of H2O and Kubeflow is an extremely powerful opportunity, as it provides a turn-key solution for easily deployable and highly scalable machine learning applications, with minimal input required from the user. [Kubeflow](http://kubeflow.org/) is an open source project managed by Google and built on top of their Kubernetes engine. It is designed to alleviate some of the more tedious tasks associated with machine learning. Kubeflow helps orchestrate deployment of apps through the full cycle of development, testing, and production, and allows for resource scaling as demand increases.[H2O 3](http://h2o.ai/)’s goal is to reduce the time spent by data scientists on time-consuming tasks like designing grid search algorithms and tuning hyperparameters, while also providing an interface that allows newer practitioners an easy foothold into the machine learning space. https://github.com/h2oai/h2o-3

---

[Seldon Core](https://www.seldon.io/) Seldon Core is an open source platform for deploying machine learning models on Kubernetes https://github.com/SeldonIO/seldon-core

---

[Pachyderm](http://pachyderm.io/) Pachyderm is a tool for production data pipelines. If you need to chain together data scraping, ingestion, cleaning, munging, wrangling, processing, modeling, and analysis in a sane way, then Pachyderm is for you. If you have an existing set of scripts which do this in an ad-hoc fashion and you're looking for a way to "productionize" them, Pachyderm can make this easy for you. https://github.com/pachyderm/pachyderm

---

[Fabric for Deep Learning - FfDL, pronounced fiddle](https://developer.ibm.com/patterns/deploy-and-use-a-multi-framework-deep-learning-platform-on-kubernetes/)  Deep Learning Platform offering TensorFlow, Caffe, PyTorch etc. as a Service on Kubernetes. This repository contains the core services of the FfDL (Fabric for Deep Learning) platform. FfDL is an operating system "fabric" for Deep Learning. https://github.com/IBM/FfDL

FfDL is a collaboration platform for:

- Framework-independent training of Deep Learning models on distributed hardware
- Open Deep Learning APIs
- Common instrumentation
- Running Deep Learning hosting in user's private or public cloud

---

[PolyAxon](https://polyaxon.com/) Welcome to Polyaxon, a platform for building, training, and monitoring large scale deep learning applications.Polyaxon deploys into any data center, cloud provider, or can be hosted and managed by Polyaxon, and it supports all the major deep learning frameworks such as Tensorflow, MXNet, Caffe, Torch, etc. Polyaxon makes it faster, easier, and more efficient to develop deep learning applications by managing workloads with smart container and node management. And it turns GPU servers into shared, self-service resources for your team or organization https://github.com/polyaxon/polyaxon

---

[Datalayer](https://github.com/datalayer/datalayer) Big Data Science on Kubernetes in the Cloud. https://datalayer.io Datalayer is building a Simple, Collaborative and Multi Cloud platform for Big Data Scientists. https://docs.datalayer.io 

---

[Machine Learning Container Templates](https://github.com/IntelAI/mlt) from [IntelAI](http://ai.intel.com/) - mlt aids in the creation of containers for machine learning jobs. It does so by making it easy to use container and kubernetes object templates.

---



# ML that is adapted for Kubernetes

*“Impossible” is a word that humans use far too often."* [Seven of Nine](http://quotegeek.com/television-quotes/star-trek-voyager/)

---

[Pipeline.AI](https://github.com/PipelineAI/pipeline) PipelineAI: Real-Time Enterprise AI Platform https://pipeline.ai - Quickstart for Kubernetes: https://github.com/PipelineAI/pipeline/tree/master/docs/quickstart/kubernetes

---

[Helm Charts Apache Kafka](https://github.com/Landoop/kafka-helm-charts) Kubernetes Helm charts for Apache Kafka and Kafka Connect and other components for data streaming and data integration. [Stream-reactor](https://github.com/Landoop/stream-reactor) and Kafka Connectors any environment variable beginning with CONNECT is used to build the Kafka Connect properties file, the Connect cluster is started with this file in distributed mode.

---

[Bigdata Playground](https://github.com/Chabane/bigdata-playground) A complete example of a big data application using : Kubernetes, Apache Spark SQL/Streaming/MLib, Apache Flink, Kafka Streams, Apache Beam, Scala, Python, Apache Kafka, Apache Hbase, Apache Parquet, Apache Avro, Apache Storm, Twitter Api, MongoDB, NodeJS, Angular, GraphQL - The aim is to create a disposable Hadoop/HBase/Spark/Flink/Beam/ML stack where you can test your jobs locally or to submit them to the Yarn resource manager. We are using Docker to build the environment and Docker-Compose to provision it with the required components (Next step using Kubernetes). Along with the infrastructure, We are check that it works with 4 projects that just probes everything is working as expected. The boilerplate is based on a sample search flight web application.

---

# Pipeline and Data Flow

---

[Banzai Pipeline](https://github.com/banzaicloud/pipeline) Pipeline enables developers to go from commit to scale in minutes by turning Kubernetes into a feature rich application platform integrating CI/CD, centralized logging, monitoring, enterprise-grade security and autoscaling.

---

[Argo](https://argoproj.github.io/) Get stuff done with container-native workflows for Kubernetes. https://github.com/argoproj/argo Argo is designed from the ground up for containers without the overhead and limitations of legacy VM and server-based environments. Argo is cloud agnostic and can run on any kubernetes cluster. Argo with Kubernetes puts a cloud-scale supercomputer at your fingertips.

[Argo Events](https://github.com/argoproj/argo-events) Argo Events is an open source event-based dependency manager for Kubernetes. The core concept of the project are sensors which are implemented as Kubernetes-native Custom Resource Definition that define a set of dependencies (signals) and actions (triggers). The sensor's triggers will only be fired after it's signals have been resolved. Sensors can trigger once or repeatedly.


---

[Airflow](https://airflow.apache.org/) Apache Airflow (or simply Airflow) is a platform to programmatically author, schedule, and monitor workflows. When workflows are defined as code, they become more maintainable, versionable, testable, and collaborative. Use Airflow to author workflows as directed acyclic graphs (DAGs) of tasks. The Airflow scheduler executes your tasks on an array of workers while following the specified dependencies. Rich command line utilities make performing complex surgeries on DAGs a snap. The rich user interface makes it easy to visualize pipelines running in production, monitor progress, and troubleshoot issues when needed.

[ETL best practices with airflow](https://gtoonstra.github.io/etl-with-airflow/) What you will find here are interesting examples, usage patterns and ETL principles that I thought are going to help people use airflow to much better effect. https://github.com/gtoonstra/etl-with-airflow

[kube-airflow](https://github.com/mumoshu/kube-airflow) kube-airflow provides a set of tools to run Airflow in a Kubernetes cluster.

[Airflow Operator](https://github.com/GoogleCloudPlatform/airflow-operator) Airflow Operator is a custom Kubernetes operator that makes it easy to deploy and manage Apache Airflow on Kubernetes. Apache Airflow is a platform to programmatically author, schedule and monitor workflows. Using the Airflow Operator, an Airflow cluster is split into 2 parts represented by the AirflowBase and AirflowCluster custom resources. 


---

**Beam**

[beam-operator](https://github.com/aleksdjuricin/beam-operator) This operator manages [Apache Beam](https://beam.apache.org/) instances on Kubernetes, simplifying creation and administration.

[Scheduled Apache Beam jobs using Kubernetes Cronjobs](https://github.com/sanderploegsma/beam-scheduling-kubernetes) Scheduled Dataflow pipelines using Kubernetes Cronjobs

[Google Cloud Dataflow Template Pipelines](https://github.com/GoogleCloudPlatform/DataflowTemplates) These Dataflow templates are an effort to solve simple, but large, in-Cloud data tasks, including data import/export/backup/restore and bulk API operations, without a development environment. The technology under the hood which makes these operations possible is the Google Cloud Dataflow service combined with a set of Apache Beam SDK templated pipelines. Google is providing this collection of pre-implemented Dataflow templates as a reference and to provide easy customization for developers wanting to extend their functionality.

---

[Rook](https://rook.io/) Storage Orchestration for Kubernetes https://github.com/rook/rook Rook is an open source cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for a diverse set of storage solutions to natively integrate with cloud-native environments. Rook turns storage software into self-managing, self-scaling, and self-healing storage services. It does this by automating deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management. Rook uses the facilities provided by the underlying cloud-native container management, scheduling and orchestration platform to perform its duties. Rook integrates deeply into cloud native environments leveraging extension points and providing a seamless experience for scheduling, lifecycle management, resource management, security, monitoring, and user experience.

---

[OpenEBS](https://www.openebs.io/) OpenEBS is containerized block storage written in Go for cloud native and other environments w/ per container (or pod) QoS SLAs, tiering and replica policies across AZs and environments, and predictable and scalable performance. https://github.com/openebs/openebs OpenEBS enables the use of containers for mission-critical, persistent workloads. OpenEBS is containerized storage and related storage services.

OpenEBS allows you to treat your persistent workload containers, such as DBs on containers, just like other containers. OpenEBS itself is deployed as just another container on your host and enables storage services that can be designated on a per pod, application, cluster or container level, including:
- Data persistence across nodes, dramatically reducing time spent rebuilding Cassandra rings for example.
- Synchronization of data across availability zones and cloud providers.
- Use of commodity hardware plus a container engine to deliver so called container attached block storage.
- Integration with Kubernetes, so developer and application intent flows into OpenEBS configurations automatically.
- Management of tiering to and from S3 and other targets.

Our vision is simple: let storage and storage services for persistent workloads be fully integrated into the environment and hence can be managed automatically that it almost disappears into the background as just yet another infrastructure service that just works.

[Open EBS Maya](https://github.com/openebs/maya) OpenEBS Maya extends Kubernetes capabilities to orchestrate CAS containers. OpenEBS Maya extends the capabilities of Kubernetes to orchestrate CAS (aka Container Native) Storage Solutions like OpenEBS Jiva, OpenEBS cStor, etc. Maya (meaning Magic), seamlessly integrates into the Kubernetes Storage Workflow and helps provision and manage the CAS based Storage Volumes. 

[OpenEBS Helm Charts](https://github.com/openebs/charts)


---

# Can Spark still be Master of the Sea?


*"Would'st thou," so the helmsman answered, "Learn the secret of the sea? Only those who brave its dangers Comprehend its mystery!"* [Henry Wadsworth Longfellow](http://quotes.yourdictionary.com/helmsman)

```
"Gentile or Jew
 O you who turn the wheel and look to windward,
 Consider Phlebas, who was once handsome and tall as you" 
 ```
 [The Waste Land by T.S. Eliot](https://www.poetryfoundation.org/poems/47311/the-waste-land)

---

**Note:** Kubernetes support was integrated into Spark with the 2.3 release. It is still incomplte and missing several important features, but it is a top priority for the Spark team.

---

[Spark Operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) Kubernetes operator for specifying and managing the lifecycle of Apache Spark applications on Kubernetes. Spark Operator aims to make specifying and running Spark applications as easy and idiomatic as running other workloads on Kubernetes. It uses Kubernetes custom resources for specifying, running, and surfacing status of Spark applications. For a complete reference of the custom resource definitions, please refer to the API Definition. For details on its design, please refer to the design doc. It requires Spark 2.3 and above that supports Kubernetes as a native scheduler backend.

---

[Multi cloud Spark application service on PKS](https://github.com/SnappyDataInc/spark-on-k8s) An Integrated and collaborative cloud environment for building and running Spark applications on PKS/Kubernetes. This project provides a streamlined way of deploying, scaling and managing Spark applications. Spark 2.3 added support for Kubernetes as a cluster manager. This project leverages Helm charts to allow deployment of common Spark application recipes - using Apache Zeppelin and/or Jupyter for interactive, collaborative workloads. It also automates logging of all events across batch jobs and Notebook driven applications to log events to shared storage for offline analysis. This project is a collaborative effort between SnappyData and Pivotal.

---

[Sparknetes](https://github.com/hypnosapos/sparknetes) Spark on kubernetes. Based on official documentation of spark 2.3 at https://spark.apache.org/docs/2.3.0/running-on-kubernetes.html

---

[HDFS on Kubernetes](https://github.com/apache-spark-on-k8s/kubernetes-HDFS) Repository holding helm charts for running Hadoop Distributed File System (HDFS) on Kubernetes. See [charts/README.md](https://github.com/apache-spark-on-k8s/kubernetes-HDFS/blob/master/charts/README.md) for how to run the charts. See [tests/README.md](https://github.com/apache-spark-on-k8s/kubernetes-HDFS/blob/master/tests/README.md) for how to run integration tests for HDFS on Kubernetes.

---

[Apache Spark Helm Chart](https://github.com/helm/charts/tree/master/stable/spark) This chart will do the following:
- 1 x Spark Master with port 8080 exposed on an external LoadBalancer
- 3 x Spark Workers with HorizontalPodAutoscaler to scale to max 10 pods when CPU hits 50% of 100m
- 1 x Zeppelin with port 8080 exposed on an external LoadBalancer
- All using Kubernetes Deployments

---

[Helm Chart for Spark Operator](https://github.com/helm/charts/tree/master/incubator/sparkoperator) This is the Helm chart for the Spark-on-Kubernetes Operator. Prerequisites: The Operator requires Kubernetes version 1.8 and above because it relies on garbage collection of custom resources. If customization of driver and executor pods (through mounting custom configMaps and volumes) is desired, then the Mutating Admission Webhook needs to be enabled and it only became beta in Kubernetes 1.9.

The chart can be installed by running:
```
$ helm repo add incubator http://storage.googleapis.com/kubernetes-charts-incubator
$ helm install incubator/sparkoperator
```
By default, the operator is installed in a namespace called "spark-operator". It would be created if it does not exist.

---

[Kubernetes official examples](https://github.com/kubernetes/examples/tree/master/staging/spark) - (Not up to date) Following this example, you will create a functional Apache Spark cluster using Kubernetes and Docker. You will setup a Spark master service and a set of Spark workers using Spark's standalone mode [Spark on GlusterFS example](https://github.com/kubernetes/examples/tree/master/staging/spark/spark-gluster) (Also, not up to data) This guide is an extension of the standard Spark on Kubernetes Guide and describes how to run Spark on GlusterFS using the Kubernetes Volume Plugin for GlusterFS - The setup is the same in that you will setup a Spark Master Service in the same way you do with the standard Spark guide but you will deploy a modified Spark Master and a Modified Spark Worker ReplicationController, as they will be modified to use the GlusterFS volume plugin to mount a GlusterFS volume into the Spark Master and Spark Workers containers. Note that this example can be used as a guide for implementing any of the Kubernetes Volume Plugins with the Spark Example. There is also a [video available](https://youtu.be/xyIaoM0-gM0) that provides a walkthrough for how to set this solution up

---

[Intel BigDL](https://bigdl-project.github.io/) BigDL: Distributed Deep Learning Library for Apache Spark  https://github.com/intel-analytics/BigDL - BigDL is a distributed deep learning library for Apache Spark; with BigDL, users can write their deep learning applications as standard Spark programs, which can directly run on top of existing Spark or Hadoop clusters. To makes it easy to build Spark and BigDL applications, a high level Analytics Zoo is provided for end-to-end analytics + AI pipelines.
- Rich deep learning support. Modeled after Torch, BigDL provides comprehensive support for deep learning, including numeric computing (via Tensor) and high level neural networks; in addition, users can load pre-trained Caffe or Torch models into Spark programs using BigDL.
- Extremely high performance. To achieve high performance, BigDL uses Intel MKL and multi-threaded programming in each Spark task. Consequently, it is orders of magnitude faster than out-of-box open source Caffe, Torch or TensorFlow on a single-node Xeon (i.e., comparable with mainstream GPU).
- Efficiently scale-out. BigDL can efficiently scale out to perform data analytics at "Big Data scale", by leveraging Apache Spark (a lightning fast distributed data processing framework), as well as efficient implementations of synchronous SGD and all-reduce communications on Spark.

[BigDL-core](https://github.com/intel-analytics/BigDL-core) Core HW bindings and optimizations for BigDL

[Getting Started](https://bigdl-project.github.io/master/#getting-started/)

[Deep Learning Tutorials on Apache Spark using BigDL](https://github.com/intel-analytics/BigDL-tutorials) Step-by-step Deep Learning Tutorials on Apache Spark using BigDL. The tutorials are inspired by Apache Spark examples, the Theano Tutorials and the Tensorflow tutorials.

[ElephantScale BigDL Tutorials](https://github.com/elephantscale/bigdl-tutorials)

[LetNet/BigDL Workshop](https://github.com/alex-kalinin/lenet-bigdl) Notebooks for LetNet/BigDL deep learning workshop. The workshop environment is available for download in a Docker container.

[Intel Analytics Zoo](https://analytics-zoo.github.io/) Distributed Tensorflow, Keras and BigDL on Apache Spark  - https://github.com/intel-analytics/analytics-zoo - Analytics Zoo provides a unified analytics + AI platform that seamlessly unites Spark, TensorFlow, Keras and BigDL programs into an integrated pipeline; the entire pipeline can then transparently scale out to a large Hadoop/Spark cluster for distributed training or inference.
- Data wrangling and analysis using PySpark
- Deep learning model development using TensorFlow or Keras
- Distributed training/inference on Spark and BigDL
- All within a single unified pipeline and in a user-transparent fashion!
In addition, Analytics Zoo also provides a rich set of analytics and AI support for the end-to-end pipeline, including:
- Easy-to-use abstractions and APIs (e.g., transfer learning support, autograd operations, Spark DataFrame and ML pipeline support, online model serving API, etc.)
- Common feature engineering operations (for image, text, 3D image, etc.)
- Built-in deep learning models (e.g., object detection, image classification, text classification, recommendation, etc.)
- Reference use cases (e.g., anomaly detection, sentiment analysis, fraud detection, image similarity, etc.)

---


# Spark on OKD

[Rad Analytics Spark Operator](https://github.com/radanalyticsio/spark-operator) ConfigMap and CRD based approach for managing the Spark clusters in Kubernetes or OpenShift.

---

[OpenShift Spark](https://github.com/radanalyticsio/openshift-spark) This repository contains several files for building Apache Spark focused container images, targeted for usage on OpenShift Origin. [tutorial-sparkpi-java-vertx](https://github.com/radanalyticsio/tutorial-sparkpi-java-vertx) A Java implementation of SparkPi using Vert.x 3 - This application is an example tutorial for the radanalytics.io community. It is intended to be used as a source-to-image (s2i) application.



# Some Utils and Accessories


---

[Helm Chart for Elastic-Fluentd-Kibana logging](https://github.com/cdwv/efk-stack-helm) Helm chart to deploy a working logging solution using the ElasticSearch - Fluentd - Kibana stack on Kubernetes


---

[Draft](https://draft.sh/) A tool for developers to create cloud-native applications on Kubernetes https://github.com/Azure/draft Draft makes it easier for developers to build applications that run on Kubernetes by doing two main things:
- The draft create command gives developers the artifacts they need to build and run their applications in Kubernetes
- The draft up command builds the container image for an application and deploys it to Kubernetes

[Draft Pack Repository Plugin](https://github.com/draftcreate/draft-pack-repo) Draft Pack Repository Plugin (or draft pack-repo for short) enables users to fetch, list, add and remove pack repositories to bootstrap all of their internal and external projects. It is incredibly opinionated on how to fetch, list, add and remove these repositories whereas Draft core does not care about these concepts.  This also enables the Draft community to come up alternative forms of pack repositories by implementing their own plugin for fetching down these packs, so it made sense to initially spike the tooling as an entirely separate project.

---

[Brigade](https://brigade.sh/) Event-based Scripting for Kubernetes. https://github.com/Azure/brigade Script simple and complex workflows using JavaScript. Chain together containers, running them in parallel or serially. Fire scripts based on times, GitHub events, Docker pushes, or any other trigger. Brigade is the tool for creating pipelines for Kubernetes.
- JavaScript scripting
- Project-based management
- Configurable event hooks
- Easy construction of pipelines
- Check out the [docs](https://azure.github.io/brigade/) to get started.

The Brigade Technology Stack

- Brigade ❤️ JavaScript: Writing Brigade pipelines is as easy as writing a few lines of JavaScript.
- Brigade ❤️ Kubernetes: Brigade is Kubernetes-native. Your builds are translated into pods, secrets, and services
- Brigade ❤️ Docker: No need for special plugins or elaborate extensions. Brigade uses off-the-shelf Docker images to run your jobs. And Brigade also supports DockerHub webhooks.
- Brigade ❤️ GitHub: Brigade comes with built-in support for GitHub, DockerHub, and other popular web services. And it can be easily extended to support your own services.

The [design introduction](https://azure.github.io/brigade/topics/design.html) introduces Brigade concepts and architecture.

Related Projects

- [Kashti](https://github.com/Azure/kashti) - a dashboard for your Brigade pipelines.
- [Brigadeterm](https://github.com/slok/brigadeterm) - a simple terminal ui for brigade pipelining system.
- [Brigade exporter](https://github.com/slok/brigade-exporter) - a [Prometheus](https://prometheus.io/) exporter to gather metrics from Brigade.

Gateways

- [BitBucket events](https://github.com/lukepatrick/brigade-bitbucket-gateway): Gateway Support for BitBucket repositories
- [GitLab events](https://github.com/lukepatrick/brigade-gitlab-gateway): Gateway Support for GitLab repositories
- [Kubernetes events](https://github.com/azure/brigade-k8s-gateway): Gateway that listens to Kubernetes event stream
- [Event Grid gateway](https://github.com/radu-matei/brigade-eventgrid-gateway): Gateway for Azure Event Grid events
- [Cron Gateway](https://github.com/technosophos/brigade-cron): Schedule events to run at a particular time
- [Trello and Generic Webhooks](https://github.com/technosophos/brigade-trello): Experimental gateway for Trello and for generic webhooks
- [Draft Pack for Building Custom Gateways](https://github.com/technosophos/draft-brigade): Build your own gateway in [5 minutes](http://technosophos.com/2018/04/23/building-brigade-gateways-the-easy-way.html)

[Kashti](http://kashti.sh/) Kashti is a dashboard for your Brigade pipelines. https://github.com/Azure/kashti Brigade provides event-driven scripting for Kubernetes. With a simple JavaScript file, you can build elaborate pipelines composed of multiple containers running in parallel or serially. Among other possible applications, Brigade can be used to build highly flexible CI/CD pipelines. Kashti is a web dashboard for Brigade, helping you easily visualize and inspect your Brigade builds. Kashti gives you a deep view into your Brigade projects, scripts, and jobs.

[Brigade Kubernetes Gateway](https://github.com/Azure/brigade-k8s-gateway) Send Kubernetes events into a Brigade pipeline. This is a Brigade gateway that listens to the Kubernetes event stream and triggers events inside of Brigade.

[Brigadier: The JS library for Brigade](https://github.com/Azure/brigadier) Brigadier is the events and jobs library for Brigade. This is the core of the Brigadier library, but the Kubernetes runtime is part of Brigade itself. To run a brigade.js file in Kubernetes, it will need to be executed within Brigade. This library is useful for:
- testing brigade.js files
- extending Brigade's worker
- supporting code completion in tooling
- implementing alternative Brigade backends



---

# The Other Category

---

[podder-ai](https://github.com/podder-ai) has some tangentialy conncected material that appears to be working towards a coherent Kubernetes ML system. [Kubeb](https://github.com/podder-ai/kubeb) Kubeb (Cubeb or Cubeba) provide CLI to build and deploy a web application to Kubernetes environment Kubeb use Docker & Helm chart for Kubernetes deployment [pipeline-framework](https://github.com/podder-ai/pipeline-framework) pipeline-framework is a platform to schedule and monitor workflows based on [Apache Airflow](https://airflow.apache.org/) [pipeline-generator](https://github.com/podder-ai/pipeline-generator) Generator code for pipeline-framework. [pipeline-framework-sample](https://github.com/podder-ai/pipeline-framework-sample) This is sample project of pipeline-framework, started from pipeline-generator, and sample task is based on poc-base-sample.[poc-base-sample](https://github.com/podder-ai/poc-base-sample)Sample task implementation for Podder.ai pipeline framework. How to implement a task using poc-base repository [poc-base](https://github.com/podder-ai/poc-base) Boilerplate project for creating python task using the Pipeline-framework.

---

