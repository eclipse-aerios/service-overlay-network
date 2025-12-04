
# aeriOS-Orchestrator-Overlay  
Interconnect aeriOS service components within an isolated network overlay.

---

## Description  
This component enhances security and connectivity between two or more aeriOS service components, whether they reside within the same domain or are distributed across the aeriOS continuum.  
By collaborating with the **HLO-orchestrator** and **aeros-k8s-shim** components, it establishes an encrypted network overlay, ensuring a **secure and isolated communication channel** for aeriOS services.  
Additionally, **integrated DNS resolution** simplifies service discovery, enabling seamless interaction between those components.

---

## Installation and Deployment  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/eclipse-aerios/service-overlay-network.git
```

### **2️⃣ Navigate to the Helm Chart Directory**  
```sh
cd aerios-orchestrator-overlay/helm/aerios-orchestrator-overlay
```

### **3️⃣ Review Configuration**  
Ensure that the values in `values.yaml` are set correctly before deploying.  

### **4️⃣ Deploy the Helm Chart**  
Replace `<deployment-name>` with your desired name:  
```sh
helm install <deployment-name> .
```

---

## 📂 Adding Your Files  


###  **Using the Command Line**  
If you want to add files and push an existing repository, use the following commands:  
```sh
cd existing_repo
git remote add origin https://github.com/eclipse-aerios/service-overlay-network.git
git branch -M main
git push -uf origin main
```

---

## Contributing  
For contributing, refer to the **Installation and Deployment** section above, which contains all necessary information for development and collaboration.

---

## Authors and Acknowledgments  
Developed by:  
- **Vasilis Pitsilis**  
- **Andreas Sakelaropoulos**  


