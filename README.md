# OuterSpace Helm Chart Repository

This repository contains examples of algorithm implementations in the form of Helm charts for the OuterSpace Operator. The OuterSpace Operator is a powerful tool that simplifies the deployment and management of applications on Kubernetes. You can learn more about the OuterSpace Operator [here](https://operator.outerspace.sh).

## Getting Started

To use these examples, you will need to have the OuterSpace Operator installed on your Kubernetes cluster.

### Prerequisites

- Kubernetes cluster
- Helm v3.0+
- OuterSpace Operator

### Installing Helm

If you don't have Helm installed on your workstation, you can follow the instructions [here](https://helm.sh/docs/intro/install/).

### Installing OuterSpace Operator

To install the OuterSpace Operator, please follow the instructions provided on the [official website](https://operator.outerspace.sh).

## Using the Helm Chart Examples

Once you have the prerequisites installed, you can use the Helm chart examples in this repository.

1. Clone this repository:

```bash
git clone https://github.com/Alien6-Studio/outerspace-charts.git
```

2. Navigate to the directory of the algorithm you want to deploy:

```bash
cd charts/
```

3. Deploy the Helm chart:

```bash
helm install algorithm-name .
```

Replace `algorithm-name` with the name of the algorithm you are deploying.

## Contributing

We welcome contributions! If you have an algorithm implementation you'd like to share, please feel free to open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
