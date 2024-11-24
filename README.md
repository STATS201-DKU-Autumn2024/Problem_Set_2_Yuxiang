# Problem_Set_2_Yuxiang

## System Configuration Report

### **CPU Information**
- **Architecture:** x86_64  
- **CPU op-mode(s):** 32-bit, 64-bit  
- **Address sizes:** 46 bits physical, 48 bits virtual  
- **Byte Order:** Little Endian  
- **CPU(s):** 2  
- **On-line CPU(s) list:** 0,1  
- **Vendor ID:** GenuineIntel  
- **Model name:** Intel(R) Xeon(R) CPU @ 2.20GHz  
- **CPU family:** 6  
- **Model:** 79  
- **Thread(s) per core:** 2  
- **Core(s) per socket:** 1  
- **Socket(s):** 1  
- **Stepping:** 0  
- **BogoMIPS:** 4399.99  
- **Flags:**  
  fpu, vme, de, pse, tsc, msr, pae, mce, cx8, apic, sep, mtrr, pge, mca, cmov, pat, pse36, clflush, mmx, fxsr, sse, sse2, ss, ht, syscall, nx, pdpe1gb, rdtscp, lm, constant_tsc, rep_good, nopl, xtopology, nonstop_tsc, cpuid, tsc_known_freq, pni, pclmulqdq, ssse3, fma, cx16, pcid, sse4_1, sse4_2, x2apic, movbe, popcnt, aes, xsave, avx, f16c, rdrand, hypervisor, lahf_lm, abm, 3dnowprefetch, invpcid_single, ssbd, ibrs, ibpb, stibp, fsgsbase, tsc_adjust, bmi1, hle, avx2, smep, bmi2, erms, invpcid, rtm, rdseed, adx, smap, xsaveopt, arat, md_clear, arch_capabilities  
- **Hypervisor vendor:** KVM  
- **Virtualization type:** Full  
- **L1d cache:** 32 KiB (1 instance)  
- **L1i cache:** 32 KiB (1 instance)  
- **L2 cache:** 256 KiB (1 instance)  
- **L3 cache:** 55 MiB (1 instance)  
- **NUMA node(s):** 1  
- **NUMA node0 CPU(s):** 0,1  

### **Vulnerabilities**
- **Gather data sampling:** Not affected  
- **Itlb multihit:** Not affected  
- **L1tf:** Mitigation; PTE Inversion  
- **Mds:** Vulnerable; SMT Host state unknown  
- **Meltdown:** Vulnerable  
- **Mmio stale data:** Vulnerable  
- **Reg file data sampling:** Not affected  
- **Retbleed:** Vulnerable  
- **Spec rstack overflow:** Not affected  
- **Spec store bypass:** Vulnerable  
- **Spectre v1:** Vulnerable: __user pointer sanitization and usercopy barriers only; no swapgs barriers  
- **Spectre v2:** Vulnerable; IBPB: disabled; STIBP: disabled; PBRSB-eIBRS: Not affected; BHI: Vulnerable (Syscall hardening enabled)  
- **Srbds:** Not affected  
- **Tsx async abort:** Vulnerable  

### **GPU Information**
No GPU detected.

### **Memory Information**
| **Type** | **Total** | **Used** | **Free** | **Shared** | **Buff/Cache** | **Available** |
|----------|-----------|----------|----------|------------|----------------|---------------|
| Mem      | 12 GiB    | 696 MiB  | 8.9 GiB  | 1.0 MiB    | 3.1 GiB        | 11 GiB        |
| Swap     | 0 B       | 0 B      | 0 B      |            |                |               |

### **Disk Space**
| **Filesystem** | **Size** | **Used** | **Avail** | **Use%** | **Mounted on**        |
|----------------|----------|----------|-----------|----------|-----------------------|
| overlay        | 108G     | 33G      | 76G       | 31%      | /                     |
| tmpfs          | 64M      | 0        | 64M       | 0%       | /dev                 |
| shm            | 5.8G     | 0        | 5.8G      | 0%       | /dev/shm             |
| /dev/root      | 2.0G     | 1.2G     | 820M      | 59%      | /usr/sbin/docker-init |
| tmpfs          | 6.4G     | 40K      | 6.4G      | 1%       | /var/colab           |
| /dev/sda1      | 50G      | 34G      | 17G       | 68%      | /etc/hosts           |
| tmpfs          | 6.4G     | 0        | 6.4G      | 0%       | /proc/acpi           |
| tmpfs          | 6.4G     | 0        | 6.4G      | 0%       | /proc/scsi           |
| tmpfs          | 6.4G     | 0        | 6.4G      | 0%       | /sys/firmware        |

### **Python Version**
Python 3.10.12

### **Package Installation**
To install required packages, use the following command:
```bash
pip install -r requirements.txt
```