So machst du einen **bereits existierenden Ordner** zu einem Repository in Github:

---

## 🔹 Ordner lokal initialisieren und zu Github, Gitea hochladen

### 1️⃣ In deinen Ordner wechseln

```bash
cd /pfad/zu/deinem/ordner
```

### 2️⃣ Git initialisieren

```bash
git init
```

### 3️⃣ Dateien hinzufügen

```bash
git add .
```

### 4️⃣ Ersten Commit machen

```bash
git commit -m "Initial commit"
```

---

### 5️⃣ Neues Repository in Github erstellen

* In Github → **New Repository**
* Namen vergeben
* **Wichtig:** Kein README / .gitignore erstellen lassen (sonst gibt’s Konflikte)

Danach bekommst du eine URL wie:

```
https://github.example.com/username/repo.git
```

oder per SSH:

```
git@github.com:username/repo.git
```

---

### 6️⃣ Remote hinzufügen

```bash
git remote add origin git@github.example.com:username/repo.git
```

### 7️⃣ Hochladen 

```bash
git branch -M main  # ACHTUNG: Branch ev. ändern
```
```bash
git push -u origin main  # ACHTUNG: Branch ev. ändern
```

Fertig ✅