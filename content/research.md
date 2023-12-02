+++
title = 'Research'
date = 2023-11-21T10:19:21-05:00
showToc = true
draft = false
+++

## "Statically Inferring Usage Bound for Infrastructure as Code"

This is an ongoing work with [Prof. Mark Santolucito](https://www.marksantolucito.com/) at Barnard College.

Presented [poster](/files/iac_bounds_poster.pdf) at Northeastern Formal Methods Meetup at Yale University in Oct. 2023.

_(Abstract)_
Infrastructure as Code (Iac) has enabled cloud customers to have more agility in creating and modifying complex deployments of cloud-provisioned resources. By writing a configuration in IaC languages such as CloudFormation, users can declaratively specify their infrastructure and CloudFormation will handle the creation of the resources. However, understanding the complexity of IaC deployments has emerged as an unsolved issue. In particular, estimating the cost of an IaC deployment requires estimating the future usage and pricing models of every cloud resource in the deployment. Gaining transparency into predicted usage/costs is a leading challenge in cloud management. Existing work either relies on historical usage metrics to predict cost, or on coarse-grain static cost analysis that ignores interactions between resources. Our key insight is that the topology of an IaC deployment imposes constraints on the usage of each resource. We propose a system for fine-grained static cost analysis that works by modeling the inter-resource interactions in an IaC deployment as a set of SMT constraints. This allows customers to have formal guarantees on the bounds of their cloud costs.


## Temporal Stream Logic (TSL)

[TSL](https://www.marksantolucito.com/papers/cav-19.pdf) is a temporal logic designed for reactive software synthesis. Since Fall 2021, I have been working with Prof. Mark Santolucito on TSL. Along with [Barnard PL Labs](https://barnard-pl-labs.github.io/), I maintain and develop [tsltools](https://github.com/barnard-PL-Labs/tsltools/), a toolset and library for processing and synthesizing TSL specifications. I am actively working on new theoretical extensions and synthesis techniques for TSL.

## Sparse Synchronous Model (SSM) and Language (SSLANG)

[SSM](https://www.cs.columbia.edu/~sedwards/papers/edwards2020sparse.pdf) is a synchronous programming model that provides precise software timing with concurrency and determinism. Since Fall 2020, along with the research group led by [Prof. Stephen Edwards](https://www.cs.columbia.edu/~sedwards/) and [John Hui](https://j-hui.com/), I have been maintaining and developing [SSLANG](https://github.com/ssm-lang/sslang), a functional programming language built atop SSM. In particular, I lead the type system group. Besides several other features, I implemented an HM(X)-style constraint-based type system.

## Causal Tracing from System Logs through Natural Language Processing

This was an undergraduate research project supervised by Prof. Junfeng Yang in Spring 2020.
The project explored applications of natural language processing models in system log analysis. In particular, we used BERT language model to trace root causes of errors for systems like Apache Web Server.