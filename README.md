tekton-headstart
# Tekton - Headstart

Based on "Tekton Pipelines Tutorial" at https://github.com/tektoncd/pipeline/blob/main/docs/tutorial.md

## 100 Tekton Pipelines Tutorial

This tutorial uses a simple `Hello World` example to show you how to:
- Create a `Task`
- Create a `Pipeline` containing your `Tasks`
- Use a `TaskRun` to instantiate and execute a `Task` outside of a `Pipeline`
- Use a `PipelineRun` to instantiate and run a `Pipeline` containing your `Tasks`

This tutorial consists of the following sections:

- [Creating and running a `Task`](#creating-and-running-a-task)
- [Creating and running a `Pipeline`](#creating-and-running-a-pipeline)

**Note:** Items requiring configuration are marked with the `#configure` annotation.
This includes Docker registries, log output locations, and other configuration items
specific to a given cloud computing service.

### 200 Before you begin

#### 100 Running on Remote Server

Before you begin this tutorial, make sure you have [installed and configured](https://github.com/tektoncd/pipeline/blob/main/docs/install.md)
the latest release of Tekton on your Kubernetes cluster, including the
[Tekton CLI](https://github.com/tektoncd/cli).

#### 200 Running on Local Server

To run this tutorial on your local workstation, see the docs for [setting up your local environment](https://github.com/tektoncd/pipeline/blob/main/docs/developers/local-setup.md).

To learn more about the Tekton entities involved in this tutorial, see [Further reading](#further-reading).

### 300 Creating and running a `Task`


More ...
