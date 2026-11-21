# PcAiOptimizer

PcAiOptimizer er et portabelt Windows-værktøj, der skal analysere pc’ens hardware og give anbefalinger til sikker lokal AI-kørsel — uden at ændre systemet uden eksplicit godkendelse.

## Funktioner

- Hardwareanalyse for Windows 10/11
- CPU-, RAM-, GPU-, lager- og driverdetektion
- NVIDIA-SMI/drevertjek, når værktøjet er tilgængeligt
- Anbefaling af realistisk lokal modelstørrelse og kvantisering
- Sikker visning af foretagne ændringer, før de udføres
- Eksport af læsbar tekst rapport
- Færdig portable `.exe` bygget af GitHub Actions

## Sikkerhed

Værktøjet starter i read-only tilstand. Systemændringer eller driverinstallationen må kun udføres efter en tydelig brugerbekræftelse.

## Bygning

GitHub Actions bygger den portable `.exe` automatisk på Windows. Se Releases-siden for download, når den første build er færdig.

## Status

Projektet bygges ud fra en sikker, read-only basisfunktion. Modeludvalg, benchmarks og valgfri optimeringer implementeres trinvis.
