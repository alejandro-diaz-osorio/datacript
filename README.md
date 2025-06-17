# 🔐 DATA.CRIPT

Aplicación web para encriptar y desencriptar mensajes usando AES-128 con una clave personalizada.

## Vista previa

![Preview](public\page_preview.png)

## Características

- 🔐 Cifrado AES-128 en modo CBC con padding PKCS7
- ✅ IV aleatorio
- 🔁 Función de desencriptado compatible
- ⚡ Interfaz simple y rápida

## Requisitos

- Node.js >= 18
- pnpm (opcional, recomendado)

## Instalación

```bash
git clone https://github.com/tu-usuario/datacript.git
```

```bash
cd datacript
```

```bash
pnpm install
```

## Desarrollo local

```bash
pnpm dev
```

```bash
Visita http://localhost:4321
```

## Seguridad

- El IV se genera aleatoriamente y se adjunta en el mensaje cifrado.
- La clave del usuario se ajusta a 128 bits (16 caracteres) automáticamente.
- El descifrado valida y muestra errores si la clave es incorrecta o el formato inválido.

---

#### Este proyecto es para fines educativos.