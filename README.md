# k3s-polaris

This project provides a K3S deployment of Polaris, which I created to explore Kubernetes. The deployment utilizes the [docker-polaris](https://github.com/ogarcia/docker-polaris) project and its documentation.

## Getting Started

Before getting started, please note that this deployment is specific to my environment and lacks any configurable variables. Therefore, you'll likely need to make some modifications to adapt it to your own environment. For detailed instructions on setting up and replicating my environment easily, refer to the [k3s-ansible](https://github.com/techno-tim/k3s-ansible) repository.

## Deployment

Clone repository and cd into the directory

Run the following command
  kubectl apply -f ./polaris.yml


## Contribution

Contributions are always welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.
License

This project is licensed under the MIT License.
