# **Data Models Registry**

---

The [**Data Models Registry →**](https://github.com/ceramicstudio/datamodels) is home to all of the data models that have been created by other developers in the Ceramic community which you can reuse when building your application. Using data models from the registry promotes data composability by giving your application access to existing data on the network and helps avoid unnecessarily creating new data models.

## **Available data models**

---

Visit the [**Data Models Registry →**](https://github.com/ceramicstudio/datamodels) for a full list of available data models. Although we cannot list every data model in the registry, here is a sampling of what can be found there:

| Data model                                                                                                            | Description                                                                              | Maintainer   |
| --------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------ |
| [`identity-profile-basic`](https://github.com/ceramicstudio/datamodels/tree/main/packages/identity-profile-basic)     | Stores a user's profile                                                                  | 3Box Labs    |
| [`identity-accounts-web`](https://github.com/ceramicstudio/datamodels/tree/main/packages/identity-accounts-web)       | Stores verifiable credentials that link a user's Web2 accounts to their Ceramic account  | 3Box Labs    |
| [`identity-accounts-crypto`](https://github.com/ceramicstudio/datamodels/tree/main/packages/identity-accounts-crypto) | Stores a list of CAIP-10 Links that link a user's Web3 accounts to their Ceramic account | 3Box Labs    |
| [`social-connections`](https://github.com/ceramicstudio/datamodels/tree/main/packages/social-connections)             | Stores a user's social graph                                                             | CyberConnect |

## **Adding your models to the registry**

---

If none of the data models in the Data Models Registry suit your needs, you can create new data models using the [Glaze CLI](../../../../tools/glaze/deploy-from-cli.md) or the [Glaze DevTools](../../../../tools/glaze/development.md) library. After creating your data models, you can submit them to the registry!
