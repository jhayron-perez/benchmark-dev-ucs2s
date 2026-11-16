# Legacy onset benchmark core (unchanged copies)

These three scripts are the monsoon-onset benchmark of Masiwal et al. (2026, arXiv:2602.03767),
copied **unchanged** from `envfluids/benchmark-dev`, `metrics/monsoon/codes/` (commit `f736146`):

| file | original location |
|---|---|
| `mae_far_mr_probabilistic_models.py` | `mae_far_mr_probablistic_models/` |
| `onset_reliability_diagram_cmz.py` | `realibility_diagram/` |
| `binned_skill_score_cmz.py` | `probabilistic_skill_scores/` |

`../run_onset_core.py` imports them and replaces only their forecast loader
(`get_forecast_probabilistic_twice_weekly`); `../config.py` looks here first.
