# :snowflake: :whale: awesome-AI-kubernetes
Tools for AI, DL, ML, CV, DS, Analytics baked in the oven to be Native on [Kubernetes](http://kubernetes.io/)

For a less specialized general purpose Kubernetes list, please check [awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

Note: A lot of volunteer effort by individuals supporting OSS is represented in this list. When you can, please consider giving feedback to the authors, testing their code and filing issue reports/feature requests and hit the Star button for their project. If your favorite project is missing from this list, please let me know.

Kubernetes means "Helmsman" and originated with Google's Borg:

"Its development and design are heavily influenced by Google's Borg system, and many of the top contributors to the project previously worked on Borg. The original codename for Kubernetes within Google was Project Seven, a reference to Star Trek character Seven of Nine that is a 'friendlier' Borg. The seven spokes on the wheel of the Kubernetes logo is a nod to that codename." https://en.wikipedia.org/wiki/Kubernetes

Note: I will attempt to sprinkle in various salty sea references in this document with perhaps some borg ones as well to stay with the spirit of the Kubernetes naming genesis...



# ML designed for Kubernetes (i.e. Native Kube)


[Kubeflow](http://kubeflow.org/)  Cloud Native platform for machine learning. https://github.com/kubeflow/kubeflow

[Seldon Core](https://www.seldon.io/) Seldon Core is an open source platform for deploying machine learning models on Kubernetes https://github.com/SeldonIO/seldon-core

[Pachyderm](http://pachyderm.io/) Pachyderm is a tool for production data pipelines. If you need to chain together data scraping, ingestion, cleaning, munging, wrangling, processing, modeling, and analysis in a sane way, then Pachyderm is for you. If you have an existing set of scripts which do this in an ad-hoc fashion and you're looking for a way to "productionize" them, Pachyderm can make this easy for you. https://github.com/pachyderm/pachyderm

[Fabric for Deep Learning - FfDL, pronounced fiddle](https://developer.ibm.com/patterns/deploy-and-use-a-multi-framework-deep-learning-platform-on-kubernetes/)  Deep Learning Platform offering TensorFlow, Caffe, PyTorch etc. as a Service on Kubernetes. This repository contains the core services of the FfDL (Fabric for Deep Learning) platform. FfDL is an operating system "fabric" for Deep Learning. https://github.com/IBM/FfDL

FfDL is a collaboration platform for:

- Framework-independent training of Deep Learning models on distributed hardware
- Open Deep Learning APIs
- Common instrumentation
- Running Deep Learning hosting in user's private or public cloud

[PolyAxon](https://polyaxon.com/) Welcome to Polyaxon, a platform for building, training, and monitoring large scale deep learning applications.Polyaxon deploys into any data center, cloud provider, or can be hosted and managed by Polyaxon, and it supports all the major deep learning frameworks such as Tensorflow, MXNet, Caffe, Torch, etc. Polyaxon makes it faster, easier, and more efficient to develop deep learning applications by managing workloads with smart container and node management. And it turns GPU servers into shared, self-service resources for your team or organization https://github.com/polyaxon/polyaxon

[Machine Learning Container Templates](https://github.com/IntelAI/mlt) from [IntelAI](http://ai.intel.com/) - mlt aids in the creation of containers for machine learning jobs. It does so by making it easy to use container and kubernetes object templates.

# ML that is adapted for Kubernetes

[Pipeline.AI](https://github.com/PipelineAI/pipeline) PipelineAI: Real-Time Enterprise AI Platform https://pipeline.ai - Quickstart for Kubernetes: https://github.com/PipelineAI/pipeline/tree/master/docs/quickstart/kubernetes



# Can Spark still be Master of the Sea?

"Gentile or Jew
O you who turn the wheel and look to windward,
Consider Phlebas, who was once handsome and tall as you" [The Waste Land by T.S. Eliot](https://www.poetryfoundation.org/poems/47311/the-waste-land)

Note: Kubernetes support was integrated into Spark with the 2.3 release. It is still incomplte and missing several important features, but it is a top priority for the Spark team.

[Spark Operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) Kubernetes operator for specifying and managing the lifecycle of Apache Spark applications on Kubernetes. Spark Operator aims to make specifying and running Spark applications as easy and idiomatic as running other workloads on Kubernetes. It uses Kubernetes custom resources for specifying, running, and surfacing status of Spark applications. For a complete reference of the custom resource definitions, please refer to the API Definition. For details on its design, please refer to the design doc. It requires Spark 2.3 and above that supports Kubernetes as a native scheduler backend.


[Multi cloud Spark application service on PKS] (https://github.com/SnappyDataInc/spark-on-k8s) An Integrated and collaborative cloud environment for building and running Spark applications on PKS/Kubernetes. This project provides a streamlined way of deploying, scaling and managing Spark applications. Spark 2.3 added support for Kubernetes as a cluster manager. This project leverages Helm charts to allow deployment of common Spark application recipes - using Apache Zeppelin and/or Jupyter for interactive, collaborative workloads. It also automates logging of all events across batch jobs and Notebook driven applications to log events to shared storage for offline analysis. This project is a collaborative effort between SnappyData and Pivotal.








