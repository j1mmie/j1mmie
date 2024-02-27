# Beta launch todo:
- [x] Ensure bots don't get rewards or waste CPU / memory during reward processing
- [x] Cache static data
- [ ] Log monitoring
- [x] Upgrade Gamelift to Node 18
      - Amazon Linux 2023 (AL2023)
      - Install Node from DNF maybe? sudo dnf install nodejs-1:18.18.2-1.amzn2023.0.1.x86_64
      - Gamelift Server SDK version: 4.0.2



# Memory allocation improvements:
 - Avoid using UseSpriteMesh when sprite changes often

TODO: Refactor SectorGrid.cs to cache neighboring dots and isolate dot-related logic
