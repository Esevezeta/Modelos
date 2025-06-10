# Modelos

📚 **Librería de clases en C#** para modelar una estructura orientada a objetos con interfaces, agregación y patrones de uso de colección y recursos.

---

## ✨ Características

- **Clase `Persona`** que:
  - Usa agregación con `Direccion`
  - Implementa `IComparable` (ordenación por edad)
  - Implementa `ICloneable` (clonación superficial y profunda)
- **Clase `GrupoPersonas`** que:
  - Implementa `IEnumerable` para recorrer personas
  - Implementa `IDisposable` para gestionar recursos

---

## 🧱 Estructura de clases

- `Persona.cs`  
- `Direccion.cs`  
- `GrupoPersonas.cs`

---

## 🛠 Uso en otro proyecto (ej. WinForms en Windows)

1. Cloná este repositorio o descargalo:
   ```bash
   git clone https://github.com/tu-usuario/Modelos.git
