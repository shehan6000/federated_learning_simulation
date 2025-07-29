# federated_learning_simulation


This is a simple simulation of a **federated learning system** using PyTorch. The project demonstrates how multiple clients (each with their own dataset) can train a local model independently, and how a server can aggregate those models using **Federated Averaging** to form a global model without directly accessing client data.

---

## 📌 Features

* Implements a basic **logistic regression model** in PyTorch.
* Simulates **federated learning** with:

  * Local model training on multiple clients.
  * Federated averaging of model weights.
  * Evaluation of the global model across all combined client data.
* Uses `sklearn` to generate and preprocess classification data.

---

## 🛠️ Requirements

* Python 3.7+
* PyTorch
* scikit-learn
* NumPy
