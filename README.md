# CryptojackingTrap

CryptojackingTrap is a comprehensive solution comprising multiple projects designed to identify cryptojacking malware mining any cryptocurrency on victims' machines. To use each of the following submodules, please visit the its provided link, clone the repository, and follow the specific instructions outlined in its README file.

| Submodule | Purpose |
| --- | --- |
| [listener-bitcoin](https://github.com/CryptojackingTrap/listener-bitcoin) | Listening to the Bitcoin network |
| [listener-ethereum](https://github.com/CryptojackingTrap/listener-ethereum) | Listening to the Ethereum network |
| [listener-monero](https://github.com/CryptojackingTrap/listener-monero) | Listening to the Monero network |
| [monitor](https://github.com/CryptojackingTrap/monitor) | Debugging suspicious files or processes |
| [detector](https://github.com/CryptojackingTrap/detector) | Analyzing all data to detect malicious behavior |
| [util](https://github.com/CryptojackingTrap/util) | Utilities for evaluation |
| [dataset](https://github.com/CryptojackingTrap/dataset) | Dataset for experimental evaluations |

## Research Paper

Explore the detailed insights and in-depth analysis presented in our research paper titled "CryptojackingTrap: An Evasion Resilient Nature-Inspired Algorithm to Detect Cryptojacking Malware," published in the [IEEE Transactions on Information Forensics and Security (TIFS)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206), the first-ranked journal in the security field. The paper is officially available on IEEE Xplore and can be accessed [here](https://ieeexplore.ieee.org/abstract/document/10400529). Alternatively, you can also view the paper on [Google Drive](https://drive.google.com/file/d/1S3tnV7W-uKCuCPaPyjKOKdCmmOcEPDMK/view).

In this paper, CryptojackingTrap is presented as a novel cryptojacking detection solution designed to resist most malware defense methods. The CryptojackingTrap is armed with a debugger and extensible cryptocurrency listeners and its algorithm is based on the execution of cryptocurrency hash functions: an indispensable behavior of all cryptojacking executors. This algorithm becomes aware of this specific hash execution by correlating the memory access traces of suspicious executables
with publicly available cryptocurrency P2P network data. With the advantage of this assembly-level investigation and a nature-inspired approach to triggering the detection alarm, CryptojackingTrap provides an accurate, evasion-proof technique for detecting cryptojacking. After experimental evaluation, the false
negative and false positive rates are zero, and in addition, the false positive rate is mathematically calculated as 10<sup>-20</sup>. CryptojackingTrap has an open, extensible architecture and is available to the open-source community.

## Citation
If you find this application helpful and use it in your research or projects, please cite the following papers:

````markdown
@ARTICLE{10400529,
  author={Chahoki, Atefeh Zareh and Shahriari, Hamid Reza and Roveri, Marco},
  journal={IEEE Transactions on Information Forensics and Security}, 
  title={CryptojackingTrap: An Evasion Resilient Nature-Inspired Algorithm to Detect Cryptojacking Malware}, 
  year={2024},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TIFS.2024.3353072}}

@INPROCEEDINGS{8546867,
  author={Zareh, Atefeh and Shahriari, Hamid Reza},
  booktitle={2018 15th International ISC (Iranian Society of Cryptology) Conference on Information Security and Cryptology (ISCISC)}, 
  title={BotcoinTrap: Detection of Bitcoin Miner Botnet Using Host Based Approach}, 
  year={2018},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ISCISC.2018.8546867}} 
````

## Dataset
The complete dataset referenced in the paper is available on [IEEE Dataport](https://ieee-dataport.org/documents/cryptojackingtrap).

## Maintenance

This repository is currently maintained by Atefeh Zareh ([@Atefeh-Zareh](https://github.com/Atefeh-Zareh)). If you encounter any bugs or usage issues, please feel free to create an issue on [our issue tracker](https://github.com/CryptojackingTrap/CryptojackingTrap/issues).
