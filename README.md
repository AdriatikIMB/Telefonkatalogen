# Oppsett av Linux på Raspberry Pi

## Intro
Denne guiden hjelper deg med å sette opp Linux fra en ny installasjon på Raspberry Pi. Selv om mye kan gjøres med GUI, anbefales det å øve på å bruke terminalen. Etter denne guiden skal du (forhåpentligvis) ikke lenger trenge mus, tastatur eller skjerm for å styre Raspberry Pi-en, men du trenger dette nå første gangen.

**OBS:** CMD i Windows og terminalen i Linux bruker ikke alle de samme kommandoene. Sjekk tabellen på siste side for nyttige kommandoer.

## Guide

1. **Åpne terminalen** med `CTRL + ALT + T` (her skriver du kommandoene under).

2. **Se etter og installer oppdateringer** til all programvare som er installert:
   ```bash
   sudo apt update  # finner oppdateringer
   sudo apt upgrade # installerer oppdateringer
