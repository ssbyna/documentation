FROM python:3.9

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir sphinx sphinx_rtd_theme docutils

WORKDIR /docs

CMD sphinx-build -b html . _build/html
