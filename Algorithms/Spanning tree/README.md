# Алгоритми за покриващи дървета

| Алгоритъм | Време | Памет | Описание |
| --- | --- | --- | --- |
| [Kruskal](<./Kruskal/>) | $O(E \cdot log V)$ | $O(E)$ |Намира минимално (максимално) покриващо дърво като сортира всички ребра и добавя последователно, избягвайки цикли |
| [Prim](<./Prim/>) | $O(E + V \cdot log V)$ | $O(V+E)$ | Намира минимално (максимално) покриващо дърво като започва от произволен връх и винаги добавя текущо най-оптималното ребро|