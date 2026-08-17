# Laboratory-03-Multi-Cloud-Explorer

# Laboratory 03 – Multi-Cloud Explorer

## Linux Investigation

### Operating System

The Linux server is running **Ubuntu 24.04.4 LTS (Noble Numbat)**.

**Result:**

```text
PRETTY_NAME="Ubuntu 24.04.4 LTS"
NAME="Ubuntu"
VERSION_ID="24.04"
VERSION="24.04.4 LTS (Noble Numbat)"
VERSION_CODENAME=noble
ID=ubuntu
ID_LIKE=debian
```

---

### CPU Information

The server uses an **x86_64 architecture** with **1 CPU**. The CPU is identified as an **Intel Xeon E312xx (Sandy Bridge)** running at approximately **2.00 GHz**.

**Result:**

```text
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
CPU(s):              1
Vendor ID:           GenuineIntel
Model name:          Intel Xeon E312xx (Sandy Bridge)
CPU family:          6
Model:               42
Thread(s) per core:  1
Core(s) per socket:  1
Socket(s):           1
CPU MHz:             2000.000
```

---

### Memory

The server has approximately **2.2 GiB of total memory**. At the time of the investigation, approximately **1.3 GiB was being used**, with about **964 MiB available**.

**Result:**

```text
              total        used        free      shared  buff/cache   available
Mem:           2.2Gi       1.3Gi       576Mi       5.9Mi       556Mi       964Mi
Swap:             0B          0B          0B
```

---

### Disk Space

The main filesystem `/dev/vda1` has approximately **19 GB of total disk space**. About **11 GB is currently used**, while approximately **7.5 GB is available**, resulting in **60% disk usage**.

**Result:**

```text
Filesystem      Size  Used Avail Use% Mounted on
/dev/vda1        19G   11G  7.5G  60% /
```

---

# Cloud Migration

If this Linux server were migrated to the cloud, equivalent virtual machine services could be used from each major cloud provider.

### AWS

**Service: Amazon EC2 (Elastic Compute Cloud)**

Amazon EC2 could host this Linux server as a virtual machine in AWS. The operating system, CPU, memory, storage, and networking resources could be configured according to the server's requirements.

**Equivalent service:**

> Linux Server → **Amazon EC2**

---

### Microsoft Azure

**Service: Azure Virtual Machines**

Azure Virtual Machines could be used to migrate the Linux server to Microsoft Azure. Azure supports Linux virtual machines and allows users to configure computing, storage, and networking resources.

**Equivalent service:**

> Linux Server → **Azure Virtual Machines**

---

### Google Cloud Platform

**Service: Google Compute Engine**

Google Compute Engine could host the Linux server as a virtual machine on Google Cloud. The required CPU, memory, disk storage, operating system, and networking configuration can be selected when creating the virtual machine.

**Equivalent service:**

> Linux Server → **Google Compute Engine**

---

## Evidence

The screenshots below provide evidence of the Linux investigation performed in the KillerCoda Kubernetes environment.

### Evidence 1 — Operating System

The terminal shows that the server is running **Ubuntu 24.04.4 LTS**.

![KillerCoda Operating System](screenshots/killercoda-terminal.png)

### Evidence 2 — CPU Information

The `lscpu` command shows the server's architecture, CPU count, vendor, and processor model.

![KillerCoda CPU Information](screenshots/killercoda-terminal.png)

### Evidence 3 — Memory

The `free -h` command shows approximately **2.2 GiB total memory**, **1.3 GiB used**, and **964 MiB available**.

![KillerCoda Memory](screenshots/killercoda-terminal.png)

### Evidence 4 — Disk Space

The `df -h` command shows that `/dev/vda1` has **19 GB total**, **11 GB used**, **7.5 GB available**, and **60% usage**.

![KillerCoda Disk Space](screenshots/killercoda-terminal.png)

---

## Summary

| Investigation        | Result                                                       |
| -------------------- | ------------------------------------------------------------ |
| **Operating System** | Ubuntu 24.04.4 LTS                                           |
| **Architecture**     | x86_64                                                       |
| **CPU**              | 1 × Intel Xeon E312xx (Sandy Bridge), approximately 2.00 GHz |
| **Memory**           | 2.2 GiB total                                                |
| **Memory Used**      | 1.3 GiB                                                      |
| **Memory Available** | 964 MiB                                                      |
| **Disk**             | 19 GB total                                                  |
| **Disk Used**        | 11 GB                                                        |
| **Disk Available**   | 7.5 GB                                                       |
| **Disk Usage**       | 60%                                                          |
| **AWS Migration**    | Amazon EC2                                                   |
| **Azure Migration**  | Azure Virtual Machines                                       |
| **GCP Migration**    | Google Compute Engine                                        |
