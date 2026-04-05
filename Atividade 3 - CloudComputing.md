## 1. Definição do Laboratório Ideal

* **Capacidade das Máquinas:** Mínimo de 4 vCPUs, 16GB de RAM e GPU dedicada com suporte a Ray Tracing.
* **Armazenamento:** 100 GB de disco SSD/Balanced para sistema operacional e softwares.
* **Sistema Operacional:** Ubuntu Pro.
* **Quantidade de Alunos:** 24 alunos + 1 professor (Total: **25 máquinas**).
* **Infraestrutura do Bloco:** Estimativa baseada em **4 laboratórios** (Total: **100 máquinas**).

---

## 2. Estimativas de Custo: Provedores Cloud

As estimativas abaixo consideram um **compromisso de 3 anos** para garantir o melhor custo-benefício institucional.

### A. Google Cloud Platform (GCP)
* **Configuração:** `g2-standard-4` | 4 vCPUs | 16 GiB RAM | GPU NVIDIA L4 | 100 GiB Disk.
* **Região:** South Carolina (us-east1).
* **Estimativa Unitária (1 máquina):** **273,28 USD / mês**
* **Estimativa Laboratório (25 máquinas):** **6.796,29 USD / mês**
* **Estimativa Bloco (100 máquinas):** **27.180,71 USD / mês**

### B. Amazon Web Services (AWS)
* **Configuração:** `g4dn.2xlarge` | 8 vCPUs | 32 GiB RAM | GPU NVIDIA T4 | 100 GiB EBS.
* **Região:** US East (Boston).
* **Estimativa Unitária (1 máquina):** **342,04 USD / mês**
* **Estimativa Laboratório (25 máquinas):** **8.551,00 USD / mês**
* **Estimativa Bloco (100 máquinas):** **34.204,00 USD / mês**

---

## 3. Comparação e Análise Técnica

| Critério | Google Cloud (GCP) | Amazon Web Services (AWS) |
| :--- | :--- | :--- |
| **GPU** | NVIDIA L4 (Mais moderna/potente) | NVIDIA T4 (Geração anterior) |
| **Performance vCPU/RAM** | 4 vCPU / 16 GB | 8 vCPU / 32 GB |
| **Custo Mensal (Bloco)** | **27.180,71 USD** | **34.204,00 USD** |

### Descrição Comparativa:
1.  **Custo-Benefício:** O **Google Cloud** apresentou um valor mensal inferior para a unidade. Embora a instância da AWS (`g4dn.2xlarge`) ofereça o dobro de memória e núcleos de processamento, para a maioria das atividades de ensino de Computação Gráfica, a GPU é o gargalo principal.
2.  **Tecnologia de GPU:** O GCP utiliza a **NVIDIA L4**, que possui arquitetura Ada Lovelace, sendo superior em performance de renderização e IA em relação à **NVIDIA T4** (arquitetura Turing) utilizada na instância selecionada da AWS.
3.  **Veredito:** Para um cenário onde o orçamento é rígido, o **GCP** oferece a melhor tecnologia de vídeo por um preço menor. A **AWS** seria justificável caso os projetos dos alunos demandassem muita memória RAM (acima de 16GB) para carregar cenas extremamente complexas.
---

## 4. Links das Estimativas
* **AWS (possui todos os serviços):** [https://calculator.aws/#/estimate?id=63ac3f1764f88587700844934fb59f7c8e862b8c](https://calculator.aws/#/estimate?id=63ac3f1764f88587700844934fb59f7c8e862b8c)
* **GCP - 1 Máquina:** [https://cloud.google.com/products/calculator?dl=CjhDaVF3TlRnd1pHSmxNQzAxTUdFNExUUXdNall0WVRNMk1TMHpNMlpsWldObE16bGlNaklRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc](https://cloud.google.com/products/calculator?dl=CjhDaVF3TlRnd1pHSmxNQzAxTUdFNExUUXdNall0WVRNMk1TMHpNMlpsWldObE16bGlNaklRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc)
* **GCP - Lab:** [https://cloud.google.com/products/calculator?dl=CjhDaVJpWWpjMVkySmhZaTFtTmpVNExUUmhZVEl0WW1VeFl5MDRZVGM0T0dNeU16TmpaR1lRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc](https://cloud.google.com/products/calculator?dl=CjhDaVJpWWpjMVkySmhZaTFtTmpVNExUUmhZVEl0WW1VeFl5MDRZVGM0T0dNeU16TmpaR1lRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc)
* **GCP - Bloco:** [https://cloud.google.com/products/calculator?dl=CjhDaVF5TURGaE1XRm1OeTFqWlRoaExUUTROV1F0WVdOa1lpMDRORE0wT0dFd1kyTmhORGdRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc](https://cloud.google.com/products/calculator?dl=CjhDaVF5TURGaE1XRm1OeTFqWlRoaExUUTROV1F0WVdOa1lpMDRORE0wT0dFd1kyTmhORGdRQVE9PRAIGiQ5N0ZDMEI1RS1CMENELTQ2REQtOTk2OS1ENEVFRDIxMDE4Njc)

---
