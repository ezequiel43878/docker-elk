
# ELK


**Problema de volumen**:

    nested: AccessDeniedException[/usr/share/elasticsearch/data/nodes docker

**Solucion**:

    sudo chown -R 1000:1000 [directory]

    Ej:
        volumes:
          - ./elasticsearch/data:/usr/share/elasticsearch/data
    
    sudo chown -R 1000:1000 ./elasticsearch/data
