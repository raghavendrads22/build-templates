FROM hseeberger/scala-sbt:8u181_2.12.7_1.2.6

WORKDIR /opt/app

ENV PORT=80

RUN touch /boot.sh # this is the script which will run on boot

# daemon for cron jobs
# RUN echo 'echo will install crond...' >> /boot.sh
# RUN echo 'crond' >> /boot.sh

# start it!
CMD sh /boot.sh && sbt "run 80"
