```bash
echo "deb [trusted=yes] https://github.com/JafarAbdi/ompl-jammy-buildfarm/raw/stable/ ./" | sudo tee /etc/apt/sources.list.d/JafarAbdi_ompl-jammy-buildfarm.list
echo "yaml https://github.com/JafarAbdi/ompl-jammy-buildfarm/raw/stable/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-JafarAbdi_ompl-jammy-buildfarm.list
```
