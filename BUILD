__defaults__(all=dict(environment="manylinux"))

python_sources(
    name="root",
)

python_tests(
    name="tests0",
)

docker_environment(
    name="manylinux",
    platform="linux_x86_64",
    image="python:3.9.14-slim-bullseye",
)
