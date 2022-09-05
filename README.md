# PJSK-MultiGUI

**更快、更简单的进行语音合成**  v1.1.0


v1.1.0更新内容：
- honami,shiho的模型
- 在可能的情况下，GUI直接输出报错而不是闪退

## 下载地址

### 本体

- github的release版本 （更新至v1.1.0)  
- 本体下载：
	- [[Baidu]](https://pan.baidu.com/s/1CbjIF4QztLTj3mj4z_q6Ow?pwd=t4dr)（更新至v1.1.0)  
### 预训练模型
|Character|Version|Google|Baidu|
|:---:|:---:|:---:|:---:|
|ichika|1.0|[ichika](https://drive.google.com/file/d/1_P_2U0TC1U_T3lxxxVW3TuKJ45l2w4Cm/view?usp=sharing)|[ichika](https://pan.baidu.com/s/1oSYX9TTg9COJsabkU3gomg?pwd=m4qf)|
|saki|1.0|[saki](https://drive.google.com/file/d/1zB09x-7qSe-abyxH8NIUZ7lCSYQ4UfEp/view?usp=sharing)|[saki](https://pan.baidu.com/s/15qtkqWib87Ks3OWKm7AFcw?pwd=13dj)|
|honami|1.0|[honami](https://drive.google.com/file/d/152VhjHghjd8W6eV08ah66-xRa9IG0aT1/view?usp=sharing)||
|shiho|1.0|[shiho](https://drive.google.com/file/d/1-7q3pR0HvBdrPdkEmpOmZTQLAyzaiW-I/view?usp=sharing)||
|airi|1.0|[airi](https://drive.google.com/file/d/1uWeixKe5PEz4mGhjS9K8Z8d1AJpv2izO/view?usp=sharing)|[airi](https://pan.baidu.com/s/1w_8yQ9grDcj8Hseo-ovWaA?pwd=sw6p)|
|mizuki|1.0|[mizuki](https://drive.google.com/file/d/1e43kk2SWAeh3EPMAsW-bDdVROsW7VVa8/view?usp=sharing)|[mizuki](https://pan.baidu.com/s/1l_jLQZQiTQbgGTZztUuwBQ?pwd=6sih)|
|ena|1.0|[ena](https://drive.google.com/file/d/1sL9VjWAjPWAS2ilACqcR5WHLCjcF1u4k/view?usp=sharing)|[ena](https://pan.baidu.com/s/1-IYeQ7DdAoD6I2CzlGXSyw?pwd=ej7c)|
|mafuyu|1.0|[mafuyu](https://drive.google.com/file/d/1it_vKoFDVryxzjRbglYvMy6vi2tXTKoO/view?usp=sharing) |[mafuyu](https://pan.baidu.com/s/1G04eZDFJcqm8LCZNbEF9fQ?pwd=b8br)|
|kanade|1.0|[kanade](https://drive.google.com/file/d/16K_R_AWC5tELDpRYaA6DLYucYqfcoho2/view?usp=sharing)|[kanade](https://pan.baidu.com/s/1QPYNsh9qfPDW7mzTpUo5wA?pwd=z5fm)|
|more more jump!|1.1|[mmj](https://drive.google.com/file/d/19BG7vQpjB3oXuWKlOfDluVN0OFzjnzNC/view?usp=sharing) |[mmj](https://pan.baidu.com/s/1UcCsooLr97cHHWXd8P431w?pwd=265a)|
## 关于授权（重要）
- 欢迎同人二创作品，用于PJSK的语音不需要授权，用于其它游戏的角色请提前私信我。但是请勿将语音合成结果直接用于商业目的。
- 二创作品请**注明基于语音合成，并标注语音合成出处**->（B站源视频），并且**禁止**制作会造成对角色产生不良影响的作品。避免造成不必要的误会。

## 使用方法
- clone当前项目到本地，获得config文件
- 按顺序选择config，pth文件
- 选择角色点击确定（只有mmj是四目标）
- 输入文本，生成后点击播放。可以多次生成选择较好的结果保存

## 常见问题
- **第一次生成时被卡住？**

	第一次使用的时候需要从github上下载大约22M左右的压缩包，推荐第一次生成时挂上梯子，不然会很慢。之后就不用了
- 闪退？

	可能出现的问题见下方，如果不能解决您的问题，可以留下Issues，我会尝试解决

## 注意
- 黑白mfy效果时好时坏，谨慎使用
- 播放**点一次就行！**
- 语速调节值**越大**语速**越慢**
- 虽然理论上config文件可以复用，但是config是获取当前角色的手段，所以请一一对应
- 根目录下的playSounds文件夹是为了解决一个小问题而生成的文件夹，打开有可能卡顿，在程序使用结束后可以直接删除
- 保存的音频文件在results文件夹中

## 闪退问题解决方案
- 去掉路径中的中文
- 请按顺序选择config与pth文件
- 不同的模型可以使用的标点符号不太相同，查看是否使用了未设定的标点（主要原因）

	**——同时尝试不同的标点符号也是改变语气的好方法**
	- saki,airi,mzk,knd:!"&*,-.?{}~
	- mmj,ena:_,.!?-~…
	- ick,mfy:_,.!?-
- 输入不带标点的语句
	
## 致谢
- ick,hnm,shiho,mfy模型提供者：没人理 [-Bilibili空间-](https://space.bilibili.com/618272)
- knd模型提供者： 鲤鱼L1yuu [-Bilibili空间-](https://space.bilibili.com/436749613)
- 数据集提供者：涼风_青叶 [-Bilibili空间-](https://space.bilibili.com/5437778)
- 原vits-japanese项目提供者：[CjangCjengh](https://github.com/CjangCjengh) [-Bilibili空间-](https://space.bilibili.com/35285881)
- vits原项目：[vits](https://github.com/jaywalnut310/vits)