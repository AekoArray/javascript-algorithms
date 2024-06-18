# Алгоритм Беллмана–Форда

Алгоритм Беллмана–Форда - это алгоритм, который вычисляет кратчайшие пути от одной исходной вершины ко всем остальным вершинам взвешенного орграфа. Он медленнее алгоритма Дейкстры для решения той же задачи, но более универсален, поскольку способен обрабатывать графики, в которых некоторые веса ребер являются отрицательными числами.

![Bellman-Ford](https://upload.wikimedia.org/wikipedia/commons/2/2e/Shortest_path_Dijkstra_vs_BellmanFord.gif)

## Сложность

Наихудшая производительность `O(|V||E|)`
Наилучшая производительность	`O(|E|)`
Наихудшое использование памяти `O(|V|)`

## Ссылки

- [Википедия](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm)
- [Michael Sambol на YouTube](https://www.youtube.com/watch?v=obWXjtg0L64&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)