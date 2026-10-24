# Drop impact on a Teflon surface — OpenFOAM 13 case

## How to run

**Step 1 – Load OpenFOAM**
```bash
source /opt/openfoam13/etc/bashrc
```

**Step 2 – Go into the case folder**
```bash
cd AM6513-MultiPhase
```

**Step 3 – Build the mesh**
```bash
blockMesh
```

**Step 4 – Check the mesh** (should end with `Mesh OK.`)
```bash
checkMesh
```

**Step 5 – Place the drop** (should end with `End`)
```bash
setFields
```

**Step 6 – Run the simulation** (0–150 ms)
```bash
foamRun
```
