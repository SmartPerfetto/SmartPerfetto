# SmartPerfetto

English | 中文

AI-powered Android performance analysis built on Perfetto.

Load a `.pftrace` / `.perfetto-trace`, ask a natural-language question, and get an evidence-backed answer with SQL results, root-cause reasoning, and optimization suggestions.

## Getting Started

Clone the repo, then run the setup check to confirm your environment is compatible before installing:

```bash
python3 verify_setup.py
```

This prints your detected platform and picks the nearest package mirror for faster dependency downloads.

### Quick start

```bash
./start.sh
```

Then open http://localhost:10000 and load a trace.

Or install the CLI:

```bash
npm install -g .
smp doctor
```

## License

AGPL-3.0-or-later
