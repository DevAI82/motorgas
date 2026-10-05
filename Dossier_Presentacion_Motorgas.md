# Dossier Ejecutivo: Plan de Transformación Digital & Automatización con IA para MOTOR GAS BIKE (Albacete)

---

## 1. Resumen Ejecutivo & Contexto de MOTOR GAS BIKE

**MOTOR GAS BIKE** es el concesionario y taller multimarca especializado en motocicletas líder en Albacete. Concesionario oficial y especialista de marcas premium como **KTM**, **CFMOTO**, **Kove**, **Royal Enfield**, **Husqvarna** y **GasGas**, combinando venta de motos nuevas y de ocasión, taller mecánico oficial de alta precisión y boutique para el motorista.

- **Ubicación:** Calle Casas Ibáñez, 17-19, 02005 Albacete
- **Teléfono Taller & Ventas:** `967 67 16 76`
- **Canal de Redes:** `https://www.instagram.com/motorgasbike_/?hl=es`

### Diagnóstico de los Cuellos de Botella Detectados:
1. **Dependencia Total de Instagram sin Showroom Web Indexado:** Motor Gas Bike publica contenido con frecuencia en Instagram (@motorgasbike_), pero carece de un catálogo web optimizado para búsquedas orgánicas en Google. Búsquedas con alta intención de compra en Albacete (*"concesionario KTM Albacete"*, *"comprar CFMOTO 450MT Albacete"*, *"motos segunda mano Albacete"*, *"taller de motos Albacete"*) se pierden ante la falta de una web moderna de alta conversión.
2. **Interrupción Constante en el Taller y Mostrador:** Los mecánicos en los elevadores (ajustando suspensiones WP, cambiando aceites Motorex o kits de arrastre) y los encargados de boutique no pueden atender cada llamada telefónica al 967 67 16 76 ni contestar al momento los más de 40 mensajes diarios de Instagram. Cada mensaje o llamada sin atender es un motero que acude a otro taller o tienda.
3. **Pérdida de Ventas por Respuestas Tardías en Instagram Direct:** Cuando un motero comenta en un Reel o envía un DM preguntando por el precio o financiación de una moto, cada hora de demora enfría el interés de compra.

---

## 2. La Solución en Dos Fases

```
┌─────────────────────────────────────────────────────────────┐
│ FASE 1: CAPTACIÓN INMEDIATA & ATENCIÓN 24/7 (Semanas 1-2)    │
│  • Web Showroom ultrarrápida Mobile-First (KTM & Multimarca)│
│  • Asistente Telefónico 24/7 para Taller y Tienda           │
│    (ElevenLabs en el 967 67 16 76)                          │
│  • Chatbot Omnicanal WhatsApp & Instagram DM (Zernio)       │
│  • Campañas de Meta Ads de Alta Conversión en Albacete      │
└──────────────────────────────┬──────────────────────────────┘
                               │ (Validación de métricas y citas)
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ FASE 2: CRM ESPECIALIZADO MOTOR GAS BIKE (Meses 2-3)        │
│  • Panel Dual: Venta de Motos & Gestión de Elevadores       │
│  • Ficha Técnica de la Moto por Bastidor (VIN)              │
│  • Historial de Mantenimiento Oficial (Aceite Motorex, etc.)│
│  • Disparos Post-Venta Automáticos (Revisión a los 10 meses)│
│  • Base de datos privada en Supabase con Row Level Security │
└─────────────────────────────────────────────────────────────┘
```

---

## 3. Los 4 Pilares de la Propuesta

### Pilar 1: Showroom Web Mobile-First, Frontend, Seguridad & SEO
- **Frontend Design Deportivo de Alta Fidelidad:** Siguiendo `CLAUDE FRONTEND.md`: paleta de colores oficial de competición (naranja KTM `#ff6600`, carbono y blanco racing), carga instantánea inferior a 0.8s, navegación táctil intuitiva y filtros por tipo de carnet (Carnet B/A1 125cc, Carnet A2 y Carnet A libre) y modalidad (Trail, Naked, Enduro, Scooter).
- **Auditoría de Seguridad Exhaustiva:** Alineada con `Auditoria-de-Seguridad.md`:
  - Aislamiento de variables de entorno y API keys en `.env`.
  - Base de datos blindada con políticas Row Level Security (RLS) en Supabase.
  - Implementación de cabeceras de seguridad HTTP (CSP, HSTS).
- **SEO Local Albacete:** Marcado Schema.org `MotorcycleDealer` y `AutoRepair` con geolocalización en Calle Casas Ibáñez 17-19 para copar los primeros resultados en Google Maps y búsqueda local.

