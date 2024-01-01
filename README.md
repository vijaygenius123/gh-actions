# GitHub Actions Overview

## Introduction

GitHub Actions help you automate your software development workflows in the same place you store code and collaborate on pull requests and issues. You can write individual tasks, called actions, and combine them to create a custom workflow. Workflows are custom automated processes that you can set up in your repository to build, test, package, release, or deploy any code project on GitHub.

## Concepts

### Workflows

A workflow is a configurable-automated process made up of one or more jobs. You must create a YAML file to define your workflow configuration.

### Events

An event is a specific activity that triggers a workflow run. GitHub webhooks handle the event dispatch.

### Jobs

A job is a set of steps that execute on the same runner. By default, a workflow with multiple jobs will run those jobs in parallel.

### Steps

A step is an individual task that can run commands in a job. A step can be either an action or a shell command.

### Actions

Actions are the smallest portable building block of a workflow. You can create your own actions, or use actions created by the GitHub community.
