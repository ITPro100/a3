# Audi A3 в 3D

Інтерактивна 3D-сцена Audi A3 Sedan 2016 (8V, 1.8 TFSI, LX7R Monsoon Gray) на three.js.

- Режими сцени: Studio / Acid / Car wash
- Перемикачі оптики та «стилю під фото» (колір кузова, тонування, чорні диски)
- Можна підвантажити власну модель `.glb` або `.gltf` разом з його `.bin` і текстурами (кнопка або drag & drop)

## Файли

| Файл | Що це |
|---|---|
| `index.html` | Сторінка зі сценою (three.js 0.160 з unpkg) |
| `audi-s3-8v.glb` | Вбудована 3D-модель, підвантажується через `fetch` |

## Запуск

Сторінку треба відкривати через HTTP-сервер (через `file://` `fetch` моделі не спрацює):

```bash
python3 -m http.server 8000
# відкрити http://localhost:8000
```

Або увімкнути GitHub Pages для гілки з цими файлами (Settings → Pages).

## Ліцензія моделі

3D-модель: [2014 Audi S3 Limousine](https://sketchfab.com/3d-models/2014-audi-s3-limousine-33056acd771241638ebe74109ba2777a) — tonielpro520, CC BY 4.0.
