# Contributing to Trinity Graph Engine

Thank you for considering contributing to Trinity Graph Engine!

## Getting Started

1. Fork the repository
2. Clone your fork
3. Run `make dev-setup` to set up your development environment
4. Start services with `docker-compose up -d`

## Development Workflow

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Make your changes
3. Run tests: `make test`
4. Run linters: `make lint`
5. Commit with meaningful messages
6. Push and open a Pull Request

## Code Standards

- Python: Follow PEP 8, use type hints
- Go: Follow effective Go guidelines
- TypeScript: Use ESLint configuration
- Write tests for new functionality

## Service Development

Each service has its own directory under `services/`:
- `social-graph` - Neo4j-based social graph service
- `knowledge-graph` - Apache Jena knowledge graph service
- `ai-graph` - Vector DB and LLM integration service
- `fusion-engine` - Cross-graph query fusion

## Questions?

Open a GitHub issue with the `question` label.
