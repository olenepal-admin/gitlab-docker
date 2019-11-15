#FROM gitlab/gitlab-ce:12.2.7-ce.0
FROM gitlab/gitlab-ce:latest

#RUN groupadd -r appuser && useradd -r -u 1000 -g appuser appuser
#USER appuser
ENV DEPLOY /deploy/EPaath28
RUN mkdir -p  $DEPLOY
RUN chmod -R 775 $DEPLOY
RUN chown -R  998:root $DEPLOY
#

