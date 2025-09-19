# Datalous
Infrastructures for machine vision data


Datalous is a data-engineering platform that builds structure around raw machine vision outputs such as videos, keypoints, and trajectories. Inspired by Daedalus, the mythic craftsman, it provides the tools and pipelines needed to transform complex spatiotemporal data into analyzable, usable formats.


```markdown
```mermaid
flowchart TD
  A["Raw Machine Vision Data"]
  A --> B["Datalous — infrastructure for machine vision data"]
  B --> C["Data Storage & Backups"]
  B --> D["Data Handling Pipelines"]
  B --> E["Configs & Metadata"]
  C --> F["GUI Client"]
  D --> G["Statistical Analysis & Visualization"]
  E --> F
  E --> G
