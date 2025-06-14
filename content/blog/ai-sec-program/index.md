---
title: "Building an AI Security Program from the Ground Up"
description: "A practical guide to developing a security programs for AI systems, covering model discovery, risk assessment, and compliance in the AI era."
summary: "From asset discovery to compliance, learn how to build an AI security program that addresses the unique challenges of securing artificial intelligence systems."
date: 2025-02-20T10:00:00-08:00
lastmod: 2024-02-20T10:00:00-08:00
draft: false
weight: 50
categories: ["Security", "AI", "Program Management"]
tags: ["ai-security", "cybersecurity", "risk-management", "compliance", "model-security", "data-protection", "nist", "security-program"]
contributors: ["David Galiata"]
pinned: false
homepage: false
images: ["featured.jpg"]
seo:
  title: "Building an AI Security Program - Complete Guide for Security Engineers"
  description: "A guide to building AI security programs covering model discovery, risk assessment, data flows, controls, and compliance requirements."
  canonical: ""
  noindex: false
---

# Introduction

I am currently working as a security engineer who is venturing into artificial intelligence (AI) security. I've discovered that while many traditional security principles transfer to AI systems, the complexity and unique characteristics of AI require security practitioners to think differently about how we apply these principles. When I first thought of "building a program," I didn't know where to start. I started making notes, writing docs, and eventually came up with an approach. In this post I want to share my perspective on building an AI security program from the ground up, focusing on why each element matters and how they work together.

## The Foundation: Understanding Your AI Environment

The old security adage "you can't secure what you don't know" has never been more relevant than in the context of AI security. When the Log4j vulnerability sent security teams scrambling to identify vulnerable systems, many organizations learned the hard way that their asset inventories were incomplete. This same challenge exists with AI systems, but with additional layers of complexity.

Traditional asset management approaches fall short when dealing with AI systems because of their unique nature. Unlike conventional software that runs in controlled, defined environments, AI models can be embedded throughout your technology stack in ways that aren't immediately visible. An AI model might be called by multiple applications, process data from various sources, and produce outputs that feed into other systems. This interconnected nature makes traditional asset tracking insufficient.

## Building Your AI Security Foundation

### 1. Model Discovery and Cataloging

Model discovery requires a different approach than traditional asset inventory. When we inventory traditional assets, we typically look for servers, applications, and databases in known locations. However, AI models can exist in many forms across your organization. They might be running in public cloud services, embedded in third-party applications, or even operating in unofficial tools that employees have adopted without formal approval.

The real challenge isn't just finding these models; it's understanding their context. For each model, you need to understand its purpose, its data sources, and its impact on business operations. This understanding is crucial because AI models often have complex dependencies that aren't immediately apparent (or your security team is unaware of). A seemingly simple customer service chatbot might be accessing customer data, product information, and pricing systems all at once.

### 2. Risk Assessment Through an AI Lens

Risk assessment for AI systems requires us to think beyond traditional vulnerability scanning and threat modeling. When assessing AI risk, we need to consider both technical and ethical dimensions. An AI model might be technically secure but still pose risks through biased outputs or privacy violations.

Take a large language model deployed in an enterprise setting for document analysis and summary generation. Traditional security risk assessment would focus on API security, authentication, and access controls. However, with AI systems, we need to consider additional attack vectors. An attacker might use carefully crafted inputs to make the model reveal sensitive information embedded in its training data. They might probe the model's responses to reconstruct proprietary information about your business processes.

These risks become even more complex when we consider model supply chain security. Many organizations use pre-trained models from third-party vendors, then fine-tune them on internal data. This creates a new dimension of risk assessment: How do we verify the integrity of the base model? What controls exist to prevent the model from retaining sensitive information from the fine-tuning data? How can we ensure the model's behavior remains consistent and trustworthy after updates?

### 3. Understanding Data Flows in the AI Context

Data flow mapping becomes particularly important with AI systems because they often process data in unique ways. Unlike traditional applications where data flows are relatively straightforward, AI systems might transform data in ways that make it hard to track. For example, when text is converted into embeddings for natural language processing, the resulting vectors might still contain sensitive information, but in a form that's harder to identify and protect.

This complexity requires us to think about data protection at every stage: during training, inference, and output generation. We need to understand not just where data comes from and where it goes, but how it's transformed along the way and what sensitive information might be encoded in these transformations.

### 4. Implementing Effective Controls

Security controls for AI systems need to protect both the model and the data it processes. This dual protection requirement creates unique challenges. For instance, when implementing input validation for an AI model, we can't just check for SQL injection or XSS attacks, we need to consider prompt injection attacks that might manipulate the model's behavior in subtle ways.

Protecting model outputs presents another unique challenge. Unlike traditional applications, where we can define valid and invalid outputs, AI models might produce unexpected but technically valid outputs that could still pose security risks. This requires us to implement more sophisticated output validation that considers context and potential misuse.

### 5. Meeting Compliance Requirements in the AI Era

Compliance for AI systems goes beyond checking boxes on a regulatory checklist. New AI-specific regulations like the EU AI Act introduce requirements around transparency, fairness, and accountability that traditional security programs weren't designed to address. The NIST AI Risk Management Framework provides a structured approach for organizations to identify, assess, and mitigate AI-specific risks throughout the system lifecycle. This means developing new processes and controls specifically for AI governance.

## A Practical Path Forward

Starting an AI security program can feel overwhelming, but it doesn't have to be. Begin by focusing on a single business unit or application area where AI is being used. This allows you to develop and refine your approach before scaling across the organization.

Your initial focus should be on understanding the AI systems in your chosen area: their purpose, their data sources, their interactions with other systems, and their impact on business operations. This understanding will inform every other aspect of your security program.

## Looking Ahead

Every day AI systems continue to evolve, which means our security programs must evolve with them. Staying informed about new attack vectors, understanding emerging best practices, and continuously adapting our controls. But perhaps most importantly, it means maintaining a mindset of continuous learning and adaptation.

The challenge of securing AI systems isn't just technical; it's about understanding how AI changes the way we think about security. By building a program that acknowledges these differences while maintaining sound security principles, we can create effective protection for these powerful new technologies.
