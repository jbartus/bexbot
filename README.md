# bexbot

```mermaid
flowchart TD
Sun-->Biomass;
Sun-->SolarPanels;
SolarPanels-->Battery;
Battery-->Ingest;
Battery-->Pyrolizer;
Battery-->Bury;
Battery-->Drivetrain;
Biomass-->Ingest;
Ingest-->Pyrolizer;
Pyrolizer-->Char;
Char-->Bury;
Pyrolizer-->Syngas;
Syngas-->Generator;
Generator-->Battery;
```
