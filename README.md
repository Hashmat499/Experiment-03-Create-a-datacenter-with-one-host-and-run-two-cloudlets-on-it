 # Experiment3 CloudSim Experiment – Same MIPS, Same Execution Time

##  Overview
This repository contains a **CloudSim 3.0.3 simulation experiment** that demonstrates the execution of **two cloudlets** on **virtual machines with identical MIPS requirements**.  
Since both the cloudlets and VMs are homogeneous, the cloudlets complete execution in the **same amount of time**.

This experiment is commonly used in **Cloud Computing laboratories**, **academic projects**, and **baseline IEEE simulations**.



##  Aim
To create a datacenter with one host and execute two cloudlets on virtual machines having the same MIPS requirements such that both cloudlets take the same time to complete execution.

---

##  Objectives
- To simulate a cloud datacenter using CloudSim
- To create virtual machines with identical MIPS values
- To execute cloudlets with equal computational length
- To verify that cloudlets complete execution at the same time

---

##  Tools & Technologies
- **Java JDK**: 1.8  
- **CloudSim Toolkit**: 3.0.3  
- **IDE**: IntelliJ IDEA / Eclipse  
- **Operating System**: Windows / Linux  

---

##  System Configuration

### Datacenter Configuration
| Parameter | Value |
|---------|------|
| Datacenters | 1 |
| Hosts | 1 |
| RAM | 4096 MB |
| Storage | 1,000,000 MB |
| Bandwidth | 10,000 Mbps |
| VM Scheduler | Time-Shared |

### Virtual Machine Configuration
| Parameter | Value |
|--------|------|
| Number of VMs | 2 |
| MIPS | 1000 |
| RAM | 512 MB |
| Bandwidth | 1000 Mbps |
| VMM | Xen |
| Cloudlet Scheduler | Time-Shared |

### Cloudlet Configuration
| Parameter | Value |
|--------|------|
| Number of Cloudlets | 2 |
| Cloudlet Length | 10,000 MI |
| File Size | 300 MB |
| Output Size | 300 MB |
| Processing Elements | 1 |


## Program 
--  









##  Algorithm
1. Initialize the CloudSim library.
2. Create a datacenter with one host.
3. Create a datacenter broker.
4. Create two virtual machines with identical MIPS values.
5. Submit the virtual machines to the broker.
6. Create two cloudlets with equal computational length.
7. Assign one cloudlet to each VM.
8. Start the CloudSim simulation.
9. Record the execution start and finish times.
10. Stop the simulation and analyze the results.

---

## Execution Time Formula
Execution Time = Cloudlet Length / VM MIPS

## Sample output 

========== CLOUDLET EXECUTION RESULTS ==========
Cloudlet ID: 0 | VM ID: 0 | Start Time: 0.1 | Finish Time: 10.1
Cloudlet ID: 1 | VM ID: 1 | Start Time: 0.1 | Finish Time: 10.1



## Screenshots of exectuted output 





## Result

The experiment successfully demonstrates that cloudlets with identical computational requirements, executed on virtual machines with the same MIPS capacity, complete execution at the same time.



## Conclusion

This simulation validates the correctness and fairness of CloudSim scheduling in a homogeneous cloud environment. Equal workloads executed on equally provisioned virtual machines result in identical execution times.
