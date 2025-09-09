# HY-End 장기 프로젝트 서버


Based on the [multi-file example](https://fastapi.tiangolo.com/tutorial/bigger-applications/) from
the FastAPI documentation.

## Getting Started

### Prerequisites

- [uv](https://docs.astral.sh/uv/getting-started/installation/) - Python package manager
- Python 3.12+ (Python 3.13 may have compatibility issues with some dependencies)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mjwoon/hyend-server.git
   cd hyend-server
   ```

2. **Install Python 3.12 (if needed)**
   ```bash`
   uv python install 3.12
   ```

3. **Create virtual environment with Python 3.12**
   ```bash
   uv venv --python 3.12
   ```

4. **Install dependencies**
   ```bash
   uv sync
   ```

### Running the Application

**Development server:**
```bash
uv run fastapi dev
```

**Production server:**
```bash
uv run fastapi run
```

**Direct Python execution:**
```bash
uv run python app/main.py
```

The server will start on `http://localhost:8000` by default.

### API Documentation

Once the server is running, you can access:
- Interactive API docs: `http://localhost:8000/docs`
- Alternative docs: `http://localhost:8000/redoc`

## License

MIT

<div align="center">
  <a target="_blank" href="https://astral.sh" style="background:none">
    <img src="https://raw.githubusercontent.com/astral-sh/uv/main/assets/svg/Astral.svg" alt="Made by Astral">
  </a>
</div>
