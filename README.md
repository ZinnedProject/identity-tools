# Cloud Foundry Identity Tools

A collection of useful standalone projects that are used as part of
the Identity Management solution of Cloud Foundry.

## Varz

A JEE Servlet application that drops into any servlet container and
exposes management data via `/varz` endpoints.

## Batch

Some batch jobs used to keep the UAA and Cloudcontroller databases
synchronized.  Deployed as a servlet application, e.g. if deployed as
`/batch` then there is a Spring Batch Admin UI and set of JSON
endpoints at that URL.