# oyun # Dosya yapısı:

```
dino-game/
│
├── README.md
├── requirements.txt
├── dino_game.py
└── .gitignore
```

# README.md içeriği:
```markdown
# Dinozor Labirent Oyunu

Pac-Man'den esinlenilen, Python ve Pygame ile yazılmış basit bir labirent oyunu.

## Kurulum

1. Repository'yi klonlayın:
```bash
git clone https://github.com/kullaniciadin/dino-game.git
cd dino-game
```

2. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

3. Oyunu başlatın:
```bash
python dino_game.py
```

## Nasıl Oynanır

- Ok tuşlarını kullanarak dinozoru hareket ettirin
- Sarı kareleri toplayarak puan kazanın
- Ekranda görünen skorunuzu artırmaya çalışın

## Gereksinimler

- Python 3.x
- Pygame

## Lisans

MIT License
```

# requirements.txt içeriği:
```
pygame==2.5.2
```

# .gitignore içeriği:
```
# Python
__pycache__/
*.py[cod]
*$py.class

# Virtual Environment
venv/
env/
ENV/

# IDE
.vscode/
.idea/
*.sublime-workspace
*.sublime-project

# OS
.DS_Store
Thumbs.db
```
