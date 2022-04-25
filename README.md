# Reinforcement learning algorithms for function chaining placement and routing on Edge IoT infrastructures

With the rapid deployment of smart city and Industrial Internet of Things (IIoT) applications,
video streaming and processing is a key issue as many sites are equipped with tens of
cameras collecting images and videos for different objectives such as surveillance, security,
cyber physical threats, etc. In this context, stakeholders require stringent requirements that
include high quality of video streaming with strong latency expectations to rapidly react
when an incident such as a physical intrusion. Moreover, Industrial players require efficient
deployment solutions for interconnected cameras and video analysis systems. Virtualization
techniques are being privileged for this purpose, where both the networking functions are
virtualized, using Virtualized Networks Functions (VNF) technology, and application functions
are flexibly developed for being deployed on edge nodes.

We consider IoT service chains composed by four network functions for object detection.
For an object detection application for instance, those functions include video generation,
object detection, video compression, object recognition and database update. These IoT
applications are deployed on nodes equipped with limited processing capabilities, and
interconnected with different communications techniques such as Ethernet, Bluetooth, Wifi,
Lora, etc. This heterogeneity of the processing capabilities and communications solutions
makes the orchestration and management of the deployed network services harder. We
need to investigate efficient optimizations of these resources in near real time to attend
systems with good performance (convergence time, solution's cost, etc.)

In this topic, we propose to investigate machine learning approaches with a focus on
reinforcement learning to optimize the placement and routing of the above-mentioned
chains. We already identified a approximation solution based on graph theory. This
approach is able to attend good solutions in acceptable times even for large problem
instances. Nevertheless, and for other graph architectures, this approach suffers from
solution’s quality.
Hence, we need to augment and improve the solution’s quality using reinforcement learning
techniques.
