# HexDroid CI/CD Agent

HexDroid offers a CI / CD system geared towards AOSP-based projects.

Agent is a core component that handles pipeline execution in the CI/CD workflow.

It establishes a secure connection with the HexDroid master server for communication and task management.

The agent:

- Receives and executes CI/CD pipeline jobs
- Reports execution status and results back to the master server
- Manages local build environments and resources
- Ensures secure and isolated execution of pipeline tasks

Organizations can deploy and manage HexDroid agents on their own infrastructure:

- Full control over the execution environment
- Support for custom security policies
- Integration with internal networks and resources
- On-premises or cloud deployment flexibility

## Get started

To begin using HexDroid CI/CD system for AOSP and integrate it with your setup, please refer to the official HexDroid
documentation for
detailed setup and configuration instructions:

- [Setting up AOSP CI/CD Pipeline](https://hexdroid.com/docs/platform/ci/aosp-ci-setup)
- [HexDroid Agent](https://hexdroid.com/docs/platform/ci/agent)
