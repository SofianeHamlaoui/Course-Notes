# The Linux Foundation - OSS Dev Methods

## Benifits of OSS

A key feature of OSS is that anyone can freely distribute the software. As a result, most OSS is available for download on the internet without cost, but there are certainly still maintenance and management expenses. For businesses choosing to use OSS, the nil up-front licensing cost is an attractive and key policy driver for making this decision. It can lower operating expenses. For the public sector, cost is also important. In addition, other public benefits can motivate public sector use of OSS.

OSS is how modern organizations build software. Documented advantages over software built by a handful of developers include the quality of solutions generated through the diversity of ideas and communities that form around a shared challenge. Exposing the problem space to other interested organizations also provides additional human capital to tackle challenges. For example, Linux, an open source operating system, is the largest development project in the world, with thousands of people contributing to every release. Many competing companies contribute to Linux and other OSS, allowing them to leverage the work of a global community of OSS developers and shift developers from low-value work to high-value work.

Using OSS allows for product customization, advances interoperability between tools through the use of Open Standards, and improves the overall quality of the final product. Other benefits include:

### Avoiding Lock-in

When a closed-source software application becomes entrenched into an organization’s or business’s processes or products, the organization becomes beholden, or "locked-in", to that software vendor for any new features, for bug fixes, and in many cases, for receiving product support. Where a vendor is unwilling to implement a new feature, you may need to switch to an alternative – often at considerable cost. Where a particular vendor is slow to provide bug fixes or support, this can adversely affect your own timelines and may also impose a security risk.

OSS provides an advantage in that it creates open markets for providers of all types of support. Any support business with sufficient software development competencies can add new features and fix bugs in the software; OSS users can also switch to a different support provider whenever an existing company no longer meets their needs or timelines.

The flexibility of using OSS compel GC to meet user needs by modifying existing or creating new OSS. OSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.

Support for the Local Economy and Communities
Depending on the dynamics of a software industry in a particular locality, OSS use may better support local businesses in the area. Because OSS is openly available, distributable, and modifiable, a wider breadth of smaller support service businesses may provide commercial services. Rather than a single vendor providing the warranty and technical support, any competent local IT business can provide these services. Rather than a single vendor being the only party in a position to customize software, a local consulting or software development business can provide specialized versions of the software. This dynamic can directly contribute to Canadian economic growth.

Publicly available source code enables continuous and broad peer review. Whether simply publishing the completed code or opening the development process, the practice of expanding the review and testing process to a wider audience beyond the development team ensures increased software reliability and security. Developing in the open also allows for other opinions to help adjust the direction of a product to maximize its usefulness to the community it serves.

The code created by public administration belongs to the public. By developing OSS, we help populate a larger commons that cities, states, businesses, and individuals can participate in. This creates real economic value by lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed by the GC. OSS is globally recognized as a major enabler of innovation.

### Cost

The total cost of ownership for using any software application involves three over-arching categories of expenses: (1) up-front licensing and implementation costs, (2) on-going maintenance and support costs, and (3) software upgrade or transition costs.

When using OSS, the up-front licensing cost is zero (aside from internal costs of assessing the software and the licence). A OSS licence is always "open" and granted to the world, in that it licenses everyone to use the software without any fees due. Moreover, due to the fact that OSS licences grant everyone the right to redistribute the software, nearly all OSS packages are available for free download over the internet.

As well, OSS software often incurs lower on-going maintenance costs. With closed-source software, the vendor and its select business partners are quite often the only businesses able to provide adequate support (either because the software licence grants the vendor an exclusive support contract, or due to the vendor's specialized expertise with the software and its sole ability to examine and work with the source code). This can potentially undermine competitive tendering and, in some cases, result in poor support with no available alternative. OSS, on the other hand, permits anyone to install, fix, and otherwise support the software. This can allow for a more competitive tendering of support services amongst firms. With respect to software upgrades, some closed-source vendors require licensees to purchase a new licence, or pay an upgrade fee, for new versions of the software. For OSS, on the other hand, no new licence is necessary to start using a new version of the software.

The flexibility of OSS enables rapid response to changing missions and markets as well as rapid provisioning of both known and unanticipated users. Being scalable in both directions leads to a risk reduction of longer term financial implications (and potential redundant licences). Support and maintenance of OSS - as opposed to more burdensome usages of proprietary software - provides a real cost advantage where multiple copies of software are required, or when the user base grows. The total cost of ownership is shared with a community, rather than solely the GC.

### Security

One of the most misunderstood aspects of the OSS development model is the security benefits it offers. OSS security relies on genuinely hardened code that is tested by a large number of reviewers in a wide variety of circumstances. Linus Torvalds simply noted, "talk is cheap, show me the code."

When using OSS, all of the source code is openly published. This makes it difficult for anyone to surreptitiously insert malicious code. It also allows security auditors and security researchers to inspect the code for flaws. While software security is a concern for all entities, it is of paramount importance to governments. For this reason, defence and national security agencies very often use OSS. As shown in the 2008 research paper Open Source Technology and Policy gives the example of extensive use of OSS within U.S. D.o.D. and NSA and explain the security benefits:

A key factor in the attractiveness of open software in security (and national security) applications is its auditability. It is obviously harder to conceal things in open source code, while, conversely, governments may have reason to be leery of what may lurk inside proprietary code...In the U.S. context, the major proprietary vendor Microsoft is a domestic corporation, so at least the government can be expected to work out disclosure mechanisms with the vendor. However, this is a less likely scenario for foreign-held entities. For example, is Microsoft likely to disclose proprietary code to the government of Venezuela because that government wants to scrutinize Microsoft applications for security flaws or traps?

Thus, where OSS is well-developed and well-inspected by third parties, security is generally improved. There are some security risks as well, discussed below.

### Reliance on Hardening, Not Obfuscation


OSS relies on good security practices instead of obscurity. A common misconception is that hiding code helps to prevent successful attacks. As NIST standard body recommends: "System security should not depend on the secrecy of the implementation or its components." Open Source development practices rely on hardening (or improving the security of) code by making it available for peers to test and try to break, and then fixing the problems found.

OSS is not always more secure, however in both theory and practice the OSS security model has proven that it can more quickly respond to and correct security issues.

Obfuscation relies on attackers ignorance and hides poor security practices. Within five months of the source code release of InterBase version 6, a hard-coded backdoor that had existed for seven years was found by the OSS community and fixed.

Wide Peer Review

Assuming that the goal is to make secure software, it is obvious that the easiest way to find flaws in a project is to make all of the project's code completely transparent. This approach may seem counter-intuitive, if the ultimate goal is anything other than the integrity of the technology.