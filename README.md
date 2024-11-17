# Contains my functions, I use everyday

## poetry setup
pip install poetry

poetry new <project_name>

poetry init
poetry config virtualenvs.in-project true
poetry env info
poetry env list
poetry install --no-root
poetry add requests
poetry show


poetry shell
poetry version minor (0.x.0)
poetry version patch (0.0.x)
git tag 0.0.1
git push origin --tags