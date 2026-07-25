# 📦 Portal de Compras - EL GALAN

**Sistema PWA de Gestión Digital de Compras a Proveedores**

Un portal web moderno, offline-first y sin backend para que pequeños y medianos abarroteros (y otros negocios mayoristas) gestionen digitalmente sus compras, proveedores y cartera de vencimientos.

---

## ✨ Características Principales

### 🎯 Gestión de Compras
- Registro fácil de compras con número de factura, fecha, proveedor, monto
- Cálculo automático de fecha de vencimiento basado en plazo de crédito
- Marcar compras como pagadas o pendientes
- Búsqueda y filtrado por factura, proveedor o estado
- Eliminar compras (con confirmación de seguridad)

### 👥 Gestión de Proveedores
- Registro completo: nombre, ciudad, plazo de crédito, celular, WhatsApp
- Editar proveedores existentes
- Ver todas las compras asociadas a cada proveedor
- Enlaces directos a WhatsApp para contactar al proveedor
- Acceso rápido por teléfono

### 💰 Cartera de Vencimientos
- Vista consolidada de todas las compras pendientes de pago
- Ordenadas automáticamente por fecha de vencimiento
- Estadísticas en tiempo real:
  - Compras que vencen hoy
  - Próximos 7 días
  - Próximos 30 días
  - Compras vencidas (atraso)
- Filtrado por estado (vencida, próxima, ok)
- Botón WhatsApp directo para recordar pagos

### 📊 Dashboard Ejecutivo
- Resumen visual de:
  - Total de proveedores
  - Total de compras registradas
  - Cartera pendiente (monto total)
  - Compras que vencen hoy
- Vista de compras próximas a vencer (próximos 15 días)

### 📋 Reportes
- **Reporte de Cartera**: Todas las compras pendientes con montos y vencimientos
- **Reporte de Proveedores**: Listado completo con total de compras por proveedor
- **Reporte de Vencimientos**: Análisis por período (vencidas, próximas 7 días, próximas 30 días)
- Impresión directa desde el navegador (botón 🖨️ Imprimir)

### 💾 Backup & Restore
- **Exportar a CSV**: Descarga todos tus datos en formato Excel-compatible
- **Respaldar**: Crea una copia JSON de todos los datos (fácil de restaurar)
- **Restaurar**: Carga un respaldo anterior para recuperar datos

### 📱 PWA (Progressive Web App)
- **Funciona sin internet**: Los datos se guardan localmente en tu dispositivo
- **Instalable**: Acceso directo desde pantalla de inicio (Android, iOS, PC)
- **Rápido y ligero**: No requiere servidor ni conexión backend
- **Seguro**: Todos tus datos quedan en tu dispositivo, no en la nube

---

## 🚀 Cómo Usar

### Primera Vez

1. **Abre el portal** en tu navegador
2. **Registra proveedores** (Tab: Proveedores)
   - Ingresa nombre, ciudad, plazo de crédito, celular, WhatsApp
   - Haz clic en "Guardar Proveedor"
3. **Registra compras** (Tab: Compras)
   - Selecciona proveedor
   - Ingresa número de factura, fecha, monto
   - El vencimiento se calcula automáticamente
   - Guarda la compra

### Día a Día

- **Dashboard**: Ve un resumen de tu cartera al abrir el portal
- **Cartera**: Revisa qué está por pagar en "Cartera de Vencimientos"
- **Marcar Pagado**: Cuando pagues una compra, haz clic en "✓ Pagar"
- **Contactar Proveedor**: Usa el botón 📱 WhatsApp para enviar un recordatorio

### Reportes e Impresión

1. Ve a **Reportes**
2. Elige qué reporte necesitas
3. Haz clic en 🖨️ Imprimir para generar PDF o imprimir directamente

### Backup de Datos

- **Cada semana**: Haz clic en "💾 Respaldar" para descargar un JSON
- **Ante problemas**: Carga el JSON con "♻️ Restaurar"
- **Compatibilidad Excel**: Usa "📥 Exportar Datos" para abrir en Excel

