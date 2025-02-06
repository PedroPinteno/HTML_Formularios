# 📝 HTML_Formularios - SatruxDev

Una colección completa de ejemplos de formularios HTML que demuestra las mejores prácticas, validaciones y diferentes tipos de campos de entrada.

## ✨ Características

### 🎯 Tipos de Campos
- ✏️ Campos de texto (`text`)
- 🔒 Contraseñas (`password`)
- 📝 Áreas de texto (`textarea`)
- ☑️ Casillas de verificación (`checkbox`)
- ⭕ Botones de radio (`radio`)
- 📋 Listas desplegables (`select`)
- 🔍 Campos ocultos (`hidden`)

### 🛡️ Validaciones
- 🔴 Campos requeridos (`required`)
- 📏 Patrones personalizados (`pattern`)
  - DNI español (8 números + 1 letra)
- 📊 Longitud mínima/máxima
- 🎯 Valores mínimos/máximos

### 📋 Formularios Demostrados

1. **Formulario Principal**
   - Datos personales
   - Validación de DNI
   - Mensaje de texto largo
   - Aceptación de términos
   - Origen del contacto

2. **Selección de Color**
   - Agrupación con `fieldset`
   - Opciones mutuamente excluyentes
   - Valor por defecto

3. **Preferencias de Usuario**
   - Opciones de privacidad
   - Canal de referencia
   - Múltiples selecciones

## 🛠️ Tecnologías Utilizadas

- HTML5 semántico
- Validaciones nativas del navegador
- Integración con FormsSpark
- Patrones de expresiones regulares

## 💻 Uso

1. Clona el repositorio:
```bash
git clone https://github.com/tuusuario/HTML_Formularios.git
```

2. Abre `index.html` en tu navegador

3. Prueba los diferentes formularios y validaciones

## 🔧 Personalización

### Integración con FormsSpark
1. Crea una cuenta en [FormsSpark](https://formspark.io)
2. Obtén tu URL de formulario
3. Actualiza el atributo `action` en el formulario

### Validaciones Personalizadas
```html
<!-- Ejemplo de validación de DNI -->
<input type="text" 
       pattern="[0-9]{8}[A-Za-z]{1}" 
       required>
```

### Campos Adicionales
```html
<!-- Ejemplo de campo con límites -->
<input type="number" 
       min="0" 
       max="100" 
       step="5">
```

## 📚 Mejores Prácticas Implementadas

1. **Accesibilidad**
   - Uso correcto de etiquetas `label`
   - Atributos `for` vinculados
   - Mensajes de error descriptivos

2. **Organización**
   - Agrupación lógica con `fieldset`
   - Leyendas descriptivas
   - Estructura semántica

3. **Validación**
   - Validación del lado del cliente
   - Patrones personalizados
   - Mensajes de error útiles

4. **UX/UI**
   - Campos agrupados lógicamente
   - Indicadores claros de campos requeridos
   - Feedback visual de validación

## 👤 Autor

**SatruxDev**
- Website: [satruxdev.com](https://satruxdev.com)
- GitHub: [@satruxdev](https://github.com/satruxdev)

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🎯 TODOs

- [ ] Implementar cuenta propia de FormsSpark
- [ ] Agregar más campos de formulario
- [ ] Explorar validaciones adicionales
- [ ] Añadir estilos CSS
- [ ] Implementar JavaScript para validación personalizada
