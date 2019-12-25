# DockerAUR
Repo of scripts to download applications from the Arch User Repository (AUR) and execute them.

## Example
Let's say we want to download Firefox from the AUR. Then,
```bash
./pkg-install firefox
```
To run graphically,
```bash
./dockergui firefox
```
## Dependencies
For the download script:
- Docker
- Python >= 3.6

For the graphical executer:
- Xephyr
- ratpoison (optional)
