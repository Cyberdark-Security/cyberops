# 🛡️ CyberOps — Simulador de Examen Cisco CyberOps

Plataforma web de simulación de exámenes de ciberseguridad estilo Cisco CyberOps, desarrollada por **Cyberdark Security** como herramienta de entrenamiento para estudiantes de Latinoamérica.

🔗 **Demo en vivo:** [cyberops-lake.vercel.app](https://cyberops-lake.vercel.app/)

---

## 📋 ¿Qué es?

Simulador interactivo de 50 preguntas de opción múltiple que cubre los conceptos fundamentales del examen Cisco CyberOps Associate. Permite al estudiante practicar, autoevaluar su conocimiento y prepararse para la certificación.

---

## 🧠 Temas que cubre

| Área | Ejemplos de contenido |
|------|-----------------------|
| **Fundamentos SOC** | Roles, playbooks, monitoreo continuo |
| **Modelo OSI** | Capas, protocolos por capa, TCP/UDP |
| **Amenazas y ataques** | DoS/DDoS, phishing, ransomware, zero-day, APT |
| **Herramientas** | Wireshark, SIEM, IDS/IPS, NGFW, honeypot |
| **Respuesta a incidentes** | Contención, erradicación, forense digital |
| **Hardening** | MFA, least privilege, need-to-know, segmentación |
| **Análisis de red** | netstat, traceroute, nslookup, dig, syslog |
| **Conceptos clave** | CIA, IOC, baseline, ACL, VPN, NAC, patch management |

---

## ⚙️ Características

- ✅ 50 preguntas de opción múltiple
- ✅ Cada pregunta vale 1 punto (total: 50 pts)
- ✅ Resultado y puntaje al finalizar
- ✅ Opción de borrar respuestas y reintentar
- ✅ Interfaz ligera — sin instalación, corre en el navegador

---

## 🚀 Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend | HTML + CSS + JavaScript vanilla |
| Despliegue | Vercel (serverless, deploy automático) |
| Control de versiones | GitHub |

---

## 🗂️ Estructura del proyecto

```
cyberops/
├── index.html        # Aplicación completa (preguntas + lógica + estilos)
└── README.md
```

---

## 💻 Correr localmente

No requiere instalación ni dependencias:

```bash
git clone https://github.com/Cyberdark-Security/cyberops.git
cd cyberops

# Abrir directamente en el navegador
open index.html
# o en Linux:
xdg-open index.html
```

---

## 🎯 ¿Para quién es?

- Estudiantes preparándose para **Cisco CyberOps Associate**
- Participantes del programa **Cyberdark Security**
- Cualquier persona que quiera autoevaluar sus conocimientos en ciberseguridad defensiva

---

## 🚀 Roadmap

- [ ] Banco de preguntas ampliado (+200 preguntas)
- [ ] Modo examen con temporizador
- [ ] Preguntas aleatorias por sesión
- [ ] Panel de resultados con análisis por tema
- [ ] Autenticación de estudiantes
- [ ] Panel docente para seguimiento de intentos

---

## 🏢 Sobre Cyberdark Security

Proyecto de entrenamiento ofensivo y defensivo orientado a estudiantes de ciberseguridad en Latinoamérica.

---

## ⚠️ Aviso legal

Este simulador es de uso educativo. Las preguntas están basadas en conceptos públicos del examen Cisco CyberOps Associate. No garantiza resultados en el examen oficial.

---

<div align="center">
  Hecho con ❤️ por <strong>Cyberdark Security</strong> · para Latinoamérica
</div>
