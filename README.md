# DSCI 522 Dockerfile Practice

## Development Environment

- **Jupyter** - Interactive notebook environment

### Environment Setup

#### Option 1: Using environment.yml

1. Create conda environment:

   ```bash
   conda env create -f environment.yml
   conda activate base
   ```

#### Option 3: Using Docker

1. Build and run with Docker Compose for running image from docker hub:

   ```bash
   docker compose up --build
   ```

   For ARM based chips run with platform as linux/arm64 in docker-compose.yml

2. Access Jupyter Lab at <http://127.0.0.1:8000/lab>

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.
