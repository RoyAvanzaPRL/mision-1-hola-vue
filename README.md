# mision-1-hola-vue

Proyecto base de Vue 3 creado con Vite, Vue 3 y TypeScript.

## Descripción

Este repositorio contiene una aplicación sencilla de Vue 3 configurada con Vite y TypeScript. Incluye una estructura mínima y un componente interactivo de saludo (`HelloUser.vue`)

## Tecnologías

- Vue 3 (`^3.5.34`)
- Vite (`^8.0.12`)
- TypeScript (`~6.0.2`)
- Vue TypeScript Checker (`vue-tsc` `^3.2.8`)
- Plugin oficial de Vue para Vite (`@vitejs/plugin-vue` `^6.0.6`)

## Dependencias

- `vue`

## DevDependencies

- `@types/node`
- `@vitejs/plugin-vue`
- `@vue/tsconfig`
- `typescript`
- `vite`
- `vue-tsc`

## Requisitos

- Node.js 18 o superior
- pnpm, npm o yarn (se recomienda `pnpm` si ya lo tienes instalado)

## Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/<usuario>/mision-1-hola-vue.git
cd mision-1-hola-vue
```

2. Instala las dependencias:

```bash
pnpm install
```

> Si usas npm:
> ```bash
> npm install
> ```

> Si usas yarn:
> ```bash
> yarn install
> ```

## Ejecutar el proyecto

Para levantar el servidor de desarrollo:

```bash
pnpm dev
```

Abre `http://localhost:5173` en tu navegador para ver la aplicación.

## Build de producción

Para generar una versión de producción:

```bash
pnpm build
```

Y para previsualizar el build:

```bash
pnpm preview
```

## Estructura principal

- `index.html` - archivo principal de entrada
- `src/main.ts` - punto de arranque de la aplicación
- `src/App.vue` - componente raíz
- `src/components/HelloUser.vue` - componente interactivo de saludo
- `src/style.css` - estilos globales

