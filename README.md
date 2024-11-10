# Problem_Set_1_Yuxiang

## System Configuration Report

**CPU Information:**
- Architecture:                         x86_64
- CPU op-mode(s):                       32-bit, 64-bit
- Byte Order:                           Little Endian
- Address sizes:                        42 bits physical, 48 bits virtual
- CPU(s):                               76
- On-line CPU(s) list:                  0-75
- Thread(s) per core:                   1
- Core(s) per socket:                   1
- Socket(s):                            76
- NUMA node(s):                         1
- Vendor ID:                            GenuineIntel
- CPU family:                           6
- Model:                                85
- Model name:                           Intel(R) Xeon(R) Gold 6252 CPU @ 2.10GHz
- Stepping:                             7
- CPU MHz:                              2099.999
- BogoMIPS:                             4199.99
- Hypervisor vendor:                    VMware
- Virtualization type:                  full
- L1d cache:                            2.4 MiB
- L1i cache:                            2.4 MiB
- L2 cache:                             76 MiB
- L3 cache:                             2.7 GiB
- NUMA node0 CPU(s):                    0-75

**Vulnerability Information:**
- Gather data sampling:                 Unknown (Dependent on hypervisor status)
- Itlb multihit:                        KVM: Mitigation: VMX unsupported
- L1tf:                                 Not affected
- Mds:                                  Not affected
- Meltdown:                             Not affected
- Mmio stale data:                      Vulnerable (Clear CPU buffers attempted, no microcode; SMT Host state unknown)
- Reg file data sampling:               Not affected
- Retbleed:                             Mitigation; Enhanced IBRS
- Spec rstack overflow:                 Not affected
- Spec store bypass:                    Mitigation; Speculative Store Bypass disabled via prctl and seccomp
- Spectre v1:                           Mitigation; usercopy/swapgs barriers and __user pointer sanitization
- Spectre v2:                           Mitigation; Enhanced / Automatic IBRS; IBPB conditional; RSB filling; PBRSB-eIBRS SW sequence; BHI SW loop, KVM SW loop
- Srbds:                                Not affected
- Tsx async abort:                      Not affected

**Flags:**  
`fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon nopl xtopology tsc_reliable nonstop_tsc cpuid tsc_known_freq pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch cpuid_fault invpcid_single ssbd ibrs ibpb stibp ibrs_enhanced fsgsbase tsc_adjust bmi1 avx2 smep bmi2 invpcid rdseed adx smap xsaveopt arat md_clear flush_l1d arch_capabilities`

**GPU Information:**
- GeForce RTX 2080 Ti

**Memory Information:**
|       | Total   | Used  | Free   | Shared | Buff/Cache | Available |
|-------|---------|-------|--------|--------|------------|-----------|
| Mem   | 275 GiB | 8.6 GiB | 225 GiB | 2.0 MiB | 40 GiB      | 264 GiB   |
| Swap  | 2.0 GiB | 0 B   | 2.0 GiB |        |            |           |

**Disk Space:**
| Filesystem                    | Size | Used | Avail | Use% | Mounted on                  |
|--------------------------------|------|------|-------|------|-----------------------------|
| overlay                        | 7.3T | 1.3T | 6.0T  | 18%  | /                           |
| tmpfs                          | 64M  | 0    | 64M   | 0%   | /dev                        |
| shm                            | 5.0G | 4.0K | 5.0G  | 1%   | /dev/shm                    |
| /dev/mapper/srv_vg-srv_lv      | 7.3T | 1.3T | 6.0T  | 18%  | /shared_data                |
| tmpfs                          | 138G | 0    | 138G  | 0%   | /proc/acpi                  |
| tmpfs                          | 138G | 0    | 138G  | 0%   | /proc/scsi                  |
| tmpfs                          | 138G | 0    | 138G  | 0%   | /sys/firmware               |
| tmpfs                          | 138G | 0    | 138G  | 0%   | /sys/devices/virtual/powercap |

**Python Version:**
- Python 3.9.7

## Python Package Requirements
To install all the packages, run:
`pip install -r requirements.txt`