# Datalous
Infrastructures for machine vision data


Datalous is a data-engineering platform that builds structure around raw machine vision outputs such as videos, keypoints, and trajectories. Inspired by Daedalus, the mythic craftsman, it provides the tools and pipelines needed to transform complex spatiotemporal data into analyzable, usable formats.


# Datalous

**Infrastructure for machine vision data**

```mermaid
flowchart TD
    A[Raw Machine Vision Data<br>(videos, keypoints, trajectories, logs)]
    A --> B[Datalous<br><i>Infrastructure for Machine Vision Data</i>]

    B --> C[Data Storage & Backups]
    B --> D[Data Handling Pipelines]
    B --> E[Configs & Metadata]

    C --> F[GUI Client<br>(exploration & inspection)]
    D --> G[Statistical Analysis & Visualization]
    E --> F
    E --> G


                ┌─────────────────────────┐
                │   Raw Machine Vision    │
                │   (boxes, keypoints,    │
                │   trajectories, logs)   │
                └───────────┬─────────────┘
                            │
                            ▼
              ┌─────────────────────────────┐
              │          Datalous           │
              └───────────┬─────────────────┘
                          │
      ┌───────────────────┼────────────────────┐
      ▼                   ▼                    ▼
┌─────────────┐    ┌──────────────┐    ┌──────────────────┐
│ Data Storage│    │ Data Handling│    │    Configs       │
│  & Backups  │    │ Pipelines    │    │   & Metadata     │
└─────────────┘    └──────────────┘    └──────────────────┘
      │                   │                    │
      └───────────┬───────┴───────────┬────────┘
                  │                   │
                  ▼                   ▼
        ┌────────────────┐    ┌─────────────────────┐
        │    GUI Client  │    │ Statistical Analysis │
        │ (exploration,  │    │   & Visualization    │
        │ inspection)    │    └─────────────────────┘
        └────────────────┘
