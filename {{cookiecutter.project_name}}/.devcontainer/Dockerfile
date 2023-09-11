ARG BASE
FROM ${BASE}

# jinja template enable this only if the runtime is debian
{% if cookiecutter.enable_apt_cache %}
COPY apt-cache-proxy /etc/apt/apt.conf.d/proxy
{% endif %}
