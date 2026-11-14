# 2-minute video demo – script (≈ 280 words, screen recording + voice-over)

**Before recording:** have the notebook already run (results visible), the Streamlit-free demo is the notebook itself. Open: GitHub repo, notebook outputs, results table, loss-curve figure. Record with Zoom/OBS/Loom, 1080p. Upload to YouTube (Unlisted is fine) or LinkedIn.

| Time | Screen | Say |
|---|---|---|
| 0:00–0:15 | Title slide | "Hi, I'm Mitesh Vataliya, M.Tech CSE. My project compares four optimizers – SGD, Adam, RMSprop and AdamW – for CNN image classification on CIFAR-10." |
| 0:15–0:35 | Notebook: config + data cells | "Everything except the optimizer is fixed: the same 814-thousand-parameter CNN, the same 45k/5k/10k split, augmentation, batch size and 30 epochs. Each optimizer runs with three seeds." |
| 0:35–1:05 | Scroll the training cell / show a run printing epochs (or the already-executed output) | "The notebook trains each model, keeps the best-validation checkpoint, and logs loss, accuracy and time per epoch, then evaluates once on the test set." |
| 1:05–1:35 | Results table + loss curves + bar chart | "Here are the results. [Best optimizer] reached [X] percent test accuracy, [one sentence on convergence speed], and [one sentence on training time]." |
| 1:35–1:50 | LR-sensitivity figure | "A learning-rate ablation shows [most/least sensitive optimizer]." |
| 1:50–2:00 | GitHub repo page | "All code, the LaTeX report and slides are in my GitHub repo. Thank you!" |

Tip: do not show the full 45-minute training live – show the finished outputs, or run `QUICK = True` for 2 minutes on screen.
