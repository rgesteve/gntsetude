#FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:22
FROM mcr.microsoft.com/devcontainers/base:ubuntu

#ENV PATH="/depot_tools:$PATH"

#RUN mkdir -f /opt
#RUN git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git /opt/depot_tools

RUN curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install linux \
  --extra-conf "sandbox = false" \
  --init none \
  --no-confirm


