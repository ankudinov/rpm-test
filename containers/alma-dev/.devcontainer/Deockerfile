FROM almalinux:9.4-minimal

# copy postCreate script
COPY ./postCreate.sh /bin/postCreate.sh
RUN chmod +x /bin/postCreate.sh

# install the latest yamllint and eos-downloader
RUN pip install "eos-downloader>=0.10.3"
