# GitHub Actions based MoveIt buildfarm

Use MoveIt on main from debains for humble and rolling on Ubuntu 22.04.

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/tylerjw/actions_buildfarm/jammy-rolling/ ./" \
            | sudo tee /etc/apt/sources.list.d/moveit-rolling.list
echo "deb [trusted=yes] https://raw.githubusercontent.com/tylerjw/actions_buildfarm/jammy-humble/ ./" \
            | sudo tee /etc/apt/sources.list.d/moveit-humble.list
```
