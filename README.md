# Portafolio Blue Team

![Status](https://img.shields.io/badge/Status-Active_Project-success)
![Focus](https://img.shields.io/badge/Focus-Blue_Team_%7C_SOC_%7C_Threat_Detection-blue)
![Goal](https://img.shields.io/badge/Goal-5+_Labs-orange)

Bienvenido a mi repositorio técnico de seguridad defensiva.

Este repositorio funciona como un **laboratorio vivo y en constante evolución**. Aquí documento mis prácticas, hallazgos y metodologías aplicadas en retos de plataformas de práctica como TryHackMe y LetsDefend, con el objetivo de desarrollar una sólida base técnica en análisis de alertas, triage de incidentes, uso de SIEM y respuesta ante amenazas desde la perspectiva de un analista SOC.

La dificultad de cada reto de plataforma refleja la calificación oficial de origen:

- 🟢 **Low**
- 🟡 **Medium**
- 🟠 **High**
- 🔴 **Critical**

## Aviso

Todas las prácticas se realizaron en entornos de simulación diseñados para entrenamiento de analistas SOC (simuladores de plataformas como TryHackMe y LetsDefend). Este material es exclusivamente educativo/académico.

## Tabla de Investigaciones

Los casos están divididos por sala/plataforma de origen.

### LetsDefend

| # | EventID | Alerta | Categoría | Severidad | Veredicto | Fecha |
|---|---------|--------|-----------|-----------|-----------|-------|
| 01 | [303](LetsDefend/303/303.md) | SOC325 - Unauthorized Cloud Region Access Attempt Detected | Web Attack | 🟢 Low | ✅ True Positive | 2024-09-24 |


### TryHackMe

| # | Room | Plataforma | Categoría | Dificultad | Descripción | Herramientas | Fecha |
|---|------|------------|-----------|------------|-------------|--------------|-------|
| 01 | [Payload](TryHackMe/Payload/PAYLOAD_THM.pdf) | TryHackMe | AI Supply Chain | 🟢 Easy | Investigación de un modelo de ML malicioso (pickle) que estuvo 21 días en producción y enviaba datos a un servidor externo. | Análisis de logs, Python | 2026-09-17 |
| 02 | [Snapped Phish-ing Line](TryHackMe/SnappedPhishIngLine/Snapped_Phish-ing_Line_THM.pdf) | TryHackMe | Phishing Analysis | 🟢 Easy | Análisis de correos y URLs de una campaña de phishing real, incluyendo un phishing kit, para exponer su alcance. | Terminal Linux, CyberChef | 2026-09-18 |
| 03 | [Investigating with Splunk](TryHackMe/InvestigatingWithSplunk/INVESTIGATING_WITH_SPLUNK-THM.pdf) | TryHackMe | DFIR / Log Analysis | 🟡 Medium | Análisis forense de un host Windows comprometido donde un atacante creó un backdoor. Se rastrean sus acciones mediante eventos de Windows y scripts de PowerShell ofuscados. | Splunk, CyberChef | 2026-09-20 |
| 04 | [Phishing Books](TryHackMe/PhishingBooks/PHISHING_BOOKS_THM.pdf) | TryHackMe | Phishing Analysis | 🟢 Easy | Análisis de un correo con adjunto HTML ofuscado que redirige a un portal falso, y atribución de la infraestructura a un actor conocido. | Thunderbird, CyberChef, TryDetectThis, MITRE ATT&CK Navigator | 2026-09-22 |
| 05 | [The Greenholt Phish](TryHackMe/TheGreenholtPhish/THE_GREENHOLT_PHISH_THM.pdf) | TryHackMe | Phishing Analysis / Email Forensics | 🟢 Easy | Análisis de un correo falso de transferencia bancaria: cabeceras, SPF/DMARC, IP de origen y adjunto malicioso. | Thunderbird, ABUSEIPDB, VirusTotal, dmarcian tools | 2026-10-03 |
| 06 | [The Crown Jewel](TryHackMe/TheCrownJewel/THE_CROWN_JEWEL_THM.pdf) | TryHackMe | SOC / Network Forensics | 🟢 Easy | Reconstrucción de un ataque a partir de una alerta de reverse shell: exploit RCE, ARP spoofing, robo de credenciales y exfiltración por DNS. | Wireshark, Splunk | 2026-10-04 |





---

*Este repositorio se actualiza continuamente con nuevos informes y writeups técnicos de seguridad defensiva.*# Portafolio-Blue-Team
