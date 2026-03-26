# 📌 Configuración Centralizada con Quarkus

## 📖 Descripción
Este proyecto implementa una configuración centralizada en microservicios utilizando Quarkus, separando la configuración del código mediante archivos externos.

---

## 🎯 Objetivo
Aplicar configuración centralizada en microservicios para mejorar la mantenibilidad y evitar inconsistencias.

---

## 🚀 Microservicios

Se simulan dos microservicios ejecutando la aplicación con diferentes configuraciones:

- 🧑‍🎓 Microservicio Alumnos → http://localhost:8081  
- 📚 Microservicio Cursos → http://localhost:8082  

---

## ⚙️ Configuración

Se utilizaron archivos de configuración separados:

- `application.properties` → configuración general  
- `alumnos.properties` → configuración de alumnos  
- `cursos.properties` → configuración de cursos  

---

## 🧪 Ejecución
→ http://localhost:8081 
<img width="1907" height="1128" alt="image" src="https://github.com/user-attachments/assets/4c631a7d-af33-4c1a-91c3-aaaf1c339ad5" />

→ http://localhost:8082
<img width="1901" height="1065" alt="image" src="https://github.com/user-attachments/assets/1e420939-3d2c-48e5-9a67-50dc96e24155" />
