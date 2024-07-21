This manuscript proposes a deep ensemble learning method based sensor for flotation froth image recognition. The experimental results look very good. However, some small issues in this manuscript should be addressed.

1、In line 256, 'pks(li|x) is the fuzzy prediction label', which seems not correct, 'because li is the predicted label'.
2、Because Figure 10 is referenced first, followed by Figure 9, the order of the two figures should be swapped to ensure that their appearance is consistent with the order of their reference.
3、Abbreviations in tables and figures should be included throughout the text or the authors provide literature references when these Abbreviations first appear, such as AVR (in Table 2) and MCTF (in Table 3).
4、'McSV' (in line 399) and 'MCSV' (in Table 3) should be the same abbreviations.
5、Please explain why this method only applies to the recognition of image flotation froth image.


本文提出了一种基于深度集成学习方法的浮选泡沫图像识别传感器。实验结果看起来很不错。然而，本文中还有一些小问题需要解决。

1、在第256行，“pks(li|x)是模糊预测标签”，这似乎是不正确的，“因为li是预测标签”。
2、因为先引用图10，后引用图9，所以两个图的顺序应该互换，以确保它们的外观与它们的引用顺序一致。
3、表格和图形中的缩略语应贯穿全文，或作者在这些缩略语首次出现时提供文献参考，如AVR(表2)和MCTF(表3)。
4、` McSV `(第399行)和` McSV `(表3)应该是相同的缩写。
5、请解释为什么此方法只适用于浮选泡沫图像的识别。以上翻译结果来自有道神经网络翻译（YNMT）· 计算机
 
The paper presents a deep ensemble learning-based sensor designed for flotation froth image recognition. This sensor aims to assist operators in adjusting chemical dosages during the mineral separation process by providing accurate recognition of flotation froth working conditions. The authors use a combination of pre-trained deep neural networks (ViT, Swin Transformer, and EfficientNet) and propose a membership function along with TOPSIS based on F1 score to enhance the recognition accuracy. The methodology is validated with real industrial data from a gold-antimony flotation application, showing significant improvements over traditional methods.

 

The manuscript is well-written, and the research is relevant to the readers of Sensors. However, here are a few recommendations for potential enhancements and considerations that could further strengthen your manuscript:

(1)    Please complete ‘Author Contributions’ section.

(2)   The manuscript primarily validates the proposed method using a dataset from a single industrial application (gold-antimony froth flotation). This limits the generalizability of the findings. Please consider testing on multiple datasets from different types of mineral processing plants. This would strengthen the method’s applicability across various scenarios.

(3)   While the paper demonstrates high accuracy, there is limited discussion on the real-time implementation of the sensor. The latency and processing time required for real-time froth image recognition and decision-making are crucial for practical industrial applications.

(4)   The paper does not thoroughly address the potential for overfitting, especially given the complex models used and the relatively small size of the dataset. Additional techniques to prevent overfitting, such as dropout or data augmentation, could be explored and discussed.

(5)   Although the paper compares the proposed method with classical ensemble learning techniques, it lacks a detailed comparison with other state-of-the-art machine learning methods, such as advanced convolutional neural networks (e.g., ResNet, DenseNet) and transformer-based models in similar applications.

(6)   The scalability of the proposed method to larger datasets or more diverse industrial conditions is not discussed. The ability of the model to maintain performance with an increasing number of classes or more complex froth images needs to be evaluated.

(7)   The robustness of the proposed sensor to noisy or low-quality images, which are common in real-world industrial environments, is not thoroughly investigated. Further analysis on how the sensor performs under suboptimal imaging conditions would be beneficial.

 

(8)   The method’s sensitivity to environmental changes, such as lighting conditions, camera angles, and variations in froth appearance due to different ore properties, is not explored. Such variability could impact the sensor’s performance in practical applications.

提出了一种基于深度集成学习的浮选泡沫图像识别传感器。该传感器旨在通过提供浮选泡沫工作条件的准确识别来帮助操作人员调整矿物分离过程中的化学药剂用量。作者使用了预训练的深度神经网络(ViT、Swin Transformer和EfficientNet)的组合，并提出了一种隶属度函数和基于F1分数的TOPSIS来提高识别精度。通过金锑浮选的实际工业数据验证了该方法的有效性。



手稿写得很好，研究与传感器的读者相关。然而，这里有一些潜在的增强建议和考虑因素，可以进一步加强您的手稿:

(1)请填写“作者贡献”部分。

(2)使用来自单一工业应用(金锑泡沫浮选)的数据集对所提出的方法进行了初步验证。这限制了研究结果的通用性。请考虑在来自不同类型选矿工厂的多个数据集上进行测试。这将加强该方法在各种场景中的适用性。

(3)虽然本文证明了传感器的高精度，但对传感器的实时实现讨论有限。泡沫图像实时识别和决策所需的延迟和处理时间对实际工业应用至关重要。

(4)本文没有彻底解决过拟合的潜在问题，特别是考虑到使用的复杂模型和相对较小的数据集。可以探索和讨论其他防止过拟合的技术，如dropout或数据增强。

(5)虽然将提出的方法与经典的集成学习方法进行了比较，但缺乏与其他先进的机器学习方法的详细比较，如先进的卷积神经网络(如ResNet、DenseNet)和基于transformer的模型在类似应用中的比较。

(6)未讨论所提方法在更大数据集或更多样化工业条件下的可扩展性。随着类别数量的增加或更复杂的泡沫图像，需要评估模型保持性能的能力。

(7)所提出的传感器对现实世界工业环境中常见的噪声或低质量图像的鲁棒性尚未深入研究。进一步分析传感器在次优成像条件下的表现将是有益的。



(8)该方法对环境变化的敏感性，如光照条件、摄像机角度，以及由于矿石性质不同而引起的泡沫外观变化，尚未进行探索。这种可变性会影响传感器在实际应用中的性能。
