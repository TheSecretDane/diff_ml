### Setup
1) Install [uv](https://docs.astral.sh/uv/)
2) Clone repo, then:
   - GPU (Windows, NVIDIA): `uv sync --extra cuda`
   - CPU only: `uv sync --extra cpu`
3) VS Code: select interpreter `./.venv/Scripts/python.exe` (or use kernel “Python (diff_ml)”)
