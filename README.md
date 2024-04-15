#### Quick Start
1. Download Docker Image

    Link: https://pan.baidu.com/s/1UsXLN-3eO2wOOfe8SEDDVw?pwd=g9ux

2. Import Docker Image
   ```shell
   gunzip zircon.tar.gz
   docker import zircon.tar your_image_name:tag
   docker run --name your_container_name -d -it your_image_name /bin/bash
   ```
3. Compile

   ```shell
   cd /home/geng/zircon/
   make build
   ```
5. Run
   ```shell
   cd /home/geng/zircon/
   make runla64
   ```