---

## 🔒 Privacidad y Seguridad

✅ **Todos tus datos quedan en tu dispositivo**
- No se envían a servidores externos
- No hay cuentas de usuario
- No hay contraseña requerida
- Borra el caché del navegador = borra los datos

⚠️ **Respaldos Importantes**
- Descarga un backup JSON regularmente
- Guarda el CSV como respaldo adicional
- Si cambias dispositivo, usa "Restaurar" para importar datos

---

## 📱 Instalación en tu Dispositivo

### Android
1. Abre el portal en Chrome
2. Verás un botón "Instalar" en la esquina inferior derecha
3. Haz clic → La app aparecerá en tu pantalla de inicio

### iPhone / iPad
1. Abre el portal en Safari
2. Toca el botón de compartir (↗️)
3. Selecciona "Añadir a pantalla de inicio"
4. La app se instalará como acceso directo

### PC / Laptop
1. Abre el portal en Chrome o Edge
2. Haz clic en el ícono de instalación (esquina superior derecha)
3. La app se abrirá en una ventana separada

---

## 🎨 Interfaz

- **Diseño responsive**: Se adapta a móvil, tablet y PC
- **Colores cálidos**: Naranja y verde para fácil lectura
- **Tablas optimizadas**: Información clara y organizada
- **Botones grandes**: Fácil de usar en touchscreen

---

## 💡 Consejos de Uso

1. **Nómina Consistente de Proveedores**: Usa siempre el mismo nombre para cada proveedor (ej: "COLOMBINA", no "Colombina" y "colombina")

2. **Plazo de Crédito**: Registra bien el plazo estándar de cada proveedor. Se aplicará por defecto en cada compra.

3. **Vencimientos**: Revisa diariamente la "Cartera de Vencimientos" para no olvidar pagos.

4. **WhatsApp**: Si ingresas el número de WhatsApp, podrás enviar recordatorios de pago con un clic.

5. **Búsqueda**: Usa la barra de búsqueda para encontrar rápidamente compras o proveedores.

6. **Filtros**: Filtra por estado (pagada/pendiente) para ver solo lo que te importa.

7. **Impresión**: Los reportes se ven bien en PDF. Usa "Imprimir a PDF" para guardar archivos.

---

## 📊 Datos que Guarda

### Cada Compra Incluye
- Proveedor (enlace a registro de proveedor)
- Número de factura (único por proveedor)
- Fecha de compra
- Monto
- Plazo de crédito (en días)
- Fecha de vencimiento (calculada automáticamente)
- Estado: Pagada / Pendiente
- Observaciones (notas adicionales)

### Cada Proveedor Incluye
- Nombre (obligatorio)
- Ciudad
- Plazo de crédito estándar (en días)
- Celular
- WhatsApp
- Observaciones

---

## ⚙️ Requisitos Técnicos

- **Navegador moderno**: Chrome, Firefox, Safari, Edge (últimas versiones)
- **Internet**: Solo para descargar el portal por primera vez
- **Almacenamiento**: ~1 MB por cada 100 compras registradas
- **Dispositivo**: Cualquier PC, tablet o smartphone

---

## 🛠️ Soporte y Actualización

Este portal fue desarrollado por **Vibras Positivas HM** como solución personalizada para EL GALAN.

Si necesitas:
- Personalización
- Soporte técnico
- Nuevas funcionalidades
- Integración con otros sistemas

Contacta al desarrollador.

---

## 📄 Términos de Uso

✅ Uso libre para el negocio
✅ Datos privados en tu dispositivo
✅ Sin límite de compras o proveedores
❌ No hay garantía de disponibilidad del servidor público (descarga una copia local)

---

## 🌟 Versión

**Portal de Compras EL GALAN v1.0**
- Lanzamiento: 2026
- Última actualización: Julio 2026

---

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**

*Soluciones digitales para negocios en Caucasia y la Región Cauca Antioqueña*
