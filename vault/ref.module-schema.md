---
id: EVNmHAhF83kPHM6dn4xWb
title: Module Schema
desc: ''
updated: 1638237294963
created: 1638237294963
---

```yml
version: 1
schemas:
- id: module
  parent: root
  namespace: true
  children:
    - quickstart
    - concepts
    - architecture
    - tips
    - faq
    - topic
    - ops
    - dev
    - changelog
    - config
    - advanced
    - best
    - design
    - qa
- id: best
  desc: | 
    Best practicess
- id: config
  desc: "How to configure the package"
- id: advanced
  pattern: adv
  desc: "Advanced topics"
- id: changelog
- id: qa
  desc: |
    How to run debugger and tests
  children:
    - debug
    - test
    - performance
- id: performance
  pattern: perf
  desc: |
    Profile performance
- id: ops
  desc: |
    Diagnose issues
  children:
    - pattern: deploy
- id: quickstart
- id: architecture
  desc: > 
    Explanations of architecture
  pattern: arch
  children: 
   - pattern: decision
   - pattern: hacks
   - pattern: wip
   - pattern: internal
   - pattern: lifecycle
- id: internal
  desc: >
    Internal details of code
- id: wip
  desc: >
    Current work in progress
- id: hacks
  desc: >
    Shortcuts taken
- id: decision
  desc: >
    Explanations of architectural decisions made
- id: design
  desc: >
    design process 
- id: dev
  desc: |
    Development related 
  children:
    - pattern: trouble
      title: "Troubleshooting"
    - pattern: cook
      title: "Cookbook"
    - pattern: build
    - pattern: run
      desc: "how to run the program"
    - pattern: errors
    - pattern: logs
- id: build
- id: concepts
  desc: basic concepts to do with the project
- id: tips
- id: faq
- id: topic
  pattern: t
  desc: important areas of a project
  namespace: true
  children:
    - quickstart
    - concepts
    - architecture
    - tips
    - faq
    - ops
    - dev
    - changelog
    - config
    - advanced
    - best
    - design
    - qa
- id: cook
- id: debug
  desc: how to debug an application
- id: test
  desc: how to test an application
```