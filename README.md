# ScaleIT Registration Sidecar Overview

Sidecar Application Registration on ETCD Key/Value Store

This repo shows how to add a simple sidecar application to your Main-application to register at ETCD (Key/Value Store https://coreos.com/etcd/ ) with Name, Icon and a little Description.

This example application uses the ScaleIT Platform Essential App-Registry built with ETCD: https://github.com/ScaleIT-ORG/sppe-app-registry-etcd

## Architecture

![Registration Sidecar Architecture Concept](https://raw.githubusercontent.com/ScaleIT-ORG/sidecar-registration-example/master/Resources/img/architecture.png)

# Installation

	Hint: Clone this repo with --recursive to get all Submodules 
	e.g. git clone --recursive https://github.com/ScaleIT-ORG/sidecar-registration-example.git

##  Usage

Run:

		- docker-compose build
		- docker-compose up
