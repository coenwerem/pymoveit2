```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/coenwerem/pymoveit2/noble-rolling-amd64/ ./" | sudo tee /etc/apt/sources.list.d/coenwerem_pymoveit2-noble-rolling-amd64.list
echo "yaml https://github.com/coenwerem/pymoveit2/raw/noble-rolling-amd64/local.yaml rolling" | sudo tee /etc/ros/rosdep/sources.list.d/1-coenwerem_pymoveit2-noble-rolling-amd64.list
```
