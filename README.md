<h1 align="center">🚀 CKS - ETCD Security Essentials</h1>

---

### 🗄️ <span style="color:#FF5733;">ETCD: Plaintext Data Storage</span>

ETCD stores all Kubernetes data — including secrets — in <span style="color:#E74C3C;"><strong>plain text</strong></span>.  
That means anyone with access to the disk can read sensitive data like passwords, tokens, and keys. 🔓  
> 💡 **Tip:** Always assume disk access = full access unless encrypted.

---

### 🔐 <span style="color:#2980B9;">TLS Encryption for Data in Transit</span>

Communication between the Kubernetes API server and ETCD can be intercepted if unprotected.  
Use <span style="color:#1ABC9C;"><strong>TLS encryption</strong></span> to secure data in motion and prevent eavesdropping.  
> 📌 **Why**


