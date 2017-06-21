# hi-openshift 

hi-openshift is a hi-cli module for installing openshift cluster and deploy infrastructure services.

## Installation guide:

### 1. Prerequisite

Install [hi-cli](https://github.com/hi-cli/hi-cli)

### 2. Installation Guide

```bash
hi package install openshift
```

### 3. Update Guide

```bash
hi package update openshift
```

### 4. Usage

### 4.1 Prepare installation

```bash
hi openshift install hosts=nodes
```

### 4.2 Install openshift cluster

```bash
hi openshift install
```

### 4.2 Deploy heketi

```bash
hi openshift deploy heketi
```

### Options

```bash

verbose: verbose mode
more verbose: verbose mode for more

```
