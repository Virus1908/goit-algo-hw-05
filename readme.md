## Результати
algo:rabin_karp_search    article:1 substring:Стаття result:0.1877\
algo:boyer_moore_search   article:1 substring:Стаття result:0.0431\
algo:kmp_search           article:1 substring:Стаття result:0.0729\
algo:rabin_karp_search    article:2 substring:Стаття result:1.0087\
algo:boyer_moore_search   article:2 substring:Стаття result:0.2394\
algo:kmp_search           article:2 substring:Стаття result:0.4429\
algo:rabin_karp_search    article:1 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:5.0144\
algo:boyer_moore_search   article:1 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:0.3401\
algo:kmp_search           article:1 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:2.2813\
algo:rabin_karp_search    article:2 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:7.5746\
algo:boyer_moore_search   article:2 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:0.4897\
algo:kmp_search           article:2 substring:ЦЬОГО ТЕКСТУ НЕ ІСНУЄ result:3.2767\

## Висновки

Найшвидший алгоритм в усіх випадках - Алгоритм Боєра-Мура\
Бачимо, що найповільніший алгоритм в усіх випадках - Алгоритм Рабіна-Карпа\
Також варто відмітити, що при пошуку рядка, якого не існує в тексті Алгоритм Боєра-Мура суттєво випереджає інші\
В той час, як Алгоритм  Кнута-Морріса-Пратта досить сильно втрачає продуктивність в цьому випадку. 