# wsl-cromium
```bash
sudo apt update
sudo apt install -y libasound2t64 libnss3 libatk-bridge2.0-0t64 libatk1.0-0t64 libatspi2.0-0t64 libgtk-3-0t64 libgbm1 libcups2t64 libdrm2 libxkbcommon0 libxcomposite1 libxdamage1 libxrandr2 libxfixes3 libpango-1.0-0 libcairo2
```


```bash
rm -rf .venv
source .venv/bin/activate

python -m playwright install --with-deps  # 리눅스 의존성까지 설치

pip uninstall playwright -y
pip install playwright
```
