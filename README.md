# Geonode
    
- [Installation](#installation)
    
    ## Installation for docker
    
    1. Do a backup of your current Geonode
    2. Clone this repository it will create directory with name geonode.
    3. Copy files from geonode/geonode into your geonode/genode directory.
    4. Restart  docker with command  
        ```bash
        docker-compose -f docker-compose.yml up -d --build
        ```
