# Proyecto Capstone 2026: LUM Natural Care

Sistema Integrado de Gestión (CRM y ERP) correspondiente a la carrera de Ingeniería en Informática de Duoc UC. Desarrollado por el equipo **BeNicAl**.

## 🏢 Sobre el Cliente

Marca chilena de cuidado personal formulada exclusivamente con ingredientes de origen natural.

* **Sitio Web:** [https://lumnaturalcare.cl](https://lumnaturalcare.cl)
* **Instagram:** [https://www.instagram.com/lumnaturalcare](https://www.instagram.com/lumnaturalcare)
* **TikTok:** [https://www.tiktok.com/@lumnaturalcare](https://www.tiktok.com/@lumnaturalcare)

## 👥 Equipo de Desarrollo

* **Benjamín González:** Product Owner
* **Alexis Margas:** Scrum Master
* **Nicolás Díaz:** Development Team

## 🛠️ Stack Tecnológico

* **Frontend:** React 19, Vite y Tailwind CSS para la interfaz web.
* **Backend:** API REST de alto rendimiento con NestJS y motor Fastify.
* **Base de Datos:** PostgreSQL gestionado a través del nivel gratuito de Supabase.
* **Despliegue y Nube:** Google Cloud Run y Artifact Registry para el alojamiento de contenedores.
* **Gestión y CI/CD:** Organización en GitHub para control de versiones, GitHub Actions para despliegues automatizados y Azure DevOps para el seguimiento de historias de usuario.

## 📂 Estructura Organizacional

El ecosistema del proyecto opera dentro de la organización de GitHub [lum-management-system](https://github.com/lum-management-system), dividiéndose en **tres repositorios independientes**:

* **`api`:** Código fuente del backend ([https://github.com/lum-management-system/api.git](https://github.com/lum-management-system/api.git)).
* **`web`:** Código fuente del frontend ([https://github.com/lum-management-system/web.git](https://github.com/lum-management-system/web.git)).
* **`documentos`:** Repositorio centralizado para informes de avance, mockups, diarios reflexivos y documentos de arquitectura ([https://github.com/lum-management-system/documentos.git](https://github.com/lum-management-system/documentos.git)).

## ⚙️ Principios de Arquitectura y Diseño

* **Screaming Architecture:** Estructura de carpetas que expone directamente los dominios del negocio (ej. `crm_clientes`, `erp_inventario`, `erp_pedidos`).
* **Principios SOLID:** Responsabilidad única en controladores y servicios, apoyado por la inversión de control de NestJS.
* **Claridad de Conceptos:** Uso de nombres descriptivos (como `validaciones`) en lugar de términos técnicos ambiguos (como `dto`) para facilitar el mantenimiento en equipo.
* **Idioma Estandarizado:** Todo el código de dominio, rutas y lógica de negocio está escrito estrictamente en español.
