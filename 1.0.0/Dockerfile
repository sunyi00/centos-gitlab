FROM sunyi00/centos:1.0.0

RUN yum -y install \
        libevent-devel \
        python-backports-lzma \
        python-devel \
        python-pip \
        unzip \
    && curl -s https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.rpm.sh | bash \
    && yum install gitlab-ce-8.0.4-ce.1.el7.x86_64 \
    && yum -y clean all
