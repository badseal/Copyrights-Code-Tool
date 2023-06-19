# Copyrights-Code-Tool
用于在中国版权保护中心申请软件著作权时所需的代码文档生成。

github上有很多类似产品，大部分使用起来都或多或少有些问题，自己有很多软著需要申请，所以就写了一个，尽量做到简单易用，且改善了一些不良的用户体验。近期公开代码。

# 当前的代码文档规范
- 前、后各连续30页组成，共60页。程序每页不少于50行。
- 参考：https://www.ccopyright.com/index.php?optionid=1080

# github上现有程序的一些问题
- 生成的文档页数过多，需要手工删除。这并不算什么大问题，但是也会带来工作量的提升。
- 无法选择生成的格式（docx或pdf）

# 本软件的特点
- 代码拖入即可实时识别行数，代码共需要50*60=3000行
- 代码调整：可选是否删除空行、是否删除注释行
- 生成多种文档格式：docx/pdf，以及无格式的txt
- docx和pdf，左上角添加软件名称及版本，右上角添加自动页码
- 文档默认为60页，可手工设置。
