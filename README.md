# org.opengeosys.vislab.unicave

Clone required repos:

```bash
cd C:/data/unity
git clone https://github.com/ufz-vislab/org.opengeosys.vislab.unicave.git
git clone https://github.com/bilke/UniCAVE.git
```

Add to your `Packages/manifest.json`:

````json
"org.opengeosys.vislab.unicave": "file:C:/data/unity/org.opengeosys.vislab.unicave",
"com.widve.unicave": "file:C:/data/unity/UniCAVE/UniCAVE2019/Assets/UniCAVE",
``