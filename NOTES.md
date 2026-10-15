# Catatan Lokal (fork pribadi)

Fork ini milik **ozzie5555**, hasil fork dari [usestrix/strix](https://github.com/usestrix/strix).

## Konfigurasi lokal di mesin saya

- Repo  : `~/VScode/masih-project/strix`
- Env   : `source ~/.strix/strix-env.sh` (mengisi `STRIX_LLM`, `LLM_API_BASE`, `LLM_API_KEY`)
- Model : `openai/ai/krisna/glm-5.3` via endpoint OpenAI-compatible opencode
- Sandbox image: `ghcr.io/usestrix/strix-sandbox:1.3.0`
- Dokumen setup lengkap: `~/VScode/masih-project/STRIX-SETUP.md`

## Perintah cepat

```bash
source ~/.strix/strix-env.sh
strix -n -t <target> --scan-mode quick --max-budget 10
strix view
```

## Sinkron dengan upstream

```bash
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```
