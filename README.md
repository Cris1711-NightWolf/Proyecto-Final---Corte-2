# 🚀 Proyecto Final - Segundo Corte: Infraestructura de Red y Virtualización

## 📋 Descripción del Proyecto

Este proyecto implementa una **infraestructura DevOps/NetOps completa** para una empresa tecnológica, combinando **virtualización, redes VLAN, contenedores Docker y sistemas de monitoreo** para crear un entorno corporativo segmentado y escalable.

---

## 🏗️ Arquitectura Implementada

### 🔧 Componentes Principales

- **🖥️ Máquinas Virtuales (KVM/QEMU)**
	  - Debian → Administrador del sistema
	    - Arch Linux → Recursos Humanos
		  - Rocky Linux → Tecnología
		    - Kali Linux → Seguridad

- **🐳 Contenedores Docker**
	  - Fedora → Comercial y Ventas
	    - CentOS → Recursos Humanos
		  - Ubuntu/Alpine → Finanzas

- **🌐 Infraestructura de Red**
	  - Switch Cisco 2960 con VLANs
	    - Bridges Linux para segmentación
		  - Comunicación inter-VLAN
		    - Configuración de gateways y rutas

---

## 🎯 Objetivos Cumplidos

### ✅ Implementados
- ✅ Configuración de VLANs corporativas
- ✅ Comunicación entre máquinas virtuales
- ✅ Segmentación lógica por dependencias
- ✅ Documentación técnica completa

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Tecnologías |
|-----------|-------------|
| **Virtualización** | KVM/QEMU, Virt-Manager |
| **Contenedores** | Docker, Docker Networks |
| **Redes** | Cisco IOS, VLANs, Bridges, iptables |
| **Monitoreo** | Prometheus, Grafana, Node Exporter |
| **Sistemas** | Debian, Arch Linux, Rocky Linux, Fedora |

---

## 📁 Estructura del Proyecto

proyecto_final/
├── 📄 Documentación Overleaf/
├── 🔧 Scripts de configuración/
├── 🐳 Dockerfiles/
├── 📊 Dashboards Grafana/
├── 🔍 Capturas de red/
└── 📋 Reportes técnicos/

---

## 🔗 Conectividad y VLANs

| VLAN | Dependencia | Subnet | Propósito |
|------|-------------|---------|-----------|
| **VLAN 10** | Recursos Humanos | 10.0.10.0/24 | Gestión de personal |
| **VLAN 20** | Tecnología | 10.0.20.0/24 | Infraestructura TI |
| **VLAN 30** | Finanzas | 10.0.30.0/24 | Operaciones financieras |
| **VLAN 40** | Comercial | 10.0.40.0/24 | Ventas y marketing |
| **VLAN 99** | Management | 10.0.1.0/24 | Administración |

---

## 📊 Sistema de Monitoreo

### 🎛️ Métricas Recopiladas

- **CPU Usage** 🖥️
- **Memory Utilization** 💾
- **Disk I/O** 💽
- **Network Traffic** 🌐
- **Container Metrics** 🐳

### 📈 Dashboards Implementados
- Node Exporter Full (ID: 1860)
- Métricas personalizadas por dependencia
- Alertas y thresholds configurados

---

## 🚀 Cómo Ejecutar

### Prerrequisitos

sudo apt install qemu-kvm libvirt-daemon-system virt-manager

sudo apt install docker.io docker-compose

sudo apt install bridge-utils vlan

---

## 📸 Evidencias

El proyecto incluye capturas de:

- 🔧 Configuración del switch Cisco
- 🌐 Comunicación entre VLANs
- 📊 Dashboards de Grafana
- 🐳 Contenedores en ejecución
- 🔍 Pruebas de conectividad

---

## 👥 Autores

- Yojan Contreras
- Cristian Losada

## 👨‍🏫 Docente:

- Ing. Diego Alejandro Barragán Vargas

## 🏫 Institución:

- Universidad Santo Tomás
- Facultad de Ingeniería Electrónica
- Bogotá D.C., Octubre 2025

### ⭐ ¡Si este proyecto te parece útil, no olvides darle una estrella en GitHub!

##### "De la teoría a la práctica: construyendo el futuro de la infraestructura TI" 🚀
