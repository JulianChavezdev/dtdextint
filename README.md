### Resumen del Proyecto XML/DTD

**1\. Registro de Empleados**

*   **Objetivo:** Almacenar nombre, ID, cargo y salario.
    
*   **Implementación técnica:** Uso de tres tipos de DTD:
    
    *   **Interna:** Definida en el mismo XML.
        
    *   **Externa:** En un archivo .dtd independiente.
        
    *   **Mixta:** Archivo externo + entidades internas (ej. &sucursal;).
        

**2\. Facturas de Compra**

*   **Estructura:** Jerarquía de factura -> cliente, fecha y una lista de productos.
    
*   **Detalle de productos:** Cada producto incluye nombre, cantidad y precio.
    
*   **Regla de cardinalidad:** Uso del operador + para permitir múltiples productos por factura.
    

**3\. Calendario de Eventos**

*   **Estructura:** Nodo raíz calendario con múltiples nodos evento.
    
*   **Flexibilidad:** Campos obligatorios (titulo, fecha) y campos opcionales (descripcion, ubicacion).
    
*   **Regla de cardinalidad:** Uso del operador ? para definir elementos opcionales.
    

**Simbología DTD utilizada:**

*   +: 1 o más veces (obligatorio repetir).
    
*   ?: 0 o 1 vez (opcional).
    
*   #PCDATA: Texto plano procesable.
