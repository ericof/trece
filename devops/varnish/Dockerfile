# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="Érico Andrei <ericof@plone.org>" \
      org.label-schema.name="trece-varnish" \
      org.label-schema.description="Treinamento TRE-CE Varnish image." \
      org.label-schema.vendor="Érico Andrei"

COPY etc/varnish.vcl /etc/varnish/default.vcl
