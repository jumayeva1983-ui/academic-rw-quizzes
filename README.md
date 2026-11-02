# Caravan Challenge

Online challenges (one page per stop, 45 stops) for the textbook *Silk Road Writers: Academic Reading and Writing Practice* (D. K. Jumayeva, Navoiy, 2026). The QR codes in the book open `https://jumayeva1983-ui.github.io/academic-rw-quizzes/lessonNN.html`.

The pages are built from the textbook source (`quiz/data/lessonNN.json`, `tools/build_quiz.py`); edit them there and copy `quiz/site/` here again.

## The online book

`kitob.html` is the whole book (45 stops, glossary, references) and `modul1.html` … `modul4.html` are the four modules, each a single self-contained file with the pictures and the Caravan Challenges inside. The textbook (page 8) and the Teacher's Guide (figure 1.1) link to `kitob.html`. They are built from `darslik/flipbook/Silk_Road_Writers_flipbook.html` and `Modul<N>_flipbook.html` of the textbook source (`tools/build_module.py all`); copy them here again after a rebuild.
