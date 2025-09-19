# Datalous
Infrastructures for machine vision data


Datalous is a data-engineering platform that builds structure around raw machine vision outputs such as videos, keypoints, and trajectories. Inspired by Daedalus, the mythic craftsman, it provides the tools and pipelines needed to transform complex spatiotemporal data into analyzable, usable formats.

```mermaid
flowchart TD
  A["Raw Machine Vision Data\n(videos, keypoints, trajectories, logs)"]
  A --> B["Datalous\n_infrastructure for machine vision data_"]

  B --> C["Data Storage & Backups"]
  B --> D["Data Handling Pipelines"]
  B --> E["Configs & Metadata"]

  C --> F["GUI Client\n(exploration & inspection)"]
  D --> G["Statistical Analysis & Visualization"]
  E --> F
  E --> G
