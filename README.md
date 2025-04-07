# Reverse Proxy Demo

Dette er et komplet eksempelprojekt med **frontend**, **backend**, og en **reverse proxy med Nginx**:

---

### 🧱 Projektet indeholder:
- `frontend/index.html` – viser en hilsen og henter data fra backend via `/api`
- `backend/server.js` – svarer med JSON på `/api`
- `nginx/default.conf` – sender `/api` videre til backend og serverer statiske filer
- `docker-compose.yml` – starter alt sammen på én kommando

---

### ▶️ Sådan kører du det:

1. Pak ud og åbn en terminal i mappen
2. Kør:
   ```bash
   docker-compose up --build
   ```
3. Gå til [http://localhost:8080](http://localhost:8080)  
   Du ser:
   - "Hello from the frontend!"
   - Og: "Hello from the backend!" hentet via `/api`

---

Sig til, hvis du vil have versioner med Vue/React frontend, eller hvis det skal bruges i en øvelse.
