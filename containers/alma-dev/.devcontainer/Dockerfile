FROM almalinux:9.4

RUN dnf install -y python3-pip

# copy postCreate script
COPY ./postCreate.sh /bin/postCreate.sh
RUN chmod +x /bin/postCreate.sh

RUN pip install "eos-downloader>=0.10.3"
