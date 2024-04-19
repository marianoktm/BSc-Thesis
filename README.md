# GPGPU virtualization: design, development and evaluation of HPC, IoT and edge computing middleware
BSc thesis in Computer Science

* **Author**: Mariano Aponte <br />
* **Supervisor**: Prof. Raffaele Montella, Associate Professor of University of Naples Parthenope <br />
* **Co-Supervisor**: Prof. Sokol Kosta, Associate Professor of Aalborg University <br />
* **University**: University of Naples Parthenope <br />
* **Dissertation Date**: April 18, 2024

## Abstract

Hardware virtualization is vital in High-Performance Computing and Cloud Computing scenarios. It allows an easy and cost-effective way to address the challenges of resource allocation, scalability, and performance isolation in shared environments. Since the rise of GPGPU-accelerated HPC Clusters, the research in the hardware virtualization field has focused more and more on GPGPU virtualization, and different solutions have sprung to life. In this work, we will explore the details of the Generalized Virtualization Service "GVirtuS," a transparent virtualization solution with the advantage of a framework designed in a plug-in style that allows easy development and choice of communicators and stub libraries. Firstly, we will briefly discuss GVirtuS's implementation and design choices. Furthermore, we will analyze the differences with similar solutions found by other researchers. Moreover, we will show how GVirtuS's performance was improved through the development and optimization of a novel RDMA-based communicator. We will then evaluate the performances of the communicator through the CUDA implementation of two foundational operations that underpin AI calculations: SAXPY and Matrix Multiplication. As we will see, our novel RDMA Communicator was able to achieve a 35\% performance boost over the preexisting TCP Communicator run over an Infiniband fabric and a 55\% performance boost over the same TCP Communicator run over a traditional Ethernet network. Finally, we will conclude and explore some future development goals.
