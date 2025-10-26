# DevOps Terminal Config

Kylian Dev terminal configuration with 80+ Git, Docker & Kubernetes aliases.

## Installation

**One command:**

```bash
curl -fsSL https://raw.githubusercontent.com/devkylian/dotfiles/main/.bashrc_devops -o ~/.bashrc_devops && \
curl -fsSL https://raw.githubusercontent.com/devkylian/dotfiles/main/.bashrc_functions -o ~/.bashrc_functions && \
echo 'source ~/.bashrc_devops' >> ~/.bashrc && \
source ~/.bashrc
```

## Quick Reference

### Git
```bash
gs              # git status
gaa             # git add .
gcm "message"   # add + commit + push
gnb "branch"    # create + push branch
gup             # update from main
gl              # git log graph
```

### Docker
```bash
dps             # docker ps
dcu             # docker-compose up -d
dcd             # docker-compose down
dbash <name>    # enter container
dports          # show all ports
dclean          # complete cleanup
```

### Kubernetes
```bash
k               # kubectl
kgp             # get pods
kgs             # get services
kl <pod>        # logs -f
kex <pod>       # exec -it
```

### Utilities
```bash
find-port 3000      # find process on port
kill-port 3000      # kill process on port
mkcd mydir          # mkdir + cd
extract file.tar.gz # extract any archive
```

### Help System
```bash
help            # show menu
help git        # Git commands
help docker     # Docker commands
aliases         # list all aliases
```

## Update

```bash
curl -fsSL https://raw.githubusercontent.com/devkylian/dotfiles/main/.bashrc_devops -o ~/.bashrc_devops && \
curl -fsSL https://raw.githubusercontent.com/devkylian/dotfiles/main/.bashrc_functions -o ~/.bashrc_functions && \
source ~/.bashrc
```

## Compatibility

- Windows (Git Bash)
- macOS
- Linux

## License

MIT