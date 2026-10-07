# Reflection: juliaopt_cplex.jl

CPLEX.jl was steady from 2013 to 2020 and then slowly dropped off, so I called it declining. It has 5 gaps of 3+ months, all after 2021. The longest is 7 months, 2024-06 to 2024-12. The repo also moved from JuliaOpt to jump-dev.

Almost every commit before the gap is Oscar Dowson doing maintenance: preparing releases, fixing version bounds, updating CI and the README. Since this is just a wrapper for a solver, it only needs changes when something upstream changes, so I think the gap is because there wasn't anything to do. I didn't find any ignored bug reports.

Only one commit came after the gap (a README badge fix in January 2025), so this one was hard to call a "recovery". But GitHub shows a v1.1.1 release in April 2025 and more updates later, all by the same maintainer. Its last commit before the cutoff was 2025-04-04, just barely making it Active as of 2025-09-30.
