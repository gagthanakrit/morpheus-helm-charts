# Morpheus Helm Charts

A collection of Helm charts managed and deployed via **HPE Morpheus Enterprise**.

## Repository Structure


## Charts

| Chart | Description | Version |
|-------|-------------|---------|
| `whoami` | Traefik Whoami echo service for testing deployments | 0.1.0 |

## How to Deploy

These charts are deployed via **Morpheus Enterprise**:

1. Go to **Provisioning** → **Apps** → **+ Add**
2. Select the Blueprint (e.g. `Whoami Helm App`)
3. Choose the target cluster
4. Click **Complete**

## Requirements

- HPE Morpheus Enterprise with GitHub integration configured
- Target Kubernetes cluster registered in Morpheus
- Helm installed on the Morpheus Appliance

## Integration Details

- **GitHub Org:** gagthanakrit
- **Default Branch:** main
- **Morpheus Integration:** Thanakrit-GitHub
