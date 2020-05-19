## Confluence Backup Cleanup

### Ausführung

```bash
./clean-up.sh -n [NUMBER OF ELEMENTS] -p [PATH TO ARCHIVES]
```

Folgende Optionen stehen zur Verfügung:

| Parameter                      | Funktion                             |
| ------------------------------ | ------------------------------------ |
| `-n` \| `--number-of-elements` | Number of newest elements to be kept |
| `-p` \| `--path`               | Path to archived backup files        |
| `-h` \| `--help`               | Prints info about usage and help     |

### Nutzung

Ausführung in gleichen Verzeichnis wie das Backup

```bash
./clean-up.sh -n 3 -p .
```

Ausführung in anderem Verzeichnis als das Backup

```bash
./clean-up.sh -n 3 -p ./confluence/confluencedata/backup
```
