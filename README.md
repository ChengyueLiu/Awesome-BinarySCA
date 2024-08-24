# BinarySCA

This is a repository for Binary Software Composition Analysis (Binary SCA) research and tools. The goal is to provide a
comprehensive overview of the field, including academic research, commercial tools, open-source projects, and other
resources related to binary-level software composition analysis.

wellcome to pull request and contribute to this repository.

## Concepts

**Software Composition Analysis (SCA)** is a crucial process in modern software development that involves identifying,
analyzing, and managing open-source and third-party components within applications. This technique helps developers and
security teams maintain an accurate inventory of software dependencies, ensure license compliance, and quickly identify
potential vulnerabilities in the software supply chain. Traditional SCA tools typically work with source code, scanning
codebases to detect and evaluate various libraries, frameworks, and other dependencies used in the software.

Building upon this concept, **Binary SCA** extends the capabilities of software composition analysis to compiled or
binary code. This approach is particularly valuable when source code is unavailable, such as with commercial
off-the-shelf (COTS) software, legacy applications, or when analyzing software from external vendors. Binary SCA tools
employ advanced techniques like pattern matching, fingerprinting, and binary diffing to identify third-party components
and their versions within compiled executables, libraries, or firmware images. By enabling the analysis of software
composition at the binary level, organizations can effectively manage their software supply chain security and
compliance, even in scenarios where access to source code is limited or non-existent.

## Research


| Paper                                                                                                                                                                                                | Publication | Year | Tool                                                               |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|------|--------------------------------------------------------------------|
| [BinaryAI: Binary Software Composition Analysis via Intelligent Binary Source Code Matching](https://arxiv.org/pdf/2401.11161)                                                                       | ICSE        | 2024 | [BinaryAI](https://www.binaryai.cn/)                               |
| [B2SFinder: Detecting Open-Source Software Reuse in COTS Software](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=B2SFinder%3A+Detecting+Open-Source+Software+Reuse+in+COTS+Software&btnG=) | ASE         | 2019 | [B2SFinder](https://github.com/1dayto0day/B2SFinder)               |
| [Identifying open-source license violation and 1-day security risk at large scale](https://dl.acm.org/doi/pdf/10.1145/3133956.3134048)                                                               | CCS         | 2017 | [OSSPolice](https://github.com/osssanitizer/osspolice/tree/master) |

