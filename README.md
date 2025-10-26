bot-apuestas-deportivas/
│
├── main.py
├── requirements.txt
├── .replit
├── replit.nix
├── README.md
├── config.json
└── betting_data.json# 🤖 Bot de Apuestas Deportivas para Telegram

Bot completo de apuestas deportivas con sistema de depósitos, retiros y panel de administración.

## 🚀 Características

- Sistema completo de apuestas deportivas
- Múltiples métodos de depósito y retiro
- Panel de administración
- Verificación de transacciones
- Persistencia de datos en JSON
- Optimizado para Replit

## 📋 Requisitos

- Python 3.8+
- Token de bot de Telegram (@BotFather)
- ID de Telegram para administrador

## ⚙️ Configuración Rápida en Replit

1. **Importa este repositorio:**
   - Ve a [replit.com](https://replit.com)
   - Crea nuevo repl → "Import from GitHub"
   - URL: `https://github.com/tuusuario/bot-apuestas-deportivas`

2. **Configura las variables de entorno:**
   - En Replit, ve a "Secrets" (candado)
   - Agrega:
     - `TELEGRAM_BOT_TOKEN`: Tu token de @BotFather
     - `ADMIN_IDS`: Tu ID de Telegram (ej: 123456789)

3. **Ejecuta el bot:**
   - Haz clic en "Run"
   - El bot estará activo y funcionando

## 🛠 Configuración Manual

```bash
# Clonar repositorio
git clone https://github.com/tuusuario/bot-apuestas-deportivas
cd bot-apuestas-deportivas

# Instalar dependencias
pip install -r requirements.txt

# Configurar variables de entorno
export TELEGRAM_BOT_TOKEN="tu_token"
export ADMIN_IDS="123456789"

# Ejecutar
python main.py
