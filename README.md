# 🎟️ TicketMaster - Venta de Entradas Online

![TicketMaster Banner](https://via.placeholder.com/1000x300.png?text=TicketMaster+🎟️)

> 🚀 **Una plataforma moderna para la venta de entradas en línea, con generación de códigos QR y verificación de pagos.**

## 📌 Características
✅ Compra de entradas en línea 📩
✅ Generación automática de códigos QR 🏷️
✅ Validación de pagos con comprobante 📸
✅ Notificación por correo electrónico 📧
✅ Interfaz intuitiva con React ⚛️
✅ Backend robusto con Django REST Framework 🐍

## 🛠️ Tecnologías Utilizadas
| Tecnología | Descripción |
|------------|------------|
| Django Rest Framework | API robusta y segura |
| React | Interfaz de usuario moderna |
| MySQL | Base de datos escalable |
| AWS S3 | Almacenamiento de comprobantes |
| JWT | Seguridad y autenticación |

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/AaronISV/ticketmaster.git
cd ticketmaster

# Instalar dependencias
pip install -r backend/requirements.txt
cd frontend && npm install

# Configurar variables de entorno
cp .env.example .env

# Ejecutar el backend
cd backend
python manage.py migrate
python manage.py runserver

# Ejecutar el frontend
cd ../frontend
npm start
```

## 📸 Vista Previa

<img src="https://via.placeholder.com/800x400.png?text=Vista+Previo+TicketMaster" alt="Vista Previa" width="100%">

## ✨ Contribuciones
¡Las contribuciones son bienvenidas! Sigue estos pasos:
1. Haz un fork del proyecto 🍴
2. Crea una rama con tu feature (`git checkout -b feature-nueva`)
3. Realiza commits significativos (`git commit -m 'Agrega nueva funcionalidad'`)
4. Haz push a tu rama (`git push origin feature-nueva`)
5. Abre un Pull Request 🚀

## 📜 Licencia
Este proyecto está bajo la licencia MIT.

---
_Desarrollado con ❤️ por [Aaron Soto Vásquez](https://github.com/AaronISV)_ 🎸
