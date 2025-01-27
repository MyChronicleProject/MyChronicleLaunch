# MyChronicleLaunch
Repository containing launch configuration for fast MyChronicle startup

# Development
After cloning the repository, run:

```
git submodule init
git submodule update --remote
```

Run for development:
```
docker compose up --build
```

Run for porduction:
```
docker compose -f docker-compose.yaml up --build
```
