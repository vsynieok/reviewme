# About
This is the super repo for the ReviewMe project, containing two other components as submodules.

* **reviewme-api** - back-end repository
* **reviewme-ui** - front-end repository

# Cloning and running
If you're cloning the project for the first time, use the following command:
```
git clone --recursive https://github.com/vsynieok/reviewme.git
```

If you've already cloned the project and want to pull just the submodules, do this instead:
```
git submodule update --init --recursive
```

When you have everything set up, you're ready to use **docker-compose**:
```
docker compose up --build
```
