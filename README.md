# Attribution

This repository contains a **derivative work** based on the *HTA Runner* proof-of-concept originally published on *phrack.me* in November 2022.

Original work:

* Title: **HTA Runner**
* Author: Unspecified / Phrack community contributor
* Source: phrack.me
* Archived reference: [https://web.archive.org/web/20250901000000*/https://www.phrack.me/tools/2022/11/11/HTA-Runner.html](https://web.archive.org/web/20250901000000*/https://www.phrack.me/tools/2022/11/11/HTA-Runner.html)

This project **does not claim ownership, authorship, or originality** over the underlying technique, execution model, or concept demonstrated in the original publication. All foundational credit remains with the original author(s).

## Scope and Nature of Modifications

The version described in this repository is a **modified, reduced, and documented variant** created solely for educational analysis and controlled laboratory experimentation. The changes were made to better support inspection, behavioral comparison, and learning outcomes, not to enhance effectiveness in real-world environments.

Documented changes from the original include:

* **ROT13 implementation**

  * Replaced the original manual character-mapping approach with a simplified character-code-based ROT13 function.
  * Purpose: reduce code complexity and improve readability for analysis.

* **Execution timing**

  * Introduced a delay mechanism prior to later stages using a local network command.
  * Purpose: provide sufficient time for payload to be downloaded onto the machine

## Intent and Limitations

This derivative work is intended **strictly for defensive, educational, and research purposes**, such as:

* Malware analysis training
* Red-team / blue-team labs
* Understanding HTA execution mechanics in Windows

It is **not intended for deployment, operational use, or execution on production systems**. HTA files are inherently powerful and dangerous, and misuse can result in system compromise.

By using or referencing this material, the reader acknowledges that it is provided *as-is*, without warranty, and solely for lawful and ethical experimentation in isolated environments.
