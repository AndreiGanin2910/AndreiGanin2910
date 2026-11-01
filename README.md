<picture>
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-header-light.svg">
  <img src="assets/profile-header-dark.svg" width="100%" alt="Андрей Ганин — Machine Learning">
</picture>

# Привет, я Андрей

Три года занимаюсь машинным обучением: участвую в соревнованиях, хакатонах и разрабатываю собственные проекты. Работаю с рекомендательными системами, табличными данными, CV, NLP и аудио.

Мне интересно не только улучшать метрику, но и разбираться, **почему работает решение**: как устроены данные, что проверяет валидация и как запустить готовую модель.

**Открыт к стажировкам и проектам в ML.**

[Портфолио ↗](https://andreiganin2910.github.io/) · [Kaggle](https://www.kaggle.com/qwertyyyy769492) · [Telegram](https://t.me/Andrei_diffurs) · [Email](mailto:andreiganin09@gmail.com)

## 🧩 Избранные проекты

<table>
<tr>
<td width="50%" valign="top">
<sub>RecSys</sub>
<h3><a href="https://github.com/AndreiGanin2910/Hackathon-by-pages-2-place-RecSys">Рекомендации книг ↗</a></h3>
<p>Коллаборативные модели и текстовые признаки, ранжирование CatBoost и перестановка рекомендаций с учётом жанрового разнообразия. Обучение и проверка на временных окнах.</p>
<p><b>2-е место из 300 команд</b></p>
<p><code>ALS / BPR</code> · <code>Learning-to-rank</code> · <code>Reranking</code></p>
</td>
<td width="50%" valign="top">
<sub>RecSys · Semantic models</sub>
<h3><a href="https://github.com/AndreiGanin2910/University-Course-RecSys-top15">Рекомендации университетских курсов ↗</a></h3>
<p>История студента и семантика курсов: E5, обучаемая совместимость и ансамбль бустингов. Отдельные подходы для новых курсов и студентов без истории.</p>
<p><b>pNDCG@5 · 0.4528070</b></p>
<p><code>E5</code> · <code>Cold start</code> · <code>Cross-fitting</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>Audio · RuCode / МТС</sub>
<h3><a href="https://github.com/AndreiGanin2910/Rucode-2026-Top_6-Task-C">Обнаружение синтезированной речи ↗</a></h3>
<p>Акустические и фазовые признаки вместе с представлениями wav2vec2. Проверка на отложенных дикторах и типах атак; код обучения, инференса и готовые веса.</p>
<p><b>Public score · 99.20</b></p>
<p><code>wav2vec2</code> · <code>Signal processing</code> · <code>SVM / LightGBM</code></p>
</td>
<td width="50%" valign="top">
<sub>Tabular ML · Data Fusion</sub>
<h3><a href="https://github.com/AndreiGanin2910/Data-Fusion-top-60">Прогноз интереса к банковским продуктам ↗</a></h3>
<p>41 целевая переменная и миллион клиентов. Бустинги и нейросетевые модели, OOF-признаки и отдельная смесь прогнозов для каждого продукта.</p>
<p><b>Private ROC-AUC · 0.845 / Top-60</b></p>
<p><code>TabM</code> · <code>Denoising Autoencoder</code> · <code>OOF blending</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>NLP · FAIO / Отбор</sub>
<h3><a href="https://github.com/AndreiGanin2910/FAIO-2026">FAIO — NLP-решения отбора ↗</a></h3>
<p>Два решения отборочного этапа: определение автора оценки перевода с COMET-признаками и восстановление текстовой формы через RuBERT с ограничениями BIO-разметки.</p>
<p><b>Две задачи отборочного этапа</b></p>
<p><code>COMET</code> · <code>RuBERT</code> · <code>BIO / Viterbi</code></p>
</td>
<td width="50%" valign="top">
<sub>Data engineering · Analytics</sub>
<h3><a href="https://github.com/AndreiGanin2910/Market-Microstructure-Analyzer">Микроструктура рынка Bybit ↗</a></h3>
<p>Сбор сделок и стакана через API, расчёт спреда, ликвидности и дисбаланса объёмов. Графики и автоматический отчёт в одном инструменте.</p>
<p><b>Сбор данных → анализ → отчёт</b></p>
<p><code>API / asyncio</code> · <code>Pandas</code> · <code>Plotly</code></p>
</td>
</tr>
</table>

## 🏅 Соревнования и достижения

| Соревнование | Результат |
| :--- | :--- |
| [FAIO · Международная олимпиада по ИИ и ML](https://faio.kz/) | **Серебряная медаль · Top-10** |
| Хакатон по рекомендательным системам | **2-е место из 300 команд** |
| НТО · Искусственный интеллект | **Призёр** |
| Всероссийская олимпиада по ИИ | **Финалист · Top-50 России** |
| Kaggle · CAFA 6 Protein Function Prediction | **Бронзовая медаль · 115 / 2259** |

## ⚙️ Стек и методы

| Направление | Инструменты и методы |
| :--- | :--- |
| Рекомендательные системы | ALS, BPR, learning-to-rank, семантические представления, cold start, reranking |
| Табличный ML | CatBoost, LightGBM, TabM, feature engineering, дисбаланс классов |
| Computer Vision | PyTorch, YOLO, SigLIP, image embeddings, мультимодальные признаки |
| NLP | Transformers, RuBERT, E5, COMET, fine-tuning, token classification |
| Аудио | wav2vec2 / XLS-R, спектральные и фазовые признаки, обработка сигналов |
| Валидация и ансамбли | Временные и групповые разбиения, OOF, cross-fitting, blending, анализ ошибок |
| Разработка | Python, NumPy, Pandas, SciPy, scikit-learn, Git |

Помимо ML — тренажёрный зал, волейбол и AI-конференции.
