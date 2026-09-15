# Free Fire vs PUBG Game (Kaggle Auto Runner 2)
Automated Daily Kaggle notebook runner with n8n scheduling for GitHub user `chinnux567`.

## Daily Runtime Settings
- **Session Duration**: 4 Hours
- **Schedule**: Every day at 8:00 PM IST (14:30 UTC)
- **Weekly Total**: 28 Hours (Safely under Kaggle's 30h limit)

## GitHub Secrets Required
| Secret | Value |
| --- | --- |
| `KAGGLE_USERNAME` | chinnux567 |
| `KAGGLE_KEY` | Your Kaggle API key |
| `KERNEL_NAME` | kaggle-auto-runner-2 |
| `GH_PAT` | GitHub Personal Access Token |

## Setup Instructions
1. Upload these files to your GitHub repository.
2. Add the 4 secrets listed above in **GitHub Settings > Secrets and variables > Actions**.
3. Import your n8n workflow.
4. Enjoy your automated daily script!
