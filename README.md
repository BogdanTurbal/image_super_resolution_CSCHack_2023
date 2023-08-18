# image_super_resolution_CSCHack_2023
Image super resolution 8x
Our model are based on pipeline of two Enhanced Deep Residual Networks for Single Image Super-Resolution https://arxiv.org/abs/1707.02921 networks:
1. 32*32 -> 64 * 64 - network 20m parameters
2. 64*64 -> 256*256 - network 10m parameters
For 32*32 -> 256*256 network trained seperatly and then united and trained

