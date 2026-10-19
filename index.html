```html
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Имя прилагательное — Школьная игра (5-9 класс)</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
    body {
      font-family: 'Inter', sans-serif;
      -webkit-tap-highlight-color: transparent;
    }
  </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen flex items-center justify-center p-3 sm:p-6">

  <div class="w-full max-w-xl bg-slate-800 rounded-2xl shadow-2xl border border-slate-700 p-4 sm:p-6 flex flex-col justify-between min-h-[550px]">
    
    <!-- Шапка игры -->
    <header class="mb-4">
      <div class="flex justify-between items-center mb-2">
        <span class="text-xs font-semibold uppercase tracking-wider text-indigo-400 bg-indigo-950/80 px-3 py-1 rounded-full border border-indigo-800/50" id="level-badge">Уровень 1</span>
        <span class="text-sm font-bold text-amber-400 flex items-center gap-1">
          <svg class="w-4 h-4 fill-current" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
          <span id="score">0</span> баллов
        </span>
      </div>

      <div class="w-full bg-slate-700 h-2 rounded-full overflow-hidden">
        <div id="progress" class="bg-indigo-500 h-full w-0 transition-all duration-300"></div>
      </div>
    </header>

    <!-- Основной игровой блок -->
    <main id="game-card" class="flex-1 flex flex-col justify-between">
      <div>
        <div class="text-xs text-slate-400 font-medium mb-1" id="question-number">Вопрос 1 из 8</div>
        <h2 class="text-lg sm:text-xl font-bold text-white mb-4 leading-snug" id="question-text">Загрузка...</h2>

        <!-- Варианты ответов -->
        <div class="space-y-2.5" id="options-container">
          <!-- Кнопки создаются динамически -->
        </div>
      </div>

      <!-- Пояснение правил -->
      <div id="explanation-box" class="hidden mt-4 p-3.5 bg-slate-700/60 border border-slate-600 rounded-xl text-sm text-slate-200">
        <div class="font-semibold text-amber-300 mb-1 flex items-center gap-1.5">
          <span>💡 Правило:</span>
        </div>
        <p id="explanation-text" class="leading-relaxed text-xs sm:text-sm"></p>
      </div>

      <button id="next-btn" onclick="nextQuestion()" class="hidden w-full mt-4 bg-indigo-600 hover:bg-indigo-500 active:scale-[0.98] text-white font-semibold py-3 rounded-xl transition duration-200 shadow-lg shadow-indigo-600/30">
        Следующий вопрос
      </button>
    </main>

    <!-- Финальный экран -->
    <section id="end-screen" class="hidden text-center py-6 flex-1 flex flex-col items-center justify-center">
      <div class="w-16 h-16 bg-indigo-500/20 text-indigo-400 rounded-full flex items-center justify-center mb-4 text-3xl">🏆</div>
      <h2 class="text-2xl font-bold text-white mb-2">Отличная работа!</h2>
      <p class="text-slate-300 text-sm mb-6 max-w-xs" id="final-message"></p>
      
      <div class="bg-slate-700/50 border border-slate-600 p-4 rounded-xl mb-6 w-full max-w-xs">
        <span class="text-xs text-slate-400 uppercase tracking-wider block mb-1">Итоговый результат</span>
        <span class="text-3xl font-extrabold text-amber-400" id="final-score">0</span>
        <span class="text-sm text-slate-300"> / 80 баллов</span>
      </div>

      <button onclick="restartGame()" class="w-full max-w-xs bg-emerald-600 hover:bg-emerald-500 active:scale-[0.98] text-white font-semibold py-3 rounded-xl transition duration-200 shadow-lg shadow-emerald-600/30">
        Пройти снова
      </button>
    </section>

  </div>

  <script>
    // Вопросы по программе 5-9 классов
    const questions = [
      // Уровень 1: Разряды
      {
        level: "Уровень 1: Разряды",
        q: "Укажите ПРИТЯЖАТЕЛЬНОЕ имя прилагательное:",
        options: ["Деревянный стол", "Лисий хвост", "Красивый день", "Вечерний звон"],
        correct: 1,
        rule: "Притяжательные прилагательные отвечают на вопрос «чей?» и указывают на принадлежность предмета человеку или животному (лисий хвост)."
      },
      {
        level: "Уровень 1: Разряды",
        q: "Какое из прилагательных является КАЧЕСТВЕННЫМ?",
        options: ["Школьный портфель", "Стеклянный стакан", "Высокий дом", "Вчерашний разговор"],
        correct: 2,
        rule: "Качественные прилагательные обозначают признак, который может быть выражен в большей или меньшей степени (выше, самый высокий)."
      },
      // Уровень 2: Степени сравнения
      {
        level: "Уровень 2: Степени сравнения",
        q: "Найдите ОШИБКУ в форме степени сравнения:",
        options: ["Более красивый", "Красивее", "Самый красивейший", "Наиболее высокий"],
        correct: 2,
        rule: "Нельзя объединять простую и сложную форму! Правильно говорить либо «самый красивый», либо «красивейший»."
      },
      {
        level: "Уровень 2: Степени сравнения",
        q: "Выберите форму простую сравнительную степень:",
        options: ["Выше", "Более высокий", "Высочайший", "Самый высокий"],
        correct: 0,
        rule: "Простая сравнительная степень образуется с помощью суффиксов -е, -ее (-ей), -ше (выше, громче)."
      },
      // Уровень 3: НЕ с прилагательными
      {
        level: "Уровень 3: НЕ с прилагательными",
        q: "В каком случае НЕ пишется СЛИТНО?",
        options: [
          "Не широкая, а узкая река",
          "Ничуть не интересный фильм",
          "Небольшой, но уютный дом",
          "Отнюдь не верное решение"
        ],
        correct: 2,
        rule: "«Небольшой» пишется слитно, так как его можно заменить синонимом без НЕ (маленький) и нет противопоставления с союзом «а»."
      },
      {
        level: "Уровень 3: НЕ с прилагательными",
        q: "Укажите слово, которое без НЕ НЕ употребляется:",
        options: ["Нелепый", "Невысокий", "Недорогой", "Некрасивый"],
        correct: 0,
        rule: "Слово «нелепый» пишется слитно, потому что слова «лепый» в современном русском языке не существует."
      },
      // Уровень 4: Н и НН в суффиксах
      {
        level: "Уровень 4: Н и НН в суффиксах",
        q: "В каком слове пишется НН?",
        options: ["Гусиный", "Стеклянный", "Песчаный", "Кожаный"],
        correct: 1,
        rule: "«Стеклянный» — слово-исключение. В суффиксах -ан-/-ян- пишется одна Н, кроме слов: стеклянный, оловянный, деревянный."
      },
      {
        level: "Уровень 4: Н и НН в суффиксах",
        q: "Выберите прилагательное с суффиксом -ЕНН- (с НН):",
        options: ["Осенний", "Соломенный", "Лебединый", "Звериный"],
        correct: 1,
        rule: "В прилагательных, образованных от существительных с помощью суффиксов -енн- / -онн-, пишется НН (соломенный)."
      }
    ];

    let currentIdx = 0;
    let score = 0;
    let answered = false;

    function loadQuestion() {
      answered = false;
      const q = questions[currentIdx];

      document.getElementById("level-badge").innerText = q.level;
      document.getElementById("question-number").innerText = `Вопрос ${currentIdx + 1} из ${questions.length}`;
      document.getElementById("question-text").innerText = q.q;
      
      const progressPercent = ((currentIdx) / questions.length) * 100;
      document.getElementById("progress").style.width = `${progressPercent}%`;

      const optionsContainer = document.getElementById("options-container");
      optionsContainer.innerHTML = "";

      q.options.forEach((optionText, idx) => {
        const btn = document.createElement("button");
        btn.className = "w-full text-left p-3.5 rounded-xl bg-slate-700/50 border border-slate-600/80 hover:bg-slate-700 hover:border-slate-500 transition duration-150 text-sm font-medium text-slate-100 flex justify-between items-center";
        btn.innerHTML = `<span>${optionText}</span><span class="icon text-lg"></span>`;
        btn.onclick = () => selectOption(idx);
        optionsContainer.appendChild(btn);
      });

      document.getElementById("explanation-box").classList.add("hidden");
      document.getElementById("next-btn").classList.add("hidden");
    }

    function selectOption(selectedIdx) {
      if (answered) return;
      answered = true;

      const q = questions[currentIdx];
      const buttons = document.querySelectorAll("#options-container button");

      buttons.forEach((btn) => {
        btn.disabled = true;
        btn.classList.remove("hover:bg-slate-700", "hover:border-slate-500");
      });

      if (selectedIdx === q.correct) {
        buttons[selectedIdx].classList.add("bg-emerald-950/80", "border-emerald-500", "text-emerald-200");
        buttons[selectedIdx].querySelector(".icon").innerText = "✓";
        score += 10;
        document.getElementById("score").innerText = score;
      } else {
        buttons[selectedIdx].classList.add("bg-rose-950/80", "border-rose-500", "text-rose-200");
        buttons[selectedIdx].querySelector(".icon").innerText = "✕";

        buttons[q.correct].classList.add("bg-emerald-950/80", "border-emerald-500", "text-emerald-200");
        buttons[q.correct].querySelector(".icon").innerText = "✓";
      }

      document.getElementById("explanation-text").innerText = q.rule;
      document.getElementById("explanation-box").classList.remove("hidden");
      document.getElementById("next-btn").classList.remove("hidden");
    }

    function nextQuestion() {
      currentIdx++;
      if (currentIdx < questions.length) {
        loadQuestion();
      } else {
        showEndScreen();
      }
    }

    function showEndScreen() {
      document.getElementById("progress").style.width = "100%";
      document.getElementById("game-card").classList.add("hidden");
      document.getElementById("end-screen").classList.remove("hidden");
      document.getElementById("final-score").innerText = score;

      let msg = "";
      if (score === 80) {
        msg = "Идеально! Вы великолепно знаете тему «Имя прилагательное»!";
      } else if (score >= 50) {
        msg = "Хороший результат! Вы хорошо усвоили большинство правил.";
      } else {
        msg = "Стоит еще раз повторить правила о разрядах и суффиксах прилагательных.";
      }
      document.getElementById("final-message").innerText = msg;
    }

    function restartGame() {
      currentIdx = 0;
      score = 0;
      document.getElementById("score").innerText = "0";
      document.getElementById("end-screen").classList.add("hidden");
      document.getElementById("game-card").classList.remove("hidden");
      loadQuestion();
    }

    // Запуск игры
    loadQuestion();
  </script>
</body>
</html>
```
