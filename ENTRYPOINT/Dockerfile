# FROM almalinux:9
# # CMD [ "ping", "-c5", "google.com" ]
# # CMD Can be over ridden
# ENTRYPOINT [ "ping", "-c5", "google.com" ]
# # ENTRYPOINT can't be overridden  (But with mix of both gives better results)


FROM almalinux:9
CMD [ "google.com" ]
# CMD acts as default argument to ENTRYPOINT
ENTRYPOINT [ "ping", "-c5" ]