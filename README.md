```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/coenwerem/pymoveit2/jammy-humble-amd64/ ./" | sudo tee /etc/apt/sources.list.d/coenwerem_pymoveit2-jammy-humble-amd64.list
echo "yaml https://github.com/coenwerem/pymoveit2/raw/jammy-humble-amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-coenwerem_pymoveit2-jammy-humble-amd64.list
```
