---
name: I want to add a new service
about: Used to propose the deployment of a new service
title: I would like to deploy {service name} to {provider name}
labels: service-proposal
assignees: DevinClark

---

# {Service Name}

## Table of Contents
- [Purpose](#purpose)
- [Severity](#severity)
- [Confidentiality](#confidentiality)
- [Design](#design)
- [External Dependencies](#external-dependencies)
- [Failure Modes](#failure-modes)
- [Technical](#technical)
- [Production Acceptance Critera](#production-acceptance-criteria)

## Purpose

_What does this service do?
Why do we need this?_
_Link to the code for the service_

## Suggested provider

_This will probably be heroku unless a strong case is made otherwise._

## Estimated cost to run

## Severity of outage

_Is it customer facing? internal facing? etc  what is impact of outage._

## Confidentiality

_How bad is a data leak?_

## Design

How does the thing work?

## External Dependencies

_Services this service depends on._
_API keys this service will need access to_
_Environment variable names for the API keys would be good to include too_

## Failure Modes

_what will likely break it?_

## Technical

_How is this service built and deployed?_


## Production Acceptance Criteria

_At some point, past PoC, figure out what is needed to get this to production in a healthy way. Metrics for us to monitor on to know the service is healthy._
