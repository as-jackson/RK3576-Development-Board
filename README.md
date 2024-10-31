## RK3576 Development Board Introduction


### ArmSoM-Sige5 RK3576 Development Board

ArmSoM-Sige5 adopts the second-generation 8nm high-performance AIOT platform Rockchip RK3576, with a 6 TOPS computing power NPU and support for up to 16GB of large memory. It supports 4K video encoding and decoding, offers rich interfaces including dual gigabit Ethernet ports, WiFi 6 & BT5, and various video outputs. Compatible with multiple operating systems, it is suitable for ARM-based PCs, edge computing devices, personal mobile internet devices, and other digital multimedia applications.

![rk3576 sige5](./image/RK3576_sige5.png)

More details：https://docs.armsom.org/armsom-sige5

### ArmSoM-CM5 RK3576 Compute Module

The ArmSoM-CM5 is a Compute module powered by the Rockchip RK3576 second-generation 8nm high-performance AIOT platform. It integrates a quad-core Cortex-A72 @ 2.2GHz and a quad-core Cortex-A53 @ 1.8GHz, along with a dedicated NEON co-processor, a 6 TOPS NPU, and supports up to 16GB of large memory. It supports 4K video encoding and decoding, features a rich set of interfaces, and supports various operating systems.

![rk3576 CM5](./image/RK3576_cm5.png)

ore details：https://docs.armsom.org/armsom-cm5

### RK3576 Linux mainline support

- Add rk3576 armsom-sige5 board: https://patchwork.kernel.org/project/dri-devel/patch/20240903152308.13565-10-detlev.casanova@collabora.com/ 

## RK3576 Brief datasheet

A low power, high performance AloT processor

<table>
    <thead>
        <tr>
            <th>Features</th>
            <th>RK3576</th>
      </tr>
    </thead>
    <tbody align="left">
        <tr>
            <th>CPU</th>
            <th><li>Quad Cortex-A72 and quad Cortex-A53 </li><li>1M8 unifed L2 cache for Cortex-A72</li><li>512KB unified L2 cache for Cortex-A53</li> <li>ARM cortex MO for user application</li>
        </tr>
        <tr>
            <th>GPU</th>
            <th><li>ARM Mali G52 MC3</li><li>OpenGL Es 1.1, 2.0 and 3.2, 0pencL 2.1, Wulkan 1.2</li>
        </tr>
        <tr>
            <th>NPU</th>
            <th><li>6 TOPS*@INT8</li><li>Support int4/int8/int16/FP16/BF16/TF32</li><li>Support deep learning frameworks: TensorFlow, Caffe,Tfite, Pytorch, Onnx NN, Android NN, etc</li>
        </tr>
        <tr>
            <th>Memory</th>
            <th><li>32-bit LPDDR4/LPDDR4X/LPDDR5</li><li>eMMC 5.1, SDIO 3.0 and SFC</li><li>UFS v2.0</li></th>
        </tr>
        <tr>
            <th>Multimedia</th>
            <th><li>H.265 HEVC Main10 L5.1 yuv444: 4K 120fps</li><li>H.264 AVC High10 L5.1 yuv422: 4K 60fps</li><li>H.264 MVC up to 1080P 60fps</li><li>VP9 Profile0/2 L5.1: 4K 120fps</li><li>AVS2 Profile0/2 L10.2.6: 4K 120fps</li><li>AV1 Main10 L5.3: 4K 120fps</li><li>4K@60fps video encoders for H.264/H.265</li></th>
        </tr>
        <tr>
            <th>Video Input</th>
            <th><li>16M Pixel ISP with HDR & 3DNR</li><li>Triple MIPI CSI-2 with 4-lane interfaces</li><li>16-bit DVP interface, up to 150MHz</li></th>
        </tr>
        <tr>
            <th>Display</th>
            <th><li>Multiple display up to (4K@120 + 2.5K@60 + 2K@60)</li><li>HDMI v2.1/ eDP v1.3 Combo interface</li><li>MIPI DSI, 4 lanes</li><li>DP v1.4 and USB 3.0 combo (Type-C) interface</li><li>Parallel output interface</li><li>EBC output interface</li><li>Picture Quality post-process module</li></th>
        </tr>
        <tr>
            <th>Audio Interface</th>
            <th><li>5x SAI interfaces, support I2S/thM/PCM mode</li><li>SPDIF TX and SPDIF RX</li><li>PDMO/PDM1 with 8 channels</li><li>Dual 2-ch and dual 4-ch ASRC</li><li>Digital Audio Codec with 2 channels</li></th>
        </tr>
        <tr>
            <th>High Speed Interface</th>
            <th><li>PCIe2.1/SATA3 combo interface with one data lane</li><li>PCIe2.1/SATA3/USB3.0 combo interface with one data lane</li><li>2x RGMII interfaces</li></th>
        </tr>
        <tr>
            <th>Industry</th>
            <th><li>2x CAN FD</li><li>16-bit DSMC (Double Data Rate Serial Memory Controller)</li></th>
        </tr>
        <tr>
            <th>Security</th>
            <th><li>ARM TrustZone security extension</li><li>Secure boot and JTAG</li><li>Key ladder</li><li>Crypto (RSA 4096, AES 256, SHA-512...)</li><li>HDCP 2.x for HDMI and DP/eDP</li></th>
        </tr>
        <tr>
            <th>SDK</th>
            <th><li>Linux and Android</li></th>
        </tr>
        <tr>
            <th>Others</th>
            <th><li>Package Information: FCCSP698L(16.1x17.2mm, pitch: 0.6mm)</li></th>
        </tr>
    </tbody>
</table>

### RK3576 Block Diagram

![rk3576 block diagram](./image/rk3576.png)

### RK3576 Typical Application Diagram-AloT

![rk3576 typical](./image/rk3576-typical.png)