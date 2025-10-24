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
- ✅ Sistema de monitoreo con Prometheus + Grafana
- ✅ Agentes Node Exporter en nodos críticos
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
