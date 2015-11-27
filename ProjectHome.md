> 随着互联网技术向宽带、高速、多媒体方向的发展，人类正快速进入一个信息化的时代。各种信息工具、技术、载体等应运而生。在众多类型的信息资源中，图像具有直观、形象、易于理解和信息量大等特点，成为资源库的重要组成部分。同网络信息一样，由于图像数量巨大，种类繁多，加之排列方式错综复杂，这给图像检索带来了困难。近年来，基于内容的图像检索技术有了长足的发展。基于内容的图像检索能有效的对图像进行管理和检索，这项技术既充分体现了图像的信息特点，又充分结合了传统数据库技术，它的应用对解决信息膨胀，有效快速地利用多媒体信息有很好的实用价值。图像的内容包括图像的颜色、纹理、形状等视觉特征和语义特征。其中，纹理特征作为最为显著的视觉特征之一，它是一种不依赖于颜色或亮度反映图像中同质现象的视觉特征。纹理特征包含了物体表面结构组织排列的重要信息，以及与周围环境的联系。因此在基于内容的图像检索中得到了广泛应用。
svn代码下载完毕之后，可以在R3目录中执行 java -Xmx1024m -jar start.jar启动图片搜索引擎
svn上的代码已经具备采集和搜索能力，访问http://127.0.0.1/admin.rv 可以看到管理后台，页面中部的小加号可以添加本地文件目录，能够采集png、jpg、jpeg、gif、bmp格式的图片，采集完了以后可以从http://127.0.0.1用图片的URL或目录名搜索到，或使用**:**搜索所有。