### Pilar 2: Recepción Telefónica ElevenLabs + WhatsApp/Instagram Zernio
- **Asistente Telefónico para Taller y Tienda (ElevenLabs):**
  - Descolgado inmediato en el `967 67 16 76`.
  - Voz en castellano experta en motos: gestiona citas de taller consultando la disponibilidad de elevadores, informa sobre precios de revisiones oficiales, neumáticos y disponibilidad de modelos en exposición.
  - Envía automáticamente al móvil del cliente la confirmación de cita por WhatsApp con la ubicación de Google Maps.
- **Suite Omnicanal Zernio (WhatsApp & Instagram DM):**
  - Conexión con Instagram Direct de `@motorgasbike_`: auto-respuesta inmediata a comentarios en Reels solicitando información.
  - Envío automático de ficha técnica y cuota de financiación por mensaje directo.
  - Derivación fluida a WhatsApp para cerrar la prueba en tienda física.

### Pilar 3: CRM a Medida al Estilo del Salón de Peluquería
- Adaptación del modelo implementado en Salón 224:
  - **Doble Tablero Kanban:**
    1. *Embudo de Venta de Motos:* Nuevo Contacto ➔ Cita en Tienda ➔ Financiación ➔ Entrega & Matriculación.
    2. *Control de Elevadores de Taller:* Recepción ➔ En Elevador ➔ Test Dinámico & Lavado ➔ Lista para Entrega.
  - **Ficha Técnica por Número de Bastidor (VIN):** Historial completo de revisiones, viscosidad de aceites Motorex utilizados, estado de pastillas Brembo, suspensiones WP y desgaste de kit de transmisión.
  - **Fidelización Activa:** Disparo de WhatsApp automático a los 10 meses de la compra o última revisión para invitar al motero a su puesta a punto estacional o cambio de neumáticos.

### Pilar 4: Campañas de Meta Ads de Alta Conversión
- **Campañas Especializadas en el Mundo de la Moto:**
  1. *Lanzamiento de Novedades:* Vídeos cortos en formato Reel para modelos estrella como la CFMOTO 450MT o KTM 390 Duke, ofreciendo matrícula de regalo y financiación sin intereses.
  2. *Plan Renove Motorgas:* Anuncios para tasar motos usadas en 30 minutos y descontar el importe de la moto nueva.
  3. *Campañas de Taller Estacional:* Revisiones antes de verano y antes de invierno con cita directa a WhatsApp Zernio.

---

## 4. Arquitectura Técnica bajo Framework WAT

- **Capa 1: Workflows (SOPs):** Protocolos estandarizados para recepción de motos en taller, presupuestos de reparación, prueba de motos en tienda y entrega con ficha técnica completa.
- **Capa 2: Agentes de IA:**
  - `ElevenLabs Motorcycle Agent`: ASR, comprensión técnica de modelos de motos y síntesis neuronal.
  - `Zernio Omnichannel Bot`: Enrutado de mensajes de WhatsApp Business API e Instagram Graph API.
- **Capa 3: Tools Deterministas:**
  - `workshop_calendar_sync.ts`: Control de huecos de elevadores en el taller.
  - `bike_catalog_api.ts`: Consulta de fichas y stock de motos.
  - `supabase_crm`: PostgreSQL con políticas RLS para salvaguardar la privacidad de los clientes bajo el RGPD.

---

## 5. Análisis Financiero & Retorno de Inversión (ROI)

| Métrica Proyectada | Con Operativa Tradicional | Con Plataforma MOTOR GAS BIKE IA | Impacto Neto |
| :--- | :---: | :---: | :---: |
| **Atención Telefónica en Horas de Taller** | Pérdida de 20-30 llamadas/mes | **100% llamadas contestadas al instante** | Taller a pleno rendimiento |
| **Tiempo de Respuesta en Instagram DMs** | 4 a 24 horas | **< 5 segundos (24/7)** | Cero enfriamiento de leads |
| **Ventas de Motos Adicionales** | 0 | **+4 a 6 motos/mes** | +3.800€ a 5.700€ margen |
| **Retorno de Inversión Estimado (ROI)** | — | **> 850% anual** | Máxima rentabilidad |

---

## 6. Recursos & Entregables Disponibles

1. **Simulador Interactivo en Vivo:** Abrir `mockup_interactivo_motorgas.html` en el navegador para probar el asistente de voz con síntesis real, el bot de WhatsApp, el CRM de taller y la calculadora de ROI.
2. **Presentación Ejecutiva Web:** Abrir `VER_PRESENTACION_MOTORGAS.html`.
3. **Diagrama Vectorial Editable:** Abrir `arquitectura_motorgas.excalidraw` en [excalidraw.com](https://excalidraw.com).
