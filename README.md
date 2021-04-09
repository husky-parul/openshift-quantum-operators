
# OpenShift Quantum Operators

## Overwiew

These operators integrates your quantum workloads on OpenShift. It provides a development environment to implement quantum algorithms and runs them either on IBM quantum computers or simulators.

## Getting started

1. OpenShift Qiskit Operator

   Operator sets up a development environment with an integrated [Jupyter Notebook](https://jupyter.org/) and pre-installed dependencies for running quantum circuits using your [IBM Quantum account](https://quantum-computing.ibm.com/) and [Qiskit](https://qiskit.org/).

   Example notebook implementing [Grover's Search Algorithm](https://qiskit.org/textbook/ch-algorithms/grover.html)

   For getting started guides, installation, deployment and test OpenShift Qiskit operator follow [here](https://github.com/qiskit-community/openshift-quantum-operators/tree/master/operators-examples/openshift-qiskit-operator).

2. Kubernetes Qiskit Operator

   Operator sets up a development environment with an integrated [Jupyter Notebook](https://jupyter.org/) and pre-installed dependencies for running quantum circuits using your [IBM Quantum account](https://quantum-computing.ibm.com/) and [Qiskit](https://qiskit.org/).
   Operator supports both plain kubernetes and OpenShift clusters

   For getting started guides, installation, deployment and test follow [here](operators-examples/kubernetes-qiskit-operator/README.md).

3. OpenShift IBM Quantum Operator

    OpenShift IBM quantum operator creates a flexible serving system for quantum circuits implemented in Qiskit.
    You can submit quantum workloads implemented in Qiskit which are executed on IBM Quantum systems and simulators. Workloads are executed as pods, orchestrated and managed by Kube APIs.

    For getting started guides, installation, deployment and test OpenShift IBM quantum operator go [here](https://github.com/qiskit-community/openshift-quantum-operators/tree/master/operators-examples/openshift-ibm-quantum-operator).

## Contributing

OpenShift quantum operators is a community driven project and we welcome contributions. Create [PR](https://github.com/qiskit-community/openshift-quantum-operators/pulls) to contribute.

## Report a Bug

For filing bugs, suggesting improvements, or requesting new features, please open an [issue](https://github.com/qiskit-community/openshift-quantum-operators/issues)
