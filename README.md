# Azure DevOps CI/CD Sample Project

This repository demonstrates a complete Azure DevOps multi‑stage CI/CD pipeline:

- Build & Test
- Deploy to DEV
- Auto‑Promote to QA
- Manual Approval → Deploy to PROD

## Tech Stack
- .NET 8 Web API
- Azure DevOps Pipelines (YAML)
- Multi‑stage Environments

## Run Locally
dotnet restore
dotnet build
dotnet run --project src/SampleApi

## Test
dotnet test
