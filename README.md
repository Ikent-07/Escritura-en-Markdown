# Escritura-en-Markdown
Como escribir cada cosa en Markdown (el metodo de escritura de github)

# 1. TÍTULOS

```markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

# 2. FORMATO DE TEXTO

| Resultado | Código |
|---|---|
| **Negrita** | `**Texto**` |
| *Cursiva* | `*Texto*` |
| ***Negrita y cursiva*** | `***Texto***` |
| ~~Tachado~~ | `~~Texto~~` |
| Código | `` `código` `` |
| Subíndice | `H<sub>2</sub>O` |
| Superíndice | `x<sup>2</sup>` |

# 3. LISTAS

### Lista normal

```markdown
- Manzana
- Pera
- Naranja
```

### Lista numerada

```markdown
1. Primero
2. Segundo
3. Tercero
```

### Lista con sublistas

```markdown
- Animales
  - Perro
  - Gato
- Frutas
  - Manzana
  - Pera
```

### Lista de tareas

```markdown
- [x] Aprender Markdown
- [ ] Aprender Python
- [ ] Crear un proyecto
```

# 4. BLOQUES DE CÓDIGO

### Código pequeño

```markdown
Usa `print("Hola")` para mostrar texto.
```

### Código Python

````markdown
```python
print("Hola mundo")
nombre = "Ana"
print(nombre)
```
````

### Código JavaScript

````markdown
```javascript
console.log("Hola mundo");
```
````

### Código HTML

````markdown
```html
<h1>Hola mundo</h1>
<p>Mi primera página web</p>
```
````

### Código CSS

````markdown
```css
h1 {
  color: blue;
}
```
````

### Otros lenguajes

```text
```java
```cpp
```php
```sql
```json
```bash
```typescript
```csharp
```ruby
```go
```rust
```

# 5. ENLACES

### Crear un enlace

```markdown
[Google](https://google.com)
```

### Enlace a otra página

```markdown
[GitHub](https://github.com)
```

### Enlace a una sección

```markdown
[Ir a los títulos](#1-titulos)
```

# 6. IMÁGENES

### Añadir una imagen

```markdown
![Descripción de la imagen](URL_DE_LA_IMAGEN)
```

### Imagen con enlace

```markdown
[![Descripción](URL_IMAGEN)](URL_DESTINO)
```

# 7. TABLAS

### Tabla básica

```markdown
| Nombre | Edad | Ciudad |
|---|---|---|
| Ana | 15 | Madrid |
| Luis | 16 | Sevilla |
| Pedro | 14 | Málaga |
```

### Alinear tablas

```markdown
| Izquierda | Centro | Derecha |
|:---|:---:|---:|
| Hola | Hola | Hola |
```

# 8. SEPARADORES

```markdown
---
```

También puedes utilizar:

```markdown
***
```

# 9. CITAS

### Cita normal

```markdown
> Nunca dejes de aprender.
```

### Cita dentro de otra cita

```markdown
> Primera cita
>> Segunda cita
```

# 10. COMENTARIOS HTML

Los comentarios no se muestran en el resultado visual de Markdown.

```html
<!-- Este comentario no se verá en la página -->
```

---

```html
---

<p align="left">
  <img src="https://github.com/Ikent-07.png" width="65" style="border-radius: 50%;" alt="Foto de perfil">
  <a href="https://github.com/Ikent-07">
    <strong>Ikent-07</strong>
  </a>
</p>
```
