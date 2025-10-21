## Usage

To start the development environment:

### Build and start the container
```shell
docker-compose up -d
```
### Stop the container
```shell
docker-compose down
```
Access Jupyter Lab at: http://localhost:8888

The notebooks are mounted as a volume, so any changes you make in Jupyter will be reflected in your local `notebooks/` folder and vice versa.

If you want to add packages, edit `requirements.txt` and rebuild:
```shell
docker-compose up -d --build
```