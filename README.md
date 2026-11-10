# Platform Learning

Independent learning materials about Kubernetes and **Red Hat® OpenShift® Container Platform**: practical explanations, architecture diagrams, and labs as they are verified.

This independently maintained repository contains **clear technical explanations, diagrams, exercises, and—over time—verified hands-on labs** for students, software engineers, and platform engineers.

> **Project status (November 2026):** The first conceptual lesson is available below. Other lessons, practical labs, diagrams, and videos are planned. No hands-on lab has yet been validated on a real OpenShift cluster.

## Who this is for

- **Beginners:** You know a little Linux or containers and want to understand Kubernetes and OpenShift.
- **Application developers:** You want to build, deploy, expose, configure, and troubleshoot containerized applications.
- **Platform engineers and administrators:** You want to learn OpenShift architecture, access control, Operators, storage, observability and day-2 operations.
- **Advanced practitioners:** You want to explore platform security, cluster lifecycle, and specialized infrastructure topics.

You can follow the introductory lessons without administering a cluster. Some advanced exercises will require a dedicated environment with administrator permissions.

## Learning path

| Level | Topics | What you'll be able to do |
| --- | --- | --- |
| 0. Prerequisites | Linux, containers, YAML, Kubernetes basics | Recognize fundamental resource and API concepts |
| 1. OpenShift foundations | What OpenShift is, architecture, projects, console and CLI | Explain how OpenShift relates to Kubernetes |
| 2. Application development | Workloads, images, configuration, Routes, networking, storage | Deploy and inspect common applications |
| 3. Platform operations | RBAC, security, Operators, logging, metrics, troubleshooting | Reason about operational issues and safe changes |
| 4. Advanced topics | GitOps, pipelines, lifecycle, multicluster and specialized workloads | Explore more complex platform engineering scenarios |

### Start here

**[OS-01-01 — What is Red Hat OpenShift Container Platform, and how is it different from Kubernetes?](course/01-foundations/OS-01-01-what-is-openshift.md)** — Beginner-friendly conceptual tutorial with two architecture diagrams, a technical comparison, and exercises with answers. **No cluster is required.**

## How lessons will work

Each completed tutorial is intended to include:
1. Learning objectives and prerequisites.
2. A conceptual explanation with an architecture diagram when useful.
3. Examples and commands, with exact platform versions and permissions.
4. A hands-on exercise where an appropriate environment is available.
5. Expected outcomes, troubleshooting guidance, cleanup, and knowledge checks.
6. Links to authoritative technical documentation.

Examples will be labeled so that you can distinguish **documented concepts**, **untested examples**, and **runtime-verified labs**.

## Practice environments

Different lessons require different levels of access:

| Environment | Suitable for | Important note |
| --- | --- | --- |
| [Red Hat Developer Sandbox](https://developers.redhat.com/developer-sandbox) | Developer-focused experiments without local cluster installation | Shared trial environment; quotas, lifetime and privileges are limited |
| [Red Hat OpenShift Local](https://developers.redhat.com/products/openshift-local/overview) | Local development and experimentation | Check current host requirements and available resources |
| Your own authorized test cluster | Administrator and cluster-level exercises | Use an isolated, non-production environment; plan for resource costs |

Always check the requirements stated in each lab. Some administrative tasks cannot be performed in a restricted shared Sandbox.

## Video tutorials and diagrams

The written curriculum is designed to support future video explanations and short-form lessons. Published video resources and diagrams will be linked alongside the relevant tutorials when available.

## Reliable sources

The course uses upstream and vendor documentation, including:

- [Red Hat OpenShift documentation](https://docs.redhat.com/en/documentation/openshift_container_platform)
- [Kubernetes documentation](https://kubernetes.io/docs/)
- [Red Hat Developer learning resources](https://developers.redhat.com/)

Specific tutorial pages will link to the exact documentation release used during review.

## Project development

The course is being prepared incrementally. The first published lesson uses official OpenShift Container Platform **4.22** documentation for conceptual reference. Further lessons will identify their tested environment and version. Contribution guidelines are not yet established.

## Copyright and reuse

**No public reuse license has been selected yet.** These files are visible for reading on GitHub, but the repository does not currently grant a separate license to redistribute, modify, or commercially reuse its original content. Licensing for written lessons, diagrams, and future sample code will be specified once the rights holder approves it.

**Independence and trademarks:** MSKazemi has no affiliation with Red Hat, LLC. Red Hat® and OpenShift® are trademarks of Red Hat, LLC, registered in the United States and other countries. These trademarks are used for identification purposes only and are not intended to indicate affiliation with or approval by Red Hat. This is not official Red Hat training or certification material. No Red Hat logos are used.

The technical material is educational and does not replace official product documentation or support.
