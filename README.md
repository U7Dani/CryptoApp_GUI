# 🛡 CryptoApp GUI

**CryptoApp GUI** es una aplicación escrita en Python que permite experimentar y trabajar con diversos mecanismos criptográficos modernos a través de una interfaz gráfica intuitiva. Es ideal tanto para entornos educativos como profesionales, facilitando tareas como:

- 🔐 Cifrado y descifrado simétrico y asimétrico.
- 🧾 Generación de HMAC y hash.
- ✍️ Firma digital y verificación.
- 🧬 Derivación segura de claves con sal (salt).

Su objetivo es acercar la criptografía práctica a estudiantes, analistas de ciberseguridad (Blue Team), desarrolladores y entusiastas que deseen proteger información sensible de forma accesible.

---

## ⚙ Requisitos del sistema

### 🐍 Python

- Python >= 3.10

### 📦 Dependencias

Instálalas con pip:

```bash
pip install pycryptodome cryptography pyperclip
```

### ▶ Ejecución

```bash
python "CryptoApp_GUI.py"
```

---

## ✳ Funcionalidades

- 🔒 Cifrado simétrico: AES (CBC/GCM), ChaCha20, ChaCha20-Poly1305
- 🔑 Cifrado asimétrico: RSA
- ✍️ Firma digital y verificación
- 🧾 Hashing: SHA-2 y SHA-3
- 🔏 HMAC
- 🧬 Derivación de claves (PBKDF2)
- 💾 Guardado y carga de claves

---

## 🧪 Ejemplos paso a paso

### 1. 🔐 Cifrado Simétrico con AES-CBC

**Mensaje de prueba:**  
`La contraseña de acceso es 4fTu#92x!`

**Pasos:**
- Pulsa `Generate Key`
- Pulsa `Generate Nonce`
- Selecciona `AES-CBC` y `PKCS7`
- Pulsa `Encrypt`

📸  
![image](https://github.com/user-attachments/assets/dd7d75b8-5718-49e4-a2b6-c26465542326)


---

### 2. 🔏 Generar HMAC con SHA256

**Pasos:**
- Pega el mismo mensaje original
- Usa la misma clave que generaste
- Selecciona `sha256`
- Pulsa `HMAC`

📸  
![image](https://github.com/user-attachments/assets/b7e64028-9733-43b3-90db-91e63553f502)


---

### 3. 🔑 Cifrado y Descifrado con RSA

**Pasos:**
- Pulsa `Generate Key Pair`
- Guarda `private_key.pem` y `public_key.pem`
- Escribe: `Este mensaje está cifrado con clave pública RSA.`
- Selecciona `public_key.pem` y pulsa `Encrypt`
- Copia el resultado cifrado
- Selecciona `private_key.pem` y pulsa `Decrypt`

📸  
![image](https://github.com/user-attachments/assets/d66cdaba-3030-4ea8-b279-7f26cc5de643)

![image](https://github.com/user-attachments/assets/33773767-e98a-4331-8e6c-d2676594635a)

![image](https://github.com/user-attachments/assets/55d765e2-31c9-44a9-a0fa-cf6a17776a87)

---

### 4. 🧬 Derivación de clave con PBKDF2

**Pasos:**
- Selecciona `Key Size: 256`
- Pulsa `Generate Master Key`
- Pulsa `Generate Salt`
- Pulsa `Derive Key`
- Opcional: `Save Key` y `Load Key`

📸  
![image](https://github.com/user-attachments/assets/5c6a766e-892c-4d3e-bb6d-981a8dcc5c21)


---

## 💼 Casos de uso reales

- Cifrado y envío seguro de mensajes
- Verificación de integridad con HMAC
- Protección de contraseñas mediante claves derivadas
- Simulación de firma y verificación con RSA
- Herramienta educativa para formación en criptografía moderna

---

## 🙌 Agradecimientos

Gracias a **Felipe de KeepCoding** por su guía en criptografía aplicada e inspiración en el desarrollo de esta herramienta.

---

## 👨‍💻 Autor

**Daniel (@U7Dani)**  
GitHub: [https://github.com/U7Dani](https://github.com/U7Dani)

---

> _“La mejor forma de aprender criptografía es construyendo con ella.”_
