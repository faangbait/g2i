FROM registry.lab.madeof.glass/python-311:1.0.0

USER 0

RUN INSTALL_PKGS="libpq-devel python3-devel" && \
    yum -y --setopt=tsflags=nodocs install $INSTALL_PKGS && \
    rpm -V $INSTALL_PKGS && \
    yum -y clean all --enablerepo='*'

USER 1001

CMD ["{$APP_ROOT}/src/manage.py", "runserver"]
