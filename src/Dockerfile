FROM archlinux:base-devel

RUN pacman -Syu --noconfirm && \
    pacman -S --noconfirm gtk4 libadwaita rustup

ENV CARGO_REGISTRIES_CRATES_IO_PROTOCOL=sparse
RUN rustup default stable

CMD ["/bin/bash"]
