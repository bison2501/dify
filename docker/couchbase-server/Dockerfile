FROM couchbase/server:7.2.4 AS stage_base
# FROM couchbase:latest AS stage_base
COPY init-cbserver.sh /opt/couchbase/init/
RUN groupadd -r maiauser && useradd -r -g maiauser maiauser
USER maiauser