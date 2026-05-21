# Contribuyendo a Fox Code

¡Gracias por tu interés en contribuir a **Fox Code**! 🦊

Este proyecto es open source, gratuito y hecho por y para la comunidad. Cualquier ayuda es bienvenida, ya sea reportando bugs, sugiriendo ideas o enviando código.

---

## Código de conducta

Este proyecto sigue un código de conducta basado en el respeto mutuo. No se tolera discriminación, acoso o comportamientos tóxicos. Todos somos bienvenidos aquí.

---

## Formas de contribuir

### Reportar bugs

Si encuentras un error:

1. Abre un [issue](https://github.com/jephMD/fox-code/issues/new)
2. Describe el problema con claridad
3. Incluye pasos para reproducirlo
4. Menciona tu sistema operativo y versión

### Sugerir features

¿Tienes una idea? Cuéntanos:

1. Abre un [issue](https://github.com/jephMD/fox-code/issues/new)
2. Explica qué te gustaría ver y por qué
3. Si puedes, describe cómo podría implementarse

### Enviar código (Pull Requests)

1. **Fork** el repositorio
2. Crea una rama: `git checkout -b mi-feature`
3. Haz tus cambios
4. Asegúrate de que compile: `npm run build`
5. Commit con mensaje claro: `git commit -m "feat: descripción"`
6. Push: `git push origin mi-feature`
7. Abre un **Pull Request** contra `main`

---

## Guía de estilo

### Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` — nueva funcionalidad
- `fix:` — corrección de bug
- `refactor:` — cambio sin corrección ni feature
- `docs:` — cambios en documentación
- `style:` — formato, linting
- `chore:` — tareas internas

### Código frontend (TypeScript)

- TypeScript vanilla, sin frameworks
- Clases para componentes
- Nombres en camelCase
- Preferir `const` sobre `let`
- Evitar `any` — tipar correctamente

### Código backend (Rust)

- Seguir el estilo de `rustfmt`
- Nombres en snake_case
- Documentar funciones públicas con `///`
- Manejar errores con `Result<T, E>`

---

## Desarrollo local

```bash
# Clonar
git clone https://github.com/jephMD/fox-code.git
cd fox-code

# Instalar dependencias
npm install

# Iniciar en modo desarrollo
npm run tauri dev

# Build
npm run tauri build
```

---

## ¿Dudas?

Si algo no queda claro, abre un issue o pregunta en el [discussions](https://github.com/jephMD/fox-code/discussions).

¡Gracias por hacer de Fox Code un mejor proyecto! 🚀
