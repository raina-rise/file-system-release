# FileNexus 是什么？ {#what-is-file-nexus}

FileNexus是一套完整的文件管控系统，主要满足 **内外网隔离场景下** 的文件传输和审核需求。

<div class="tip custom-block" style="padding-top: 8px">

只是想尝试一下？跳到[快速开始](./getting-started)。

</div>

## 行业痛点 {#pain-spot}

- **文件传输和审核系统割裂**

  很多公司的FTP和文件审核是两套独立的系统，这导致文件流转效率过低，同时也增加了公司软件维护成本和用户操作的心智负担。
  
- **复杂的FTP指令和环境**

  ftp/sftp的指令集较多，虽然日常操作可能只需要熟记个别指令，但是对于没有Linux或IT基础的小白用户或非技术型公司来说，FTP指令仍然过于复杂。同时用户可能还需要处理复杂的内网环境差异。

- **审核流程复杂或缺失审核流程**

  很多公司虽然做了内外网隔离，但是对文件审核的态度可能走向两个极端，要么就完全放任不管（不安全），要么审核流程过于复杂（不高效）。

## FileNexus的优势 {#advantage}

- **Docker打包，极速部署**

  FileNexus将整套系统打包进Docker镜像，无需繁琐的安装步骤，不影响现有系统环境，一行代码即可快速部署到服务器。

- **可视化操作，IT小白也能使用**

  无论是用户上传/下载文件，还是管理员审核/配置管理系统，FileNexus所有流程都在浏览器界面中完成，简易可视化操作，不懂FTP也能轻松上手。

- **传输+审核，聚合高效**

  传输+审核，一套系统内完成，方便高效。

- **文件再大，也能传**

  采用全新的分片上传+断点续传技术，普通浏览器也能轻松传输超大文件。

## 适用场景 {#use-cases}

- **需要优化文件管控流程的大型公司**
  
- **需要低成本部署文件审核系统的中小型公司**

- **需要快速部署一套FTP系统的研发团队**

- **有文件传输需求，但没有IT支撑的非科技类公司**