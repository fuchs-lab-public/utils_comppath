# utils_comppath

## Overview
+ Description: A utility library for computational pathology workflows.
+ Main Features:

`utils_comppath` provides utilities for computational pathology workflows, including integration with QuPath in Minerva using Chimera Desktop.

## QuPath in Minerva
+ Description: Use QuPath in Minerva with Chimera Desktop in OnDemand
### Log in OnDemand with Minerva account
1. Log in to [OnDemand](https://ondemand.hpc.mssm.edu).
2. Go to the 'Interactive Apps' tab and select 'Chimera Desktop'.
3. Enter Project Account and request the required Cores, Memory, and Hours.
4. After allocation, launch Chimera Desktop.

### Open QuPath in Chimera Desktop
1. Go to Application (Left Upper Corner) and open Terminal Emulator.
2. Load the QuPath module:
   ```sh
   module load qupath/0.4.3
   ```
3. Open QuPath:
   ```sh
   /hpc/packages/minerva-centos7/qupath/0.4.3/QuPath/bin/QuPath.sh
   ```
### Import Slides and Annotation
1. Create a new project.
2. Add images to the project.
3. Add annotations to the images.

+ It's easier to set up and share project with Pathologists
