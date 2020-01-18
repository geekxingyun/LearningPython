# 0x01 LearningPython

## 1.1 基础教程

[https://docs.python.org/3.7/tutorial/index.html](https://docs.python.org/3.7/tutorial/index.html)

[https://docs.python.org/3.7/index.html](https://docs.python.org/3.7/index.html)

## 1.2 第三方类库

 Tryolabs 官网发布了第五届 Python 库 Top 8 年度榜，榜单中所列出的 Python 库在各方面均有所涉及。

  以下为榜单重点内容。

1. HTTPX

   > 这是一个异步 HTTP 客户端。HTTPX 延续了 requests 的用法，它提供了标准特性以及 HTTP/1、HTTP/2 支持。它还支持完全类型注解，支持开发者使用 ASGI 协议直接调用 Python Web 应用程序。如果你需要同时发出大量请求，那么 HTTPX 就是新的首选。

2. Starlette

   > 这是一个轻量级的 ASGI 框架 / 工具包，它的特性包括：高性能、支持 WebSocket 和 GraphQL、进程内后台任务。除此之外，Starlette 还有 100% 类型注解的代码库和无依赖。你可以把它看作是一版非常轻量、现代、异步的 Flask 。

3. FastAPI

   > - 如果你只是需要一个把事情做得又对又快的框架。FastAPI 是一个不错的选择。这款新框架基于 OpenAPI 标准，用于构建具有 Python 高性能特性和自动交互文档的 API。它默认支持 Swagger UI 和 ReDoc ，使你能够直接从浏览器调用和测试你的 API，从而加快开发时间。
   > - FastAPI 还利用了现代 Python 的最佳实践之一：类型提示。它在很多方面都使用类型提示，但是最酷的特性之一是由 Pydantic 提供支持的自动数据校验和转换。

4. Pyodide

   > 它使用 WebAssembly 将 Python 科学栈引入浏览器，将科学计算提升到了一个全新的水平。你可以使用 Pyodide 在浏览器中轻松处理较大的数据流、标制结果。此外，它的 packages 目录列出了超过 35 个当前可用的包。

5. Modin

   > - Modin 的座右铭是通过改变一行代码来扩展你的 Pandas 工作流程，只需安装 Modin，改变你的导入语句，在当下拥有多核处理器的笔记本电脑上就能获得高达 4 倍的速度优势。
   > - 这是因为 Modin 实现了自己的 modin.pandas.DataFrame 对象，它是一个轻量级并行 DataFrame。这个对象的使用是透明的，因为它与 Pandas 是 API 兼容的，并且它在后台运行，使用 Ray 或 Dask 之类的计算引擎来分发数据和计算。

6. Streamlit

   > 在每个重大的机器学习项目中，都有一个需要与模型和数据进行手动交互的时间点。与花费数小时和数千行代码开发应用程序不同，Streamlit 使你能够快速构建应用程序来共享你的模型和分析。
   > Streamlit 能与各种数据科学相关的工具一起工作，如 TensorFlow、Keras、PyTorch、Pandas。

7. Detectron2

   > 它是备受期待的 Detectron 续作，是用 PyTorch 从头开始构建的，装满了最先进的计算机视觉算法。
   > 这样的类库尤其难于进行工程设计，因为它们必须支持不同类型的用例。Detectron2 采用了一种非常灵活和模块化的方式，使得它非常适合计算机视觉的研究应用。同时，它的使用极其简单，对于那些只想快速获得结果而不想干预内部机制的人来说非常理想。

8. Metaflow

   > 这是一个 Python 类库，用于帮助数据科学家和工程师构建用于现实世界的真实项目。它主要专注于减轻非技术数据科学家的技术负担，例如计算资源、并行执行、体系结构设计和版本控制等。Metaflow 使你能够轻松定义复杂的数据流，同时对分布式计算提供开箱即用的支持。
