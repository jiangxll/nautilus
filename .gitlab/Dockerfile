FROM fedora:rawhide

RUN dnf install -y dnf-plugins-core uncrustify findutils libportal-devel \
 && dnf builddep -y nautilus \
 && dnf clean all
