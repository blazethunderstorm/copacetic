---
id: multi-platform-patching
title: Multi-Platform Patching
sidebar_label: Multi-Platform Patching
---

# Multi-Platform Patching

Copacetic supports patching container images across multiple platforms (e.g., `linux/amd64`, `linux/arm64`). When patching, it produces a summary table that helps you quickly assess the result for each target platform.

## Understanding the Results

After running a command like:

```bash
copa patch --platforms linux/amd64,linux/arm64 -i my-image:latest
