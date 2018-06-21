FROM elasticsearch:5@sha256:770f5bf5fff2fd247d54f557d204a614eafa3d3e262e3f2c07986bba57d8c916

ENV ES_JAVA_OPTS="-Des.path.conf=/etc/elasticsearch"

CMD ["-E", "network.host=0.0.0.0", "-E", "discovery.zen.minimum_master_nodes=1"]
