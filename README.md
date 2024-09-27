# Telefonkatalogen

## Installationsveiledning

Denne veiledningen beskriver hvordan du setter opp telefonkatalogen på Raspberry Pi.

### Krav

- Raspberry Pi med installert OS.
- Tilgang til internett.
- Grunnleggende terminalferdigheter.

### Steg for Steg Veiledning

1. **Oppsett av Raspberry Pi**
   - Følg [denne guiden](link-til-guide) for å installere Raspberry Pi OS.

2. **Aktiver SSH**
   - Åpne terminalen:
     ```bash
     sudo raspi-config
     ```
   - Naviger til `Interfacing Options` og aktiver SSH.

3. **Sett opp brannmur**
   - Installer UFW:
     ```bash
     sudo apt install ufw
     sudo ufw enable
     sudo ufw allow ssh
     ```

4. **Installer nødvendige programmer**
   ```bash
   sudo apt install python3-pip git mariadb-server
