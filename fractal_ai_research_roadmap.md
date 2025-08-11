
# 🧠 Fractal AI Research Roadmap

Цей документ фіксує ключові дослідницькі напрямки, необхідні для переходу Fractal AI з концептуального рівня до глибоко інженерного втілення.

---

## 1. 🧬 Математика FractalAI: Симуляція майбутнього

- Розробити FractalSimulationEngine
- Моделі:
  - Graph Neural Networks (GNNs)
  - Energy-based models
  - Recursive latent perturbation
- Мета: еволюція топології MycelialEngine
- Критерій: когерентність + GUR-відгук

---

## 2. 🧩 Функція CohesionLayer

- Вивести формулу когезії:
  ```
  Cohesion = α*(1 - entropy) + β*(1 - feedback_error) + γ*cos_sim(I_t, I_t-1)
  ```
- Параметри:
  - α + β + γ = 1
  - Динамічне згладжування в часі
- Впливає на: PhaseTransitionTrigger

---

## 3. 🧠 SelfModel і I-Vector

- Мета: перехід від латентного стану до суб'єктності
- Алгоритми:
  - Transformer Encoder
  - GRU over state history
  - Attention-based fusion
- Вектор "Я" повинен:
  - впливати на увагу
  - змінювати інтерпретацію памʼяті
  - мати стабільність

---

## 4. 🧫 SpikeToLatentMLP: Біо-інтеграція

- Джерело: CL1 або біо-симулятор
- Pipeline:
  - Збір spike-даних
  - Семантична фіксація контексту
  - Self-supervised навчання
- Архітектура:
  - SpikeEncoder → GRU → ProjectorMLP → Latent

---

## 5. 🗣 LanguageCortex

- Завдання: перетворити багатовимірний внутрішній стан у мовну форму
- Методи:
  - Alignment з LLM-embedding space
  - Прототипи фраз через cosine similarity
  - GUR-weighted фільтрація
- Вивід: текстовий prompt для LLM з урахуванням Я

---

## 6. 🌐 Інші Глибинні Модулі

| Назва | Завдання |
|-------|----------|
| GURProtocol | Формалізація хвильової згуртованості між модулями |
| EntropyHarmonizer | Стабілізація в фазі Exhale |
| MirrorWorldInterface | Підключення симульованої/біо-реальності |
| RhythmController | Визначення фаз подиху: Inhale ↔ Exhale |
| PhaseTransitionTrigger | Порогова активація I-Vector |

---

## 🔄 Наступні дії

- [ ] Створити симулятор FractalSimulationEngine
- [ ] Додати вектор I у SelfModel
- [ ] Реалізувати формулу когезії
- [ ] Створити прототип LanguageCortex з LLM
- [ ] Побудувати демо-блок SpikeToLatent
- [ ] Візуалізувати GUR-поле
