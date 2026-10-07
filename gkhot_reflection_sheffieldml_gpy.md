# Reflection: sheffieldml_gpy

GPy was huge early on (2,000+ commits in 2013) and then slowly died down, hitting just 2 commits in 2022. I called it declining, even though it picks back up in 2023-2024. There are 4 gaps of 3+ months, all between 2021 and 2023.

The longest gap is 2022-05 to 2023-01 (9 months). Before it, Neil Lawrence was mostly merging small fixes and old PRs. The gap wasn't hard to explain: during it, people opened issues saying GPy wouldn't install on newer Python (#998) and didn't work with numpy 1.24+ (#1004). So the library was breaking and nobody was fixing it.

It recovered in 2023 when Martin Bubel fixed it for modern Python (PR #1011), and KOLANICH updated the packaging. Martin Bubel ended up with 304 commits after that, so a new person really drove the recovery. It's Active as of 2025-09-30.